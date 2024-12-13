FULL STACK PROJECT

# FashionFusion E-commerce Platform

## Overview
FashionFusion is a full-stack e-commerce platform designed using the MERN stack (MongoDB, Express.js, React.js, and Node.js). This project allows users to browse and purchase products online while providing an admin interface for managing inventory and orders.

---

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation and Setup](#installation-and-setup)
4. [How to Run](#how-to-run)
5. [Folder Structure](#folder-structure)
6. [Future Improvements](#future-improvements)

---

## Features

### User Features
- Product listing with filtering and searching options.
- Product details page.
- Add to cart and checkout functionality.
- User authentication (login and signup).

### Admin Features
- Admin dashboard for managing products and orders.
- Ability to add, update, and delete products.

---

## Technologies Used
- **Frontend**: React.js, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Tools**: Git, Redux (for state management)

---

## Installation and Setup

### Prerequisites
Ensure that you have the following installed:
- Node.js (v16+ recommended)
- MongoDB (running locally or a MongoDB Atlas account)

### Clone the Repository
```bash
git clone https://github.com/jayatiwari12/FashionFusion.git
cd FashionFusion
```

### Install Dependencies
Navigate to the respective directories (frontend, backend, admin) and install dependencies:

#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd frontend
npm install
```

#### Admin Panel
```bash
cd admin
npm install
```

---

## How to Run

### Backend
Start the backend server:
```bash
node ./index.js
```
The backend server will run on `http://localhost:4000` (or the configured port in your project).

### Frontend
Start the frontend server:
```bash
cd frontend
npm start
```
The frontend will run on `http://localhost:3000`.

### Admin Panel
Build and run the admin panel:
```bash
cd admin
npm run build
```
Deploy or serve the admin build as required. If you are running it locally, serve it using a static file server or through a hosting service.

---

## Folder Structure
```
FashionFusion/
├── backend/
│   ├── index.js
│   ├── models/
│   ├── routes/
│   ├── controllers/
├── frontend/
│   ├── src/
│   ├── public/
├── admin/
│   ├── src/
│   ├── build/
```

---

## Additional Features Implemented
- Fully responsive UI.
- State management using Redux for seamless user interactions.
- RESTful APIs for efficient backend communication.
- Secure login and authentication using JWT.

---

## Future Improvements
- Integration of secure payment gateways.
- Real-time order tracking for users.
- Enhanced admin analytics dashboard.
- User review and rating system.

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---

## Author
Developed by [Jaya Tiwari](https://github.com/jayatiwari12). For inquiries or contributions, please contact at jayatiwari9229@gmail.com.

