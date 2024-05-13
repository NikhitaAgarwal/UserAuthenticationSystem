## Create a folder Frontend - Add all the folder and files which are in the Forntend folder.

## Create a folder as backend - Add the other remaining files and folder in it.

**Technologies Used**:

Frontend: React, Axios
Backend: Node.js, Express, MongoDB, Mongoose, JWT
Development: Nodemon

SetUp
Frontend Setup:

Clone the Repository: Use git clone <repository-url> to clone the repository.
Navigate to the Frontend Directory: Move to the frontend directory using cd frontend.
Install Dependencies: Run **npm install** to install project dependencies.
Install React Router DOM: Use **npm install react-router-dom** to install React Router DOM.
Start the Frontend Server: Begin the frontend server with npm start.

Backend Setup:

Navigate to the Backend Directory: Change directory to the backend folder with cd backend.
Install Dependencies: Install project dependencies by running npm install.
Install Nodemon Globally: Execute **npm install -g nodemon** to install nodemon globally for development.

Initialize Your Project: If you haven't already done so, create a new directory for your project and navigate into it using your terminal or command prompt.

Initialize npm: Run **npm init -y** to initialize a new Node.js project with default settings. This will create a package.json file in your project directory.

Install Required Packages: Use npm to install the necessary packages. For Express, Mongoose, Axios, and other packages, you can run the following commands:
**npm install express mongoose axios**

This command will install Express, Mongoose, and Axios packages and add them to your package.json file as dependencies.

Install Additional Packages: Depending on your project requirements, you may need to install other packages. For example, if you're using bcrypt for password hashing or JWT for authentication, you can install them as follows:
**npm install bcrypt jsonwebtoken**
Verify Installation: After installing the packages, verify that they are added to your package.json file by checking its content. You can also verify the installation by running your project and ensuring that there are no errors related to missing modules.

Instruction:

Input Validation:
Ensure email format is correct.
Verify password length is at least 6 characters.


### Struture of the project:

frontend: Contains the frontend React code.

           *src: Contains the source code files.
               *components: Contains React components.
                           *Home: Displays user profile information.[ADD Home.js and Home.css in Home folder]
                           *Login: Handles user login functionality.[ADD login.js and login.css in login folder]
                           *Register: Handles user registration functionality.[ADD register.js and register.css in register folder]
           *App.js: Main application component.
*public: Contains public assets and index.html file.

backend: Contains backend server files.
         *index.js: Entry point for the backend server.

Packages Used:
Frontend:

React.js: A JavaScript library for building user interfaces.
react-router-dom: Provides declarative routing for React applications.
axios: A promise-based HTTP client for making requests to the backend server.
react-router-dom: Provides declarative routing for React applications.
CSS Modules: Allows for scoped styling of components.

Backend:

Express.js: A web application framework for Node.js that simplifies the process of building APIs.
Mongoose: An object modeling tool for MongoDB, providing a straightforward schema-based solution to model application data.
bcrypt: A library for hashing passwords to enhance security.
axios: Can also be used on the backend for making HTTP requests to external APIs if needed.
cors: Middleware for Express.js to enable Cross-Origin Resource Sharing (CORS), allowing frontend requests from different origins.
nodemon: A development tool that automatically restarts the server when changes are detected in the source code, improving the development workflow.


### The flow of data from frontend to backend in a MERN stack application involves several steps.

**User Interaction**: Users interact with the website's interface by clicking buttons and filling out forms.
**Data Transmission**: When users submit information, like filling out a registration form, the frontend sends this data to the backend server using HTTP requests.
**Server Processing**: The backend server receives the data, processes it (like checking if the email format is correct or if the password is long enough), and saves it to a database if everything is okay.
**Response Generation**: After processing the data, the backend server sends a response back to the frontend, indicating whether the operation was successful or if there was an error.
If the login is successful, the website will display the user's information, such as their name and email address.

Overview Of Project:

 Register Page
![Register](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/1675cf8c-7a38-4dc4-8327-67dccffab780)

Login Page:

![login](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/f3be3730-ca5f-4acf-8718-fb65f22e05f0)


![Screenshot (149)](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/5e651005-dc95-4a89-9219-76e176549e37)

Home Page

![Homepage](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/e2caf137-5453-4bcd-939b-741c446474e4)

 






