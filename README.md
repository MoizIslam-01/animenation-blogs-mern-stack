Project Summary for Animenation Blogs (MERN Stack Application)
________________________________________
1. Project Overview
Animenation Blogs is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The primary objective of this project is to provide a platform where users can create, read, update, and delete (CRUD) blogs related to anime. The application includes user authentication and role-based access, ensuring only authorized users can manage content.
________________________________________
2. Features
•	User Authentication:
Users can register, log in, and manage their own blogs. Authentication is implemented using JWT (JSON Web Tokens).

•	Blog Management:
Users can create new blogs, edit existing ones, delete blogs, and view a list of all available blogs.
Each blog contains a title, description, and author details.
•	Pages:
o	Home Page: Displays a list of all blogs.
o	Blog Details Page: Shows detailed information about a specific blog.
o	User Blogs Page: Lists all blogs created by the logged-in user.
o	Create/Edit Blog Page: Allows users to create or update blogs.
o	Authentication Pages: Includes login and registration pages.
________________________________________
3. Technologies Used
•	Frontend:
o	React.js: Used to build the user interface.
o	Redux: For state management.
o	Axios: For making API requests.
o	CSS: Styling the application.
•	Backend:
o	Node.js & Express.js: To handle server-side logic and API routes.
o	MongoDB: For storing user data and blog content.
o	Mongoose: For interacting with the MongoDB database.
•	Additional Tools:
o	JWT (JSON Web Tokens): Used for secure authentication.
o	Bcrypt.js: For hashing user passwords.
o	Postman: For API testing during development.
________________________________________
4. File Structure
•	Root Directory: Contains the main server file (server.js), configuration files, and backend-related folders.
•	client/: Contains all React.js files for the frontend.
o	components/: Reusable components like Header and BlogCard.
o	pages/: Different pages for routing, such as Blogs, CreateBlog, Login, and Register.
o	redux/: Store configuration for managing the application's state.
•	controllers/: Contains controller files for handling logic related to users and blogs.
•	routes/: Defines routes for blog and user-related APIs.
•	models/: Contains Mongoose models for users and blogs.
•	config/: Database configuration file.
________________________________________
5. How to Run the Project
1.	Backend Setup:
o	Navigate to the root directory.
o	Run npm install to install server dependencies.
o	Set up a .env file with required variables (MongoDB URI, JWT secret, etc.).
o	Run npm start to start the backend server.
2.	Frontend Setup:
o	Navigate to the client/ directory.
o	Run npm install to install frontend dependencies.
o	Run npm start to start the React development server.
o	Access the application at http://localhost:3000.
