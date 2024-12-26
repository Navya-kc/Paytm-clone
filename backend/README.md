# Paytm Clone Backend

This is the backend for the Paytm clone application built using the MERN stack.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the backend directory:
   ```
   cd paytm-clone/backend
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Set up your environment variables (e.g., MongoDB connection string).

## Usage

To start the backend server, run:
```
npm start
```

The server will run on `http://localhost:5000` by default.

## API Endpoints

- `POST /api/auth/login`: User login
- `POST /api/auth/register`: User registration
- `GET /api/transactions`: Get user transactions
- `POST /api/transactions`: Create a new transaction

## License

This project is licensed under the MIT License.