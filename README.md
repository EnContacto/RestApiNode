# RestApiNode
 Application built in Node.js using the RestAPI architecture. 
 This is a simple application with **REST API** architecture developed in **Node.js** using the **Express.js** framework. The application exposes a basic endpoint    
 that returns a welcome JSON message.

## Features

- Endpoint `GET /hello` that responds with a JSON message: `{ message: “Hello, World!” }`.

## Prerequisites

Before you start, make sure you have the following tools installed on your system:

- [Node.js](https://nodejs.org/) (version 16 or higher recommended).
- [npm](https://www.npmjs.com/) (installed automatically with Node.js)

## Steps to Download and Run the Project

1. **Clone the Repository**.  
   Clone this repository on your local machine using the command:
   ```bash
   git clone https://github.com/EnContacto/RestApiNode.git
   cd RestApiNode
2. **Install Dependencies**.
   Once you are in the project directory, install the necessary dependencies by running:
   ```bash
   npm install
3. **Running the Server**
   To start the server in development mode, use:
   ```bash
   node server.js
  Esto iniciará el servidor en http://localhost:3000.
4. **Testing the Endpoint**
   Open your browser or a tool like Postman or cURL and make a `GET` request to the following endpoint:
   `http://localhost:3000/hello`
  You should get the following response:
  `{
  "message": "Hello, World!"
   }`
##Project Structure.
   The project has the following basic structure:
   ```bash
 📁 project-restapi
 ┣ 📄 server.js # Main server code.
 ┣ 📄 package.json # Dependencies and script configuration
 ┗ 📄 README.md # Documentation of the project

