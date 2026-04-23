# Smart Home Dashboard with AI Temperature Prediction

## Overview

Smart Home Dashboard is an intelligent web-based monitoring system designed to simulate a modern smart home environment. The project combines IoT concepts, web development, and Artificial Intelligence to provide a complete monitoring and prediction platform.

Users can monitor room temperature data, update sensor values, remove outdated entries, view activity history with timestamps, and predict tomorrow’s temperature using a Long Short-Term Memory (LSTM) deep learning model.

The system also generates an alert when the predicted temperature crosses the safety threshold of 45°C.



## Key Features

Real-time room temperature monitoring

Add new room sensor data

Update existing sensor values

Delete unwanted sensor records

View complete history with date and time

Tomorrow temperature prediction using LSTM

Automatic alert for high temperature

Responsive and attractive dashboard interface

REST API integration using GET, POST, DELETE methods

Modular project structure for easy maintenance



## Technologies Used

Python

Flask

HTML5

CSS3

JavaScript

JSON

TensorFlow / Keras

NumPy

Scikit-learn

GitHub

Git Bash



## Project Architecture

Frontend  
HTML, CSS, JavaScript dashboard for user interaction

Backend  
Python Flask server for APIs and data handling

Database  
JSON files used for storing sensor data and history

AI Module  
LSTM neural network model for future temperature prediction


## Project Structure

smart-home-dashboard/

app.py

prediction.py

sensors.json

history.json

temp_history.json

templates/

index.html

static/

style.css

script.js



## Installation and Setup

### Step 1 Clone Repository

```bash
git clone <your-github-link>
cd smart-home-dashboard
Minor update for PR demonstration
## UI Update
Improved dashboard layout and user interface
