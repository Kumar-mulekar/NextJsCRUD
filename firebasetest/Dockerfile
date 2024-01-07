# Use Node.js base image
FROM node:16

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the backend files to the container
COPY . .

# Expose necessary ports for Firebase Emulator (adjust with your emulator ports)
EXPOSE 8080
EXPOSE 5001

# Set environment variables for Firebase Emulator (if needed)
# ENV FIRESTORE_EMULATOR_HOST="host.docker.internal:8080"
# ENV FUNCTIONS_EMULATOR_HOST="host.docker.internal:5001"

# Start Firebase Emulator and backend application using a script
CMD ["npm", "run", "start-emulator"]
