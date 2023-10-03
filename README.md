# GitMatch Web Application

GitMatch is a web application designed to help students and developers connect with potential teammates for hackathons and collaborate on exciting projects. This README provides an overview of the project and instructions for getting started.

## Table of Contents

- [Project Structure](#project-structure)
- [Getting Started](#getting-started)

## Project Structure

### Folders:

1. **gitmatch-recommendation**
   - This folder contains the Machine Learning model responsible for the Resume-Ranker feature. It assesses how well a user's resume matches a job description, aiding job seekers in today's competitive market.

2. **gitmatch-slide**
   - The React component for the sliding functionality of user profiles is located here. It enables users to browse and connect with potential collaborators based on specific skills and preferences.

3. **gitmatch-registration-login**
   - This folder houses the backend logic for user authentication and registration, developed using Node.js. It ensures the security and functionality of user accounts and access to GitMatch's features.

## Getting Started

To start a basic version of the GitMatch web application, follow these steps:

1. **Set Up Your Development Environment:**
   - Install a code editor (e.g., Visual Studio Code).
   - Install Node.js and npm from [nodejs.org](https://nodejs.org/).

2. **Create Your Project Folder:**
   - Create a new folder for your project.

3. **Initialize Your Node.js Project:**
   - Open your terminal and navigate to your project folder.
   - Run `npm init -y` to initialize a new Node.js project.

4. **Set Up the Frontend:**
   - Create a new React application using Create React App or your preferred setup method. If you haven't installed Create React App, you can do so with `npx create-react-app gitmatch-frontend`.
   - Navigate to your React app's directory using `cd gitmatch-frontend` (replace "gitmatch-frontend" with your preferred project name).
   - Inside your React app folder, you'll find the following files and folders:
     - `src` folder: This is where you'll place your React components and JavaScript logic.
     - `public` folder: This is where your `index.html` file is located.
     - `src/index.js`: This is the entry point for your React application.

   - Create React components as needed for your GitMatch frontend in the `src` folder.
   - Add CSS styles as required. You can use regular CSS files or CSS-in-JS libraries like styled-components.
   - Place your JavaScript logic and component interactions in the appropriate React components within the `src` folder.

   - Link your CSS and JavaScript (React) files within your React components as necessary. React components typically import and use CSS and other JavaScript files directly within the component files.

   - Start your React development server by running `npm start`. This will launch your React app, and you can access it in your web browser at `http://localhost:3000` by default.


5. **Set Up a Simple Node.js Server:**
   - Create a Node.js file (e.g., `server.js`) for your backend.
   - Install `express` using `npm install express`.

6. **Start Your Application:**
   - Run your Node.js server with `node server.js`.
   - Access your web app at `http://localhost:3000`.


