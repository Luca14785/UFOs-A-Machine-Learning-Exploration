# UFO Sighting Prediction and Comment Generation

This project is a machine learning-based UFO prediction system. Using a trained Recurrent Neural Network model, it predicts the coordinates, shape, and time of the next potential UFO sighting. It also generates a comment about the sighting using a trained text prediction model and enhances it with Google Gemini's API.

## Features:
  - Predict next UFO sighting coordinates, shape, and time
  - Map visualization of the predicted location
  - Location description generation
  - Comment generation

## Setup and Requirements:
  - Install dependencies with `pip install gradio google-generativeai pandas numpy tensorflow scikit-learn folium pillow`.
  - Ensure you have API keys for Google Gemini.
  - Required models: `UFO_PREDICTOR_UPDATED.h5`, `UFO_Comment_Generator_Optimal_1.h5`, `scaler_UPDATED.pkl`.

## Usage:
  - Run the Gradio App block found at the end of the notebook
  - Press the "Predict Next Sighting" button to get a prediction and related information of the next sighting.
      
