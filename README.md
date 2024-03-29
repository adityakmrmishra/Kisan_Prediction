﻿# Kisan Prediction

This project is an application for predicting crop types based on input environmental factors. The backend is implemented in Flask (Python), and the frontend is built using React.

## Introduction

The Crop Prediction App uses a machine learning model to predict the most suitable crop based on environmental factors such as nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall.

## Features

- Predict crop type based on environmental factors.
- User-friendly frontend for input and result display.

## Getting Started

### Prerequisites

- Node.js
- Express.js
- Python
- Flask
- Vite + React + Tailwind CSS

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/crop-prediction-app.git

 ```

2. Install backend dependencies:

```bash
cd crop-prediction-backend
npm i 
```
```bash
pip install -r requirements.txt
```

3. Install frontend dependencies:

```bash
cd crop-prediction-frontend
npm install
```

### Project Structure

**crop-prediction-backend**: Backend implementation using Node, express and Flask .

**crop-prediction-frontend**: Frontend implementation using Vite + React + Tailwind CSS .

### Backend

The backend uses a RandomForestClassifier machine learning model trained on crop data.

#### Run Backend Locally

```bash
cd crop-prediction-backend
npm run dev
```
```bash
cd crop-prediction-backend
python model_api.py
```

### Frontend

The frontend is a React application providing a user interface for entering input values and displaying predictions.

#### Run Frontend Locally

```bash
cd crop-prediction-frontend
npm run dev
```

### API Endpoints

/api/predict : Endpoint for predicting the crop type based on input environmental factors.

### Usage

1. Start the backend server.
2. Start the frontend application.
3. Visit http://localhost:5173 in your web browser.
4. Enter the required input values.
5. Click the "Predict" button to get the crop prediction.

### Contributing

Contributions are welcome! Please fork the repository and create a pull request.
