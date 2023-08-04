MERN File Sharing
-

The MERN File Sharing repository is a full-stack web application that allows users to securely share files with others. It is built using the MERN stack (MongoDB, Express, React, Node.js), which provides a robust and scalable foundation for developing modern web applications with file-sharing capabilities.

Features
-
Upload files securely to the server.
Generate unique and shareable links for each uploaded file.
Download files using the provided links.



Technologies Used
MongoDB: A NoSQL database used to store file metadata and paths.
Express: A flexible and minimalistic web application framework for Node.js.
React: A popular JavaScript library for building user interfaces.
Node.js: A server-side JavaScript runtime environment.
Multer: A middleware for handling file uploads in Node.js.

Installation and Setup
-
Clone this repository to your local machine using:

Copy code
git clone https://github.com/MicoDan/file_sharing.git


Install the required dependencies for both the server and client:
-
cd server
npm install
cd client
npm install

Create a .env file in the root of the project and provide the necessary environment variables:
-
env
Copy code
MONGODB_URI=your_mongodb_connection_string
PORT = your_port

Run the development server and client concurrently:
-

npm run dev
Open your browser and access the application at http://localhost:3000.

Folder Structure
-
client: Contains the frontend code (React).
server: Contains the backend code (Node.js and Express).
public: Static assets and the HTML template for the React app.
Contributing
Contributions are always welcome! If you find any bugs or want to improve the file-sharing capabilities, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
