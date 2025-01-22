# AutoPartsStore E-commerce Web App

Welcome to the AutoPartsStore e-commerce web app! This application allows customers to browse and purchase auto parts from an online store. The system includes user authentication, a shopping cart, and an admin dashboard to manage orders.

## Features

### Customer Features
- **User Authentication**: Secure login and registration for customers.
- **Browse Auto Parts**: View and search a variety of auto parts available for purchase.
- **Add to Cart**: Add items to the shopping cart and view the total price.
- **Checkout**: Complete purchases through a secure checkout process.
- **Order History**: View past orders and track their statuses.

### Admin Features
- **Order Management**: View and manage customer orders.
- **Inventory Management**: Add, update, or remove products in the inventory.
- **Customer Management**: Manage customer accounts and view their order history.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **Database**: JSON (for storing product and order data)
- **Web Server**: Nginx
- **Containerization**: Docker (for deployment)

## Installation

### Prerequisites
Before you begin, ensure you have the following installed:
- Node.js
- Docker (optional, for deployment)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/autopartsstore.git
    ```

2. Navigate to the project directory:
    ```bash
    cd autopartsstore
    ```

3. Install dependencies for the backend:
    ```bash
    npm install
    ```

4. Configure your JSON database:
    - The database is stored in JSON files. Ensure you have the `products.json` and `orders.json` files in the project directory.
    - No additional configuration is needed for the database as it is directly accessed via JSON.

5. Start the server:
    ```bash
    npm start
    ```

6. Open your browser and visit `http://localhost:5000` to access the app.

### Docker Setup (Optional)
To run the app in a Docker container, follow these steps:

1. Build the Docker image:
    ```bash
    docker build -t autopartsstore .
    ```

2. Run the container:
    ```bash
    docker run -p 5000:5000 autopartsstore
    ```

## Usage

1. **Customer**: 
    - Sign up or log in.
    - Browse the auto parts catalog.
    - Add parts to the cart and proceed to checkout.
    - View order history.

2. **Admin**: 
    - Log in with admin credentials.
    - Manage inventory (add, update, delete parts).
    - View and process customer orders.

## Contributing

We welcome contributions to this project! If you'd like to improve the AutoPartsStore app, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request with a description of the changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the open-source community for the libraries and tools used in this project.
# AutoPartsStore E-commerce Web App

Welcome to the AutoPartsStore e-commerce web app! This application allows customers to browse and purchase auto parts from an online store. The system includes user authentication, a shopping cart, and an admin dashboard to manage orders.

## Features

### Customer Features
- **User Authentication**: Secure login and registration for customers.
- **Browse Auto Parts**: View and search a variety of auto parts available for purchase.
- **Add to Cart**: Add items to the shopping cart and view the total price.
- **Checkout**: Complete purchases through a secure checkout process.
- **Order History**: View past orders and track their statuses.

### Admin Features
- **Order Management**: View and manage customer orders.
- **Inventory Management**: Add, update, or remove products in the inventory.
- **Customer Management**: Manage customer accounts and view their order history.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **Database**: JSON (for storing product and order data)
- **Web Server**: Nginx
- **Containerization**: Docker (for deployment)

## Installation

### Prerequisites
Before you begin, ensure you have the following installed:
- Node.js
- Docker (optional, for deployment)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/autopartsstore.git
    ```

2. Navigate to the project directory:
    ```bash
    cd autopartsstore
    ```

3. Install dependencies for the backend:
    ```bash
    npm install
    ```

4. Configure your JSON database:
    - The database is stored in JSON files. Ensure you have the `products.json` and `orders.json` files in the project directory.
    - No additional configuration is needed for the database as it is directly accessed via JSON.

5. Start the server:
    ```bash
    npm start
    ```

6. Open your browser and visit `http://localhost:5000` to access the app.

### Docker Setup (Optional)
To run the app in a Docker container, follow these steps:

1. Build the Docker image:
    ```bash
    docker build -t autopartsstore .
    ```

2. Run the container:
    ```bash
    docker run -p 5000:5000 autopartsstore
    ```

## Usage

1. **Customer**: 
    - Sign up or log in.
    - Browse the auto parts catalog.
    - Add parts to the cart and proceed to checkout.
    - View order history.

2. **Admin**: 
    - Log in with admin credentials.
    - Manage inventory (add, update, delete parts).
    - View and process customer orders.

## Contributing

We welcome contributions to this project! If you'd like to improve the AutoPartsStore app, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request with a description of the changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the open-source community for the libraries and tools used in this project.

