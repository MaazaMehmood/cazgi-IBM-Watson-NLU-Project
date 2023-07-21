# IBM_Watson_NLU(natural language understanding) Project


## Overview

    The IBM Watson NLU Sentiment Analysis project is a web application built with React on the frontend and an Express server on the backend. It leverages IBM Watson Natural Language Understanding (NLU) service to analyze the sentiment or emotions from text or URLs provided by users. The project aims to help users understand the emotions associated with the given content, enabling sentiment analysis for various purposes like social media monitoring, customer feedback analysis, and more.

## Demo
    <!-- See the live demo of the IBM Watson NLU Sentiment Analysis web application "here". -->

## Features
    Text Sentiment Analysis: Users can enter a text or paragraph, and the application will analyze its sentiment or emotions.
    URL Sentiment Analysis: Users can input a URL, and the application will fetch the content and perform sentiment analysis on it.
    Customizable Thresholds: Users can set custom sentiment thresholds to categorize content into positive, negative, or neutral sentiment.

## Technologies Used
    Frontend:
        React
        React Router
        Axios (for API requests)
        Bootstrap (or any other preferred CSS framework)
        CSS
    Backend:
        Node.js
        Express.js
        IBM Watson NLU API keys(Node.js SDK or REST API)

## Installation
To run the project locally, follow these steps:

    Clone the repository: git clone https://github.com/MaazaMehmood/cazgi-IBM-Watson-NLU-Project.git
    Install frontend dependencies: cd frontend && npm install
    Install backend dependencies: cd backend && npm install
    Set up IBM Watson NLU credentials (instructions in backend/README.md).
    Start the frontend and backend servers: npm start in both frontend and backend directories.

## Usage
    Access the web application in your browser at http://localhost:3000.
    Enter the text or URL you want to analyze.
    Submit the input, and the application will call the backend server to perform sentiment analysis using IBM Watson NLU.
    View the sentiment analysis results on the web page.

## API Endpoints
    The backend server exposes the following API endpoints:
    
    GET /api/analyze: Receives the text or URL input, calls IBM Watson NLU API, and returns the sentiment analysis results in JSON format.

