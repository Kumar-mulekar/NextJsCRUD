# Use Node.js base image
FROM node:20

# Set working directory
WORKDIR /app

# Copy package.json and yarn.lock to the container
COPY package.json yarn.lock ./

# Install dependencies using Yarn
RUN yarn install

# Copy the rest of the frontend files to the container
COPY . .

# Build the Next.js application (replace with your Yarn command)
CMD ["yarn", "dev"]
