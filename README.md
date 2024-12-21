# full-stack-e-commerce Website (MERN Stack)

Welcome to the **E-Commerce Website** repository! This project is a full-stack e-commerce platform built using the **MERN** stack (MongoDB, Express.js, React, Node.js). It allows users to browse products, add them to a cart, and proceed to checkout.

## Features

- **User Authentication**: Users can register, log in, and manage their accounts.
- **Product Catalog**: Browse and filter products by categories, price, etc.
- **Shopping Cart**: Add products to the shopping cart, modify quantities, or remove items.
- **Checkout Process**: Users can proceed to checkout and complete their purchases.
- **Order History**: Users can view their previous orders.
- **Admin Panel**: Admin users can manage products, view orders, and handle customer data.

## Technologies Used

- **MongoDB**: NoSQL database for storing product, order, and user information.
- **Express.js**: Web application framework for building the backend API.
- **React.js**: Frontend framework for building the user interface.
- **Node.js**: JavaScript runtime for the backend.
- **JWT (JSON Web Token)**: For handling secure user authentication.
- **Bcrypt.js**: For hashing passwords.
- **Stripe**: For payment processing (if applicable).

## Installation

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/deepak748030/full-stack-e-commerce.git
```

### 2. Navigate to the Project Directory

```bash
cd eccomerce-
```

### 3. Install Backend Dependencies

Go to the backend folder and install dependencies:

```bash
cd backend
npm install
```

### 4. Set Up Environment Variables

Create a `.env` file in the backend folder and add the following environment variables:

```env
MONGO_URI=your_mongo_db_connection_url
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key (if using Stripe)
```

### 5. Install Frontend Dependencies

Go to the frontend folder and install dependencies:

```bash
cd ../frontend
npm install
```

### 6. Run the Development Servers

#### Run the backend server:

```bash
cd ../backend
npm run dev
```

#### Run the frontend server:

```bash
cd ../frontend
npm start
```

The frontend will now be accessible at `http://localhost:3000`, and the backend at `http://localhost:5000`.

## Usage

- **User Registration & Login**: Users can create an account and log in to the platform.
- **Browse Products**: Users can view products, add them to their cart, and filter by categories.
- **Shopping Cart**: Add, remove, and modify quantities of products in the cart.
- **Checkout**: Complete the purchase process and view order history.

## Demo

Since the website is not hosted yet, please follow the above instructions to run it locally.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push the branch to your forked repository (`git push origin feature-name`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Key Details:
- **Demo Section**: As the website is not hosted, it includes instructions on running it locally.
- **Installation Instructions**: The README covers backend and frontend setup and environment variables.
- **Technologies Used**: List of all main technologies.
- **Contributing**: A basic guide for contributing to the project.
