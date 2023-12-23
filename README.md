# React_Money

## Overview
Personal Finance App is a mobile application designed to help users manage their personal finances. It allows users to upload transaction data via CSV files, view their financial summaries, and track their spending over time.

## Tech Stack
- **Backend**: Python (Flask/Django/FastAPI)
- **Frontend**: React Native
- **Database**: PostgreSQL/MySQL/MongoDB (choose as per your requirement)
- **Testing**: `pytest` for backend, Jest for frontend

## Project Structure

### Backend

- **`/backend/`**: Contains all server-side code.
  - **`src/`**: Main source directory.
    - **`api/`**: Contains API route definitions. Each file defines routes for different features (e.g., user management, transaction processing).
    - **`config/`**: Configuration files for different environments (development, production).
    - **`controllers/`**: Business logic of the application. Handles the processing of data between the `models` and the `api`.
    - **`models/`**: Database models. Each file represents a table in the database and includes the schema and database interaction logic.
    - **`services/`**: Independent business logic services like file parsing and external API integrations.
    - **`utils/`**: Utility functions and helpers used across the application.
  - **`tests/`**: Unit and integration tests for the backend.
  - **`.env`**: Environment variables file (not to be committed).
  - **`requirements.txt`**: Python dependencies for the project.
  - **`app.py`**: Main application entry point.

### Frontend

- **`/frontend/`**: Contains all client-side code.
  - **`src/`**: Main source directory.
    - **`components/`**: Reusable UI components.
    - **`screens/`**: Different screens of the app, each representing a view.
    - **`services/`**: Handles the business logic of the frontend, including API calls.
    - **`utils/`**: Utility functions for the frontend.
  - **`assets/`**: Static assets like images and fonts.
  - **`App.js`**: Main React Native component.
  - **`package.json`**: Node.js dependencies for the frontend.

### Root Directory

- **`.gitignore`**: Specifies intentionally untracked files to ignore.
- **`README.md`**: Project overview and instructions.
- **`docker-compose.yml`**: Docker configuration for containerized environment setup (optional).

## Setup and Installation

For running locally, we support Anaconda environments and Docker. However, these are still in development and not released.\

## Contributing Authors

Karl Bates and Zane Bates

## License

CC0 1.0 Universal Liscense 
