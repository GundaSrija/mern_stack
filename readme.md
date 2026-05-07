# MERN Stack E-Commerce Application

## Overview

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) e-commerce web application with user authentication, product management, shopping cart functionality, and responsive UI.

---

## Features

* User Authentication & Authorization
* JWT-based Login and Registration
* Product Listing and Search
* Shopping Cart Functionality
* Responsive User Interface
* REST API Integration
* MongoDB Database Connectivity
* Admin Product Management
* Secure Backend Routes

---

## Tech Stack

### Frontend

* React.js
* Redux / Context API
* HTML5
* CSS3
* JavaScript
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt.js

---

## Folder Structure

```bash
mern-stack/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── package.json
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/GundaSrija/mern-stack.git
```

### Navigate to Project

```bash
cd mern-stack
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

## Environment Variables

Create a `.env` file inside the backend folder.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## Run the Application

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm start
```

---


---

## API Endpoints

| Method | Endpoint            | Description       |
| ------ | ------------------- | ----------------- |
| POST   | /api/users/login    | User Login        |
| POST   | /api/users/register | User Registration |
| GET    | /api/products       | Get Products      |
| POST   | /api/cart           | Add to Cart       |

---

## Future Enhancements

* Online Payment Integration
* Order Tracking
* Wishlist Functionality
* Product Reviews & Ratings
* Dark Mode Support

---

## Author

**Srija Gunda**

GitHub: [https://github.com/GundaSrija](https://github.com/GundaSrija)

---

## License

This project is developed for learning and portfolio purposes.
