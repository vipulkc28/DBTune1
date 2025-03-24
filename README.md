# Image Upload and List Application

This is a full-stack application where users can upload images from the frontend, and the images are stored and listed on the backend. The backend is implemented using Flask, and the frontend is implemented using React.

## Features

- **Upload Image**: Users can upload images to the server.
- **List Images**: Displays a list of all uploaded images.
- **Image Resizing**: The uploaded images are resized before being saved on the server.

## Tech Stack

### Frontend:
- **React**: JavaScript library for building user interfaces.
- **Axios**: For making HTTP requests to the backend.

### Backend:
- **Flask**: A lightweight WSGI web application framework.
- **PIL (Pillow)**: For image resizing.
- **Flask-CORS**: To handle cross-origin resource sharing (CORS) and allow requests from the frontend.

## Installation

### Backend Setup

1. Clone the repository :- git clone <repository_url>
    cd DBtune
2. Install Python 3.x from the official Python website: https://www.python.org/downloads/
3. Install the required dependencies: Go to inside DBTune/backend/ 
    pip install flask-cors   
    pip install Flask Pillow
4. Run the backend server:  Go to inside DBTune/backend/ 
    python app.py

## The backend will be available at `http://localhost:5000`.

### Frontend Setup

1. cd DBtune/Frontend
2. Install the required dependencies:
    npm install
3. Start the React development server:
    npm Start

## The frontend will be available at `http://localhost:3000`

