# TargetTracer

Welcome to TargetTracer , a web application, designed to help users set, track, and manage their personal goals effectively. Users can create accounts, add, read, and delete their goals from a centralized platform.


## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Video Demo](#video-demo)
- [Usage](#usage)
   - [Creating an Account](#creating-an-account)
   - [Adding Goals](#adding-goals)
   - [Reading Goals](#reading-goals)
   - [Deleting Goals](#deleting-goals)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)



## Features
- **User Authentication:** Users can create accounts and log in securely.
- **Goal Management:** Users can add, read, and delete their personal goals.
- **Responsive Design:** The app is designed to be accessible and user-friendly on various devices.

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository

   ````bash
   git clone https://github.com/yash-raj-gupta/TargetTracer.git
   cd TargetTracer
   ````
   
2. Install dependencies for both frontend and backend

   ````bash
   # Install frontend dependencies
   cd frontend
   npm install
   # Install backend dependencies
   cd ..
   npm install
   ````
   
3. Configure the environment variables:
   - Create a .env file outside the 'backend' directory and set the following variables:
     
     ````env
     # Node environment can be development when changing code else production while testing
     NODE_ENV = development/production
     PORT = 5000
     MONGO_URI = your_mongodb_connection_urio
     JWT_SECRET = your_secret_key
     ````
     
4. Start the development server

   ````bash
   # for both frontend and backend 
   npm run dev
   ````


## Video Demo

https://github.com/yash-raj-gupta/TargetTracer/assets/137718338/2e10166c-696e-4879-b6cc-40b4d71da209

## Usage

### Creating an Account

- Visit the app and click on "Register" button.

![Screenshot 2024-03-01 163710](https://github.com/yash-raj-gupta/TargetTracer/assets/137718338/c06a9a97-c511-43c6-90e8-ba80b9da295d)

  
- Fill in the required details and submit the form.
- You will be signed up and redirected to the Dashboard.

### Adding Goals

- Log in with your credentials.
- On the dashboard there is the "Add goal" section.
- Fill in the details of your goal and then submit the form.

  ![new](https://github.com/yash-raj-gupta/TargetTracer/assets/137718338/341df48a-9a44-4549-bc3b-8df93b50062f)


### Reading Goals

- After loggin in, you can view your existing goals on the dashboard.
  
![Screenshot 2024-03-01 163741](https://github.com/yash-raj-gupta/TargetTracer/assets/137718338/479118f4-20f4-44d6-82cc-f82a5f1550cc)

### Deleting Goals

- On the dashboard where the goals are visible there is a icon on the goals container itself.
- Clicking on the `X` icon the goal will be removed.

![Screenshot 2024-03-01 163741](https://github.com/yash-raj-gupta/TargetTracer/assets/137718338/268d3346-35ec-41e2-8d20-0b06374ccdea)

## Technologies Used

- Frontend:
 <p><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> 
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40"/>
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></p>

- Backend:
 <p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> 
  </p>
  

## Contributing

If you find any issues, have suggestions, or want to contribute to the development of this project, feel free to open an issue or submit a pull request on the GitHub repository.
