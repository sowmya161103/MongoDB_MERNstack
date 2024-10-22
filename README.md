# Fiverr Application MERN

## Overview
*Fiverr* is a web-based application designed to bridge the gap between clients and freelancers by offering a platform where services across various domains can be offered, requested, and completed efficiently. The platform is built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and provides a seamless experience for both freelancers and clients. Users can post projects, search for freelancers, apply for jobs, and handle payments through a secure system. Additionally, the platform includes real-time updates, ensuring both parties are always up to date on job statuses.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Features
- *Freelancer Profile*: Freelancers can create profiles showcasing their skills, previous work, and reviews from clients.
- *Job Posting*: Clients can post job requirements, and freelancers can browse and apply for jobs.
- *Category-Based Job Search*: Jobs are organized by categories, making it easy for freelancers to find relevant opportunities.
- - *Real-Time Communication*: Users are notified in real-time when job statuses are updated, applications are accepted, or payments are processed, using Socket ID.
- *Secure Payments*: Payments are held in escrow and only released upon completion of the work.
## Technologies Used
- *Frontend*: HTML, SCSS, React.js
- *Backend*: Node.js, Express.js
- *Database*: MongoDB, Mongoose
- *Real-time Communication*: Socket ID

## Installation
To run the Freelansters application locally, follow these steps:

1. Clone the repository:
   git clone ("your github link!)

2. Install the required dependencies for the frontend:
   cd client
   npm install

3. Install the required dependencies for the backend:
   cd ../server
    npm install

4. Create an .env file in the root of your server folder with the following environment variables:
    PORT=
    MONGO_URI=
    SECRET_KEY=
    SOCKET_PORT=
   
6. Start the backend server:
    npm start

7. In another terminal, navigate to the client directory and start the frontend:
   cd client
   npm start

## Usage
Open your web browser and go to http://localhost:3000 to access the application.
Register for a new account or log in if you already have an account.
Browse jobs or post a new job as a client.
Apply for jobs as a freelancer, and wait for client approval.
Communicate with clients/freelancers and manage projects in real-time.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to report issues, please create an issue or submit a pull request.

## Acknowledgements
Inspiration from various freelancing platforms.
Thanks to the open-source community for providing resources and tools.
