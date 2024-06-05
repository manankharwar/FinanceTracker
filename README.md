# FinanceTracker

FinanceTracker is a robust and scalable application designed to help users manage their financial transactions seamlessly. It features a scalable backend system built with FastAPI and SQLAlchemy, and a responsive frontend interface developed using React and Axios for efficient communication with the backend API.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features
- Scalable backend system using FastAPI
- Database operations with SQLAlchemy
- CORS middleware for enhanced security
- Responsive frontend interface using React
- Efficient backend communication with Axios
- User-friendly management of financial transactions

## Tech Stack
### Backend
- **FastAPI**: Web framework for building APIs with Python 3.7+ based on standard Python type hints.
- **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **Uvicorn**: ASGI server for serving FastAPI applications.
- **CORS Middleware**: Ensures secure cross-origin requests.

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Axios**: Promise-based HTTP client for the browser and Node.js.
- **Bootstrap**: CSS framework for responsive design.

## Installation
### Prerequisites
- Python 3.7+
- Node.js
- npm (Node Package Manager)

### Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/FinanceTracker.git
    cd FinanceTracker/backend
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the FastAPI application:
    ```bash
    uvicorn main:app --reload
    ```

### Frontend Setup
1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install the required packages:
    ```bash
    npm install
    ```

3. Start the React application:
    ```bash
    npm start
    ```

## Usage
1. Start the backend server by following the backend setup instructions.
2. Start the frontend server by following the frontend setup instructions.
3. Open your browser and navigate to `http://localhost:3000` to use the application.

## API Documentation
Once the backend server is running, you can access the automatically generated API documentation by navigating to:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
