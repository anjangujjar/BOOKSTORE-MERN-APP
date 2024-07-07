# BOOKSTORE-MERN-APP

BOOKSTORE-MERN-APP is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). This application allows users to browse, search, and purchase books. It also includes features for managing user accounts and handling orders.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)


## Features

- User authentication and authorization (sign up, login, logout)
- Browse books by category or search by title/author
- View detailed information about each book
- Add books to a shopping cart
- Place orders and view order history
- Admin panel to manage books and orders

## Installation

### Prerequisites

- Node.js
- MongoDB

### Steps

1. Clone the repository

```
git clone https://github.com/anjangujjar/BOOKSTORE-MERN-APP.git
cd BOOKSTORE-MERN-APP
```

2. Install server dependencies

```
cd backend
npm install
```

3. Install client dependencies

```
cd ../frontend
npm install
```

4. Make modifications in the `config.js` file in the `backend` directory and add the following environment variables:

```
mongoDBURL=your_mongodb_uri
```

5. Start the development server

```
cd ../backend
npm run dev
```

6. Start the client

```
Open New Terminal
cd client
npm start
```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to view the application.
2. Register a new account or log in with existing credentials.
3. Browse books, add them to your cart, and place orders.
4. If you have admin privileges, you can access the admin panel to manage books and orders.

## Technologies Used

- **MongoDB**: Database
- **Express.js**: Backend framework
- **React**: Frontend library
- **Node.js**: Backend runtime
- **Mongoose**: ODM for MongoDB
- **JWT**: JSON Web Tokens for authentication
- **Redux**: State management for React

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, feel free to contact:

- Your Name: [anjangujjar1310@gmail.com](mailto:anjangujjar1310@gmail.com)
- GitHub: [anjangujjar](https://github.com/anjangujjar)
