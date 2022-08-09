# Mern-Stack-Booking-Application
Built with the MERN stack (MongoDB, Express, React and NodeJS) and Stripe

## Introduction
This is a side project I've been working on. A full stack booking application made using the MERN stack (MongoDB, Express, React & Nodejs), specially designed for a Marketplace App with similar concept used by sites like eBay, E-commerce Marketplace, Online Service Booking ,Hotel Booking etc.
With this application, I have been harnessing the power of JavaScript with React Redux Node MongoDB and Stripe to build a Global Marketplace.

## Key Features
- Allow users to post services/products on the site
- Let users buy those products/services.
- As a platform owner, you will collect money from customers and pay to sellers.
- In-between you will take certain percentage/commission/fee for being a platform owner.
- You will host two different types of users in your app. one is seller who will sell products or services, for example a hotel owner who will post his hotel rooms available for booking. Other type is buyer who will buy products or services, for example a user who want to book a hotel room.
- The entire payment flow will be automated using stripe. When a customer pays using their credit card, stripe will allocate certain percentage to the seller and certain percentage to the platform owner (platform fee). Then every week, stripe will automatically pay the balance to the account holders directly to their bank account.
- Authentication using jsonwebtoken (jwt).

## Technologies used
This project was created using the following technologies.

#### Client

- React JS
- Redux (for managing and centralizing application state)
- React-router-dom (To handle routing)
- Axios (for making api calls)
- Material UI & CSS Module (for User Interface)

#### Server
- Express
- Mongoose
- JWT (For authentication)
- bcryptjs (for data encryption)

#### Database
MongoDB (MongoDB Atlas)

## Configuration and Setup
In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine. 
- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the client on one terminal and the server on the other terminal)

## Comment
I intend to keep adding more features to this application, so if you like it, please give it a star, that will encourage me to 
to keep improving the project.


## Author

- Github: [@deepak](https://github.com/saideepakreddy0308)
- Email: [@deepak](mailto:saideepakreddy0308@gmail.com)

## License

- This project is [MIT](https://github.com/saideepakreddy0308/Mern-Stack-Booking-App/blob/main/LICENSE) licensed.
