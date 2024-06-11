# Weather Forecasting Web Application

This repository contains a Weather Forecasting web application built using React.js for the frontend, Node.js for the backend, and MySQL for the database. The application provides weather forecasts for various locations using data fetched from a weather API.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Weather Forecasting web application allows users to get real-time weather updates and forecasts for different locations. It uses a weather API to fetch data and provides a user-friendly interface to display the information.

## Features

- **Real-time Weather Updates**: Fetches current weather data from a weather API.
- **Forecast Information**: Provides weather forecasts for the next few days.
- **Search Functionality**: Allows users to search for weather information by location.
- **Responsive Design**: Ensures a seamless experience on both desktop and mobile devices.

## Technologies Used

- **Frontend**: React.js, HTML, CSS, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Build Tool**: Vite
- **API**: Weather API (e.g., OpenWeatherMap)
- **Data Format**: JSON

## Prerequisites

- Node.js and npm installed
- MySQL installed and running
- API key for the weather API (e.g., OpenWeatherMap)

## Installation

### Backend Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/weather-forecasting-app.git
    cd weather-forecasting-app/backend
    ```

2. Install backend dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the backend directory and add your MySQL connection string and other environment variables:

    ```env
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=password
    DB_NAME=weather_db
    WEATHER_API_KEY=your_weather_api_key
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

### Frontend Setup

1. Navigate to the `frontend` directory:

    ```bash
    cd ../frontend
    ```

2. Install frontend dependencies:

    ```bash
    npm install
    ```

3. Start the frontend development server:

    ```bash
    npm run dev
    ```

## Usage

1. Open the frontend in your web browser at `http://localhost:3000`.
2. Use the search bar to enter a location and get the weather forecast.
3. View real-time weather updates and forecasts for the next few days.

## Project Structure

```plaintext
├── backend/
│   ├── controllers/        # Controllers for handling requests
│   ├── models/             # Database models
│   ├── routes/             # Express routes
│   ├── middleware/         # Custom middleware
│   ├── utils/              # Utility functions
│   ├── .env                # Environment variables
│   ├── server.js           # Main server file
├── frontend/
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/          # React pages
│   │   ├── services/       # Services for API calls
│   │   ├── App.jsx         # Main App component
│   │   ├── main.jsx        # Entry point
│   ├── public/             # Public assets
│   ├── tailwind.config.js  # Tailwind CSS configuration
│   ├── vite.config.js      # Vite configuration
│   ├── package.json        # Frontend dependencies
├── README.md               # Project documentation
