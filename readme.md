<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
  <h1>CRUD using NextJs</h1>

  <p>This project consists of a frontend and backend application for managing user data using Google Cloud Functions, Firestore, Next.js, Tailwind CSS, TypeScript, and Docker.</p>

  <h2>Frontend</h2>

  <h3>Overview</h3>
  <p>The frontend of this application is built using Next.js, Tailwind CSS, and TypeScript. It interacts with a Google Cloud Functions API to perform CRUD operations for user data.</p>

  <h3>Features</h3>
  <ol>
    <li><strong>Dashboard Page:</strong> Displays user data fetched from the Google Cloud Functions API.</li>
    <li><strong>CRUD Operations:</strong> Supports Create, Read, Update, and Delete operations for user data.</li>
    <li><strong>Styling with Tailwind CSS:</strong> Utilizes Tailwind CSS for styling to ensure responsiveness and a consistent design.</li>
    <li><strong>Type Safety:</strong> Implements TypeScript for improved code quality and type safety.</li>
    <li><strong>Docker Containerization:</strong> The frontend application is containerized using Docker for easier deployment.</li>
  </ol>

  <h3>Getting Started</h3>
  <ol>
    <li>Clone this repository.</li>
    <li>Navigate to the <code>frontend</code> directory.</li>
    <li>Install dependencies using <code>npm install</code>.</li>
    <li>Run the application using <code>npm run dev</code>.</li>
    <li>Access the application on <a href="http://localhost:3000">http://localhost:3000</a>.</li>
  </ol>

  <h2>Backend</h2>

  <h3>Overview</h3>
  <p>The backend of this application is developed using Google Cloud Functions and Firestore as the database. It serves as the API layer for managing user data.</p>

  <h3>Features</h3>
  <ol>
    <li><strong>Google Cloud Functions:</strong> Utilizes Google Cloud Functions for API development.</li>
    <li><strong>Firestore Database:</strong> Deploys user data on Firestore as the database.
<!--       <ul>
        <li><strong>Note:</strong> Use Firebase Emulator for local development.</li>
      </ul> -->
    </li>
  </ol>

  <h3>Setup and Deployment</h3>
  <p>To deploy the backend:</p>
  <ol>
    <li>Set up Google Cloud Functions for API development.</li>
    <li>Use Firestore as the database for storing and managing user data.</li>
    <li>Ensure to use the Firebase Emulator for local development and testing.</li>
  </ol>

  <h3>API Endpoints</h3>
  <ul>
    <li><strong>GET /users</strong>: Retrieves a list of all users from the Firestore database.</li>
    <li><strong>POST /users</strong>: Adds a new user to the Firestore database.</li>
    <li><strong>PUT /users/:id</strong>: Updates an existing user's details based on the provided ID.</li>
    <li><strong>DELETE /users/:id</strong>: Deletes a user from the Firestore database based on the provided ID.</li>
  </ul>
</body>

</html>
