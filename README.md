# Expense-Tracker-Web-App-SIP-Project-
This is a demo site for Expense Tracking App created under the SIP Project
Expense Management System using MERN Stack

Live Website: https://main.d1sj7cd70hlter.amplifyapp.com/

Vercel Link: https://expense-tracker-app-three-beryl.vercel.app/

Project Description:
The Expense Management System is a web-based application designed to assist users in tracking and managing their daily expenses. This system is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to create a scalable, responsive, and user-friendly application.

Objectives:
1. Simplify expense tracking for individuals and organizations.

2. Provide detailed insights into spending patterns to enable better financial management.

3. Offer a platform for users to create, update, and delete expenses and categories.

4. Generate comprehensive reports based on user-defined time periods and categories.

Features
User Authentication and Authorization:

Allow users to sign up and log in to their personal accounts using secure authentication mechanisms. Implement role-based access control for administrative tasks.

Expense and Category Management:

Enable users to create, update, and delete expense entries and categories. Track expenses by date, category, and description. Support attaching receipts or other relevant documents to expense entries.

Dashboard and Reporting:

Provide a visual dashboard displaying an overview of the user's expenses, including total expenses, expenses by category, and recent transactions.

Generate reports based on selected date ranges and categories, displaying pie charts and bar graphs to help users understand their spending patterns.

Responsive User Interface:

Design a clean, responsive user interface that works seamlessly across desktop, tablet, and mobile devices.

Utilize React.js for building reusable UI components and managing state effectively.


Technical Architecture:

Frontend:

Utilize React.js for building the user interface, tsparticle library for awesome background effect and used other libraries like unique-names-generator, react-datepicker, moment

Implement responsive design using CSS frameworks like Bootstrap and Material-Icons.

Backend:

Use Node.js and Express.js to build a RESTful API for handling client requests and serving as the application's backend.

Implement authentication and authorization using JSON Web Tokens (JWT) and middleware to protect endpoints.

Database:

Store all data, including user information, expense entries, and categories, in MongoDB, a NoSQL database.

Implement Mongoose ORM for schema definition and validation.

Deployment:

Deploy the application to a cloud provider like AWS and render. frontend has deployed on AWS and backend on Render.

Set up Continuous Integration and Continuous Deployment (CI/CD) pipelines for automated builds and deployments.

Run Locally
Clone the project

  git clone https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project
Go to the project directory

  cd Expense-Tracker-App
Go to the frontend directory and Install dependencies

  cd frontend
  npm install
Go to the backend directory and Install dependencies

  cd backend
  npm install
Start the frontend server

  npm start
Start the backend server

  npm run dev
Environment Variables
To run this project, you will need to add the following environment variables to your .env file in backend folder

create config folder and add config.env file in it and all all env variables there.

MONGO_URL : Your MongoDB Connection String

PORT: PORT number

Tech Stack
Client: React, Redux, react-bootstrap, Material Icons, tsparticles

Server: Node, Express

Database: MongoDB

Screenshots
![image](https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project-/assets/94465426/e42461ce-4121-49ee-9cad-fa5573321a59)


![image](https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project-/assets/94465426/e664d4cc-f589-4500-933b-005006de906e)


![image](https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project-/assets/94465426/bfa620f3-20ec-4fa9-9978-ee6aa40c818a)


![image](https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project-/assets/94465426/62f4711c-d045-4660-937b-d416b78f0bad)


![image](https://github.com/Equinox1704/Expense-Tracker-Web-App-SIP-Project-/assets/94465426/bd078793-33ae-4945-95e4-7ae102aaed89)
