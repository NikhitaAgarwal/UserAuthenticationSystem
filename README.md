Create a folder Frontend - Add all the folder and files which are in the Forntend folder.
Create a folder as backend - Add the other remaining files and folder in it.

Technologies Used:

Frontend: React, Axios
Backend: Node.js, Express, MongoDB, Mongoose, JWT
Development: Nodemon

SetUp
Frontend Setup:

Clone the Repository: Use git clone <repository-url> to clone the repository.
Navigate to the Frontend Directory: Move to the frontend directory using cd frontend.
Install Dependencies: Run npm install to install project dependencies.
Install React Router DOM: Use npm install react-router-dom to install React Router DOM.
Start the Frontend Server: Begin the frontend server with npm start.

Backend Setup:

Navigate to the Backend Directory: Change directory to the backend folder with cd backend.
Install Dependencies: Install project dependencies by running npm install.
Install Nodemon Globally: Execute npm install -g nodemon to install nodemon globally for development.

Initialize Your Project: If you haven't already done so, create a new directory for your project and navigate into it using your terminal or command prompt.

Initialize npm: Run npm init -y to initialize a new Node.js project with default settings. This will create a package.json file in your project directory.

Install Required Packages: Use npm to install the necessary packages. For Express, Mongoose, Axios, and other packages, you can run the following commands:
npm install express mongoose axios

This command will install Express, Mongoose, and Axios packages and add them to your package.json file as dependencies.

Install Additional Packages: Depending on your project requirements, you may need to install other packages. For example, if you're using bcrypt for password hashing or JWT for authentication, you can install them as follows:
npm install bcrypt jsonwebtoken
Verify Installation: After installing the packages, verify that they are added to your package.json file by checking its content. You can also verify the installation by running your project and ensuring that there are no errors related to missing modules.

Instruction:
Input Validation:

Ensure email format is correct.
Verify password length is at least 6 characters.


Struture of the project:

frontend: Contains the frontend React code.

           *src: Contains the source code files.
               *components: Contains React components.
                           *Home: Displays user profile information.
                           *Login: Handles user login functionality.
                           *Register: Handles user registration functionality.
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


The flow of data from frontend to backend in a MERN stack application involves several steps.

Firstly, users interact with the frontend interface by navigating through views and interacting with various components such as forms and buttons. When users submit forms or trigger actions, the frontend components handle these interactions and prepare data for transmission to the backend.
Next, the frontend code prepares an HTTP request, typically using the axios library, and sends it to the backend server. This request contains relevant data, such as user input from forms, in the request payload.
Upon receiving the request, the backend server routes it to the appropriate endpoint using Express.js routing. The backend route handler then extracts the data from the request payload and processes it according to the application's business logic.
After processing the request, the backend generates a response, which is sent back to the frontend. This response can include data or error messages based on the outcome of the request processing.

Finally, the frontend code receives the response and updates the user interface accordingly. For example, if the request was successful, the frontend may display a success message and navigate to a different page. If there was an error, it may display an error message to the user.
Overall, this flow ensures seamless communication between the frontend and backend components of a MERN stack application, enabling users to interact with the application effectively.

Overview Of Project:

 Register Page
![Register](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/1675cf8c-7a38-4dc4-8327-67dccffab780)

Login Page:

![login](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/f3be3730-ca5f-4acf-8718-fb65f22e05f0)


![Screenshot (149)](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/5e651005-dc95-4a89-9219-76e176549e37)

Home Page

![Homepage](https://github.com/NikhitaAgarwal/UserAuthenticationSystem/assets/96190789/e2caf137-5453-4bcd-939b-741c446474e4)

 






