


<h1 align="center">
  <br>
  <a href='https://postimg.cc/nC7cCMGw' target='_blank'><img src='https://i.postimg.cc/nC7cCMGw/logo-green-round.png' border='0' alt='logo-green-round' height="180" width="180"/></a>
  <br>
  Natours App
  <br>
  <br>
  <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="56" height="56" alt="NodeJS" /></a>
<a href="https://expressjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored.svg" width="56" height="56" alt="Express" /></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="56" height="56" alt="MongoDB" /></a>
</h1>




<p align="center">
  <a href="#project-description">Project Description</a> |
  <a href="#tech-stack-and-libraries">Tech Stack and Libraries</a> |
  <a href="#how-it-works">How it Works</a> |
  <a href="#features">Features</a> |
  <a href="#screenshots">Screenshots</a> |
  <a href="#acknowledgements">Acknowledgements</a>
</p>

[![Thumbnail-10.png](https://i.postimg.cc/BbkMC26m/Thumbnail-10.png)](https://postimg.cc/QKgQ89c7)


<div id="project-description"></div>

## 🚀 Project Description
This project is the final project for the "Node.js, Express, MongoDB & More: The Complete Bootcamp 2023" course on Udemy. It is a full-stack web application built using Node.js, Express, and MongoDB, that implements a RESTful API for a fictional online store. The application includes features such as user authentication, CRUD operations for products and users, and integration with third-party services such as Stripe for accepting payments.

<div id="tech-stack-and-libraries"></div>

## 🛠️ Tech Stack and Libraries
- Node.js
- Express.js
- MongoDB
- Mongoose
- Pug
- JSON Web Tokens (JWT)
- Stripe
- SendGrid
- Mailtrap
- Heroku

<div id="how-it-works"></div>

## ⚙️ How it Works

This application uses the MVC (Model-View-Controller) architecture, with routes defined in the "routes" directory, controllers defined in the "controllers" directory, and views defined in the "views" directory. The app.js file initializes the Express application and connects to the MongoDB database.

The API includes endpoints for authentication, CRUD operations for products and users, and payment processing with Stripe. User passwords are hashed and encrypted with bcrypt, and JSON Web Tokens (JWT) are used for user authentication and authorization.

The application also includes error handling workflows, file uploading and image processing, and email sending with SendGrid and Mailtrap.

To run the application locally, clone the repository and run "npm install" to install the required dependencies. Then, create a .env file with your environment variables (such as database URL, Stripe API keys, and email service credentials) and run "npm start" to start the application.

To deploy the application to production, you can use the Heroku platform and connect it to your GitHub repository

<div id="features"></div>

## 💡 Features
**- User authentication and authorization:** Allow users to sign up, log in, and log out securely, and implement access control based on user roles.

**- RESTful API with advanced features:** Implement filtering, sorting, aliasing, and pagination to make your API more powerful and flexible.

**- Server-side website rendering with Pug templates:** Generate dynamic HTML pages on the server and send them to the client, allowing for faster page loads and better SEO.

**- CRUD operations with MongoDB:** Perform Create, Read, Update, and Delete operations on a MongoDB database, both locally and in the cloud.

**- Advanced MongoDB features:** Use geospatial queries, aggregation pipeline, and operators to manipulate and analyze your data more effectively.

**- Mongoose data modeling:** Define data models for your MongoDB collections, including data validation, middleware, and advanced features such as populates and virtual populates.

**- MVC architecture:** Use the Model-View-Controller design pattern to organize your code and separate concerns.

**- NoSQL data modeling:** Learn how to model relationships between data, including embedding and referencing, and decide which approach is best for your use case.

**- JWT-based authentication:** Use JSON Web Tokens to authenticate and authorize users, and provide secure access to protected resources.

**- Stripe integration:** Accept credit card payments on your website by integrating with Stripe's payment processing API.

**- File uploads and image processing:** Allow users to upload files and images to your server, and process them as needed using libraries such as Multer and Sharp.

**- Email sending:** Send emails to users using services such as Mailtrap and SendGrid, and handle email errors and bounces.

**- Error handling:** Implement robust error handling workflows to catch and handle errors effectively, both on the server and on the client.


<div id="screenshots"/>

## 📷 Screenshots
[![Safari-Browser-11.png](https://i.postimg.cc/xjPwD1p8/Safari-Browser-11.png)](https://postimg.cc/LhnCj2pF)

<br>

[![Safari-Browser-14.png](https://i.postimg.cc/Jzjgx7XR/Safari-Browser-14.png)](https://postimg.cc/SnNDNhVP)

[![Safari-Browser-13.png](https://i.postimg.cc/dQ8yJzGL/Safari-Browser-13.png)](https://postimg.cc/gr2JDtSW)

[![Safari-Browser-12.png](https://i.postimg.cc/hGy0bN2S/Safari-Browser-12.png)](https://postimg.cc/WDZrsYRK)

[![Safari-Browser-15.png](https://i.postimg.cc/yd3rJV7q/Safari-Browser-15.png)](https://postimg.cc/S2qG3bXV)

<div id="acknowledgements"></div>

## 📚 Acknowledgements 
This project was created with the help of the course **"Node.js, Express, MongoDB & More: The Complete Bootcamp 2023"** by **Jonas Schmedtmann**. Many of the concepts and techniques used in this project were learned from this valuable resource.
