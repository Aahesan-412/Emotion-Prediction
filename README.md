
Emotion Prediction Application

A deep learning-based FastAPI application for Sentiment Analysis and Emotion Prediction. This application processes text inputs to analyze and predict human emotional states using a trained neural network model.

Features

• FastAPI Backend: Fast, asynchronous REST API infrastructure for real-time text processing.
• Deep Learning Inference: Integrates TensorFlow/Keras models to parse sentiments and predict emotions.
• Interactive UI: Serves static frontend assets to provide a clean web interface for direct user interaction.

Dependencies

The project relies on the following core frameworks:
• FastAPI & Uvicorn - For serving the web application and handling API routing.
• TensorFlow (CPU edition) - For loading the deep learning network and executing classification inference.
• Pydantic - For structured data validation on incoming text payloads.
• NumPy & H5py - For handling tensor operations and loading structural model weights.
