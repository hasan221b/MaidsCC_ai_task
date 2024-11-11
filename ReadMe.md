# Device Price Prediction and API Project

This project involves developing a machine learning model to predict device prices and creating REST API endpoints using FastAPI.

## Project Overview

The project consists of:

- **Machine Learning Model**: A model that classifies and predicts device prices based on various features.
- **API Development**: REST API endpoints created with FastAPI.

## API Endpoints

- **POST /api/devices/**: Retrieve a list of all devices.
- **GET /api/devices/{id}**: Retrieve details of a specific device by ID.
- **POST /api/devices**: Add a new device.
- **POST /api/predict/{deviceId}**: Predict the price of a device by ID.

## Development Notes

- The APIs are developed using FastAPI due to familiarity with Python. 
- SpringBoot was not used as I lack experience in Java and couldn't learn it within the project timeframe.

## UI Application

A Streamlit app is available to test the API endpoints. You can access it here: [Streamlit App](https://appapp-dvrq7dbfyhfzecerffkxkn.streamlit.app/)