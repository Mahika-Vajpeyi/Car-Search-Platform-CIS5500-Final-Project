# Database Systems Project

## Goal
This platform provides users with one place to access detailed car sales information, conduct easy comparisons, and personalize their search experience. Through this platform, users can explore and understand the pre-owned car market across the United States from 1999 to 2022. 

On the homepage, users will find various statistics, such as the total number of available used cars and their average prices, both nationally and broken down by city and state. They can then refine their search using filters such as location, make, model, condition, year, and color to view cars that match their preferences. Additionally, there’s a budget slider to help users find cars that fit their wallet. The goal is to make buying a car easier and more enjoyable.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have npm installed on your system. npm is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js.

### Setting up and Running the Client

1. **Navigate to the Client Folder**

   ```bash
   cd path/to/client
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Client**

   ```bash
   npm start
   ```

   This command will start the client-side application and usually will open the default web browser displaying the application. If it doesn't automatically open, you can manually visit `http://localhost:3000` in your web browser.

### Setting up and Running the Server

1. **Navigate to the Server Folder**

   ```bash
   cd path/to/server
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Server**

   ```bash
   npm start
   ```

   This command runs the server. By default, the server will run on `http://localhost:5000`.

## Using the Application

After both the client and server are running, you can use the application by accessing the client through your web browser at `http://localhost:3000`. Ensure the server is running simultaneously to handle requests from the client.

## Additional Information

- **Client Details:** The client part of this project is built using React.js. It interacts with the server via HTTP requests.
- **Server Details:** The server is set up using Node.js and Express. It handles all backend logic including database interactions and API services.
