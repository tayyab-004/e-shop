# E Shop

Welcome to the E Shop project! This repository contains a full-fledged e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js).

## Features

- **User Authentication**: Secure login and registration functionality.
- **Product Management**: Admin capabilities to add, edit, and delete products.
- **Shopping Cart**: Add products to the cart and manage quantities.
- **Order Processing**: Place orders and view order history.
- **Responsive Design**: Optimized for various screen sizes.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/tayyab-004/e-shop.git
   ```

2. **Navigate to the project directory**:

   ```
   cd e-shop
   ```

3. **Install dependencies**:

   ```
   npm install
   ```

4. **Install dependencies for both client and server**:

   ```
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

5. **Set up environment variables**:

   Create a `.env` file in the `server` directory with the following content:

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

6. **Start the development**:

   ```
   cd e-shop
   npm start
   ```

   The client will be accessible at `http://localhost:5173` and the server at `http://localhost:5000`.
