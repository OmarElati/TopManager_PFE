# TopManager_PFE - Fullstack Task Manager (MERN)

## Overview
The **TopManager_PFE** is a cloud-based task management web application designed to streamline team task management. Built using the **MERN stack** (MongoDB, Express.js, React, and Node.js), this platform provides a user-friendly interface for efficient task assignment, tracking, and collaboration. The application caters to administrators and regular users, offering comprehensive features to enhance productivity and organization.

### Problem Statement
In a dynamic work environment, effective task management is crucial for team success. Traditional methods of task tracking through spreadsheets or manual systems can be cumbersome and prone to errors. The Cloud-Based Task Manager addresses these challenges by providing a centralized platform for task management, enabling seamless collaboration and improved workflow efficiency.

### Background
With the rise of remote work and dispersed teams, there is a growing need for tools that facilitate effective communication and task coordination. The Cloud-Based Task Manager meets this need by leveraging modern web technologies to create an intuitive and responsive task management solution. The MERN stack ensures scalability, while the integration of **Redux Toolkit**, **Headless UI**, and **Tailwind CSS** enhances user experience and performance.

## Features

### Admin Features
1. **User Management:**
   - Create admin accounts.
   - Add and manage team members.

2. **Task Assignment:**
   - Assign tasks to individual or multiple users.
   - Update task details and status.

3. **Task Properties:**
   - Label tasks as todo, in progress, or completed.
   - Assign priority levels (high, medium, normal, low).
   - Add and manage sub-tasks.

4. **Asset Management:**
   - Upload task assets, such as images.

5. **User Account Control:**
   - Disable or activate user accounts.
   - Permanently delete or archive tasks.

### User Features
1. **Task Interaction:**
   - Change task status (in progress or completed).
   - View detailed task information.

2. **Communication:**
   - Add comments or chat related to task activities.

### General Features
1. **Authentication and Authorization:**
   - Secure user login with authentication.
   - Role-based access control.

2. **Profile Management:**
   - Update user profiles.

3. **Password Management:**
   - Change passwords securely.

4. **Dashboard:**
   - Provide a summary of user activities.
   - Filter tasks into todo, in progress, or completed.

## Technologies Used
- **Frontend:**
  - React (Vite)
  - Redux Toolkit for State Management
  - Headless UI
  - Tailwind CSS

- **Backend:**
  - Node.js with Express.js

- **Database:**
  - MongoDB for efficient and scalable data storage.

The **TopManager_PFE** is an innovative solution that brings efficiency and organization to task management within teams. By harnessing the power of the MERN stack and modern frontend technologies, the platform provides a seamless experience for both administrators and users, fostering collaboration and productivity.

---

## Setup Instructions

### Server Setup

#### Environment Variables
Create an environment variables file `.env` in the server folder. The `.env` file should contain the following variables:

```bash
MONGODB_URI=your MongoDB URL JWT_SECRET=any secret key - must be secured PORT=8800 or any port number NODE_ENV=development
```

#### Set Up MongoDB
1. **Visit MongoDB Atlas Website:**
   - Go to [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

2. **Create an Account and Log in.**

3. **Create a New Cluster:**
   - Choose a Cloud Provider and Region.
   - Configure Cluster Settings and create the cluster.
   - Wait for the cluster to deploy.

4. **Create Database User and Set Up IP Whitelist.**

5. **Connect to Cluster and Configure Your Application.**

6. **Test the Connection.**

Create a new database and configure the `.env` file with the MongoDB connection URL.

#### Steps to Run Server
1. Open the project in any editor of choice.
2. Navigate to the server directory: `cd server`.
3. Run `npm install` to install the packages.
4. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and the database is connected.

### Client Side Setup

#### Environment Variables
Create an environment variables file `.env` in the client folder. The `.env` file should contain the following variables:

```bash
VITE_APP_BASE_URL=http://localhost:8800
```


#### Steps to Run Client
1. Navigate to the client directory: `cd client`.
2. Run `npm install` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

---

## Contact:
- **Email:** 5796@holbertonstudents.com
