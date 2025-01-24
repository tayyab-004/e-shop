# E Shop

Welcome to **E Shop**, a complete e-commerce application built using the MERN stack. This project includes an admin panel for managing products, orders, and homepage banners. It offers a seamless shopping experience for users and streamlined management for the admin.

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Environment Variables](#environment-variables)
5. [Usage](#usage)

---

## Features

### User Features:
- **🔒 Authentication**: Secure login and registration.
- **📚 Product Browsing**: View, filter, and sort products by category, brand, and price.
- **👀 Product Details**: Check product descriptions, ratings, and reviews.
- **🛒 Shopping Cart**: Add, update, or remove items from the cart.
- **💳 Checkout**: Manage addresses and place orders securely using PayPal.
- **📊 Order Management**: View order history and statuses.
- **⭐ Review Products**: Leave reviews and ratings after confirmed orders.

### Admin Features:
- **📊 Dashboard**: Redirected to a dedicated admin dashboard upon login.
- **🎨 Banner Management**: Upload and update homepage banners.
- **📚 Product Management**: Create, read, update, and delete products.
- **📄 Order Management**: View details and update order statuses (Confirmed, Pending, or Rejected).
- **🔐 Single Admin Role**: Admin role can only be modified directly in the database.

### General Features:
- **🌐 Responsive Design**: Fully optimized for all devices using Tailwind CSS.
- **🔊 Interactive Icons**: Enhanced user experience with Lucide-react icons.

---

## Tech Stack

### Front-End:
- **React.js**
- **Redux Toolkit**: For state management and data caching.
- **Axios**: For API requests.
- **Lucide-react**: Interactive icons.
- **Shadcn**: Components and toast messages.
- **React Router DOM**: Multi-page navigation.
- **Tailwind CSS**: Styling and responsiveness.
- **Vite**: Development build tool.

### Back-End:
- **Node.js**
- **Express.js**
- **MongoDB with Mongoose**: Database and ODM.
- **bcryptjs**: Password hashing.
- **jsonwebtoken**: Token-based authentication.
- **Cloudinary**: Image upload and storage.
- **Multer**: Handling file uploads.
- **PayPal REST SDK**: Payment processing.
- **Cors**: Cross-origin resource sharing.
- **Dotenv**: Environment variable management.
- **Nodemon**: Development server monitoring.
- **Cookie-parser**

---

## Installation

To run this project locally, follow these steps:

### 1. Clone the Repository:
```
git clone https://github.com/tayyab-004/e-shop.git
```

### 2. Navigate to the Project Directory:
```
cd e-shop
```

### 3. Install Dependencies:

```
npm install
```

#### For the server:
```
cd server
npm install
```

#### For the client:
```
cd client
npm install
```

## Environment Variables

### 4. Set Up Environment Variables:

Create a `.env` file in the `server` directory with the following variables:

```
CLIENT_ORIGIN=http://localhost:5173
PORT=5000
MONGO_URI=YOUR_MONGO_URI
CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET
PAYPAL_MODE=sandbox
PAYPAL_CLIENT_ID=YOUR_PAYPAL_CLIENT_ID
PAYPAL_CLIENT_SECRET=YOUR_PAYPAL_CLIENT_SECRET
```

### 5. Start the Development Servers:

#### Run both client and server:
```
npm start
```

- The client will be accessible at `http://localhost:5173`
- The server will run on `http://localhost:5000`

---

## Usage

- **Admin Access**: Log in as an admin to access the dashboard and manage the application.
- **User Experience**: Browse, filter, and purchase products seamlessly.
- **Payment**: Secure checkout using PayPal integration.

---

Feel free to contribute to the project and enhance its functionality. For any questions or issues, please open an issue in the repository. Enjoy building with **E Shop**!
