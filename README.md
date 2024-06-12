# Paytm 

This is a responsive web application based on the MERN stack (MongoDB, Express.js, React.js, Node.js) that mimics the core functionality of Paytm. The application includes the following pages:
- Dashboard
- Signup
- Signin
- Send Money

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization using JSON Web Tokens (JWT).
- Form validation using Zod library.
- Fully responsive design.
- Secure money transfer feature.

## Tech Stack

**Frontend:**
- React.js
- Tailwind CSS

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB
- Mongoose

**Libraries & Tools:**
- JSON Web Tokens (JWT)
- Zod
- Cors

**APIs:**
- Postman


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/paytm-project.git
    cd paytm-project
    ```

2. Install dependencies for both frontend and backend:
    ```sh
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `backend` directory and add the following:
      ```env
      MONGO_URI=your_mongo_database_uri
      JWT_SECRET=your_jwt_secret
      ```

## Usage

1. Start the backend server:
    ```sh
    cd backend
    npm start
    ```

2. Start the frontend development server:
    ```sh
    cd ../frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000`.

## API Endpoints

- **POST** `/api/auth/signup` - Register a new user
- **POST** `/api/auth/signin` - Login an existing user
- **GET** `/api/dashboard` - Fetch user dashboard data (Protected route)
- **POST** `/api/send-money` - Send money to another user (Protected route)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add Some Feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
