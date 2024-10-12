# DeepFake Face Morphing Video Detection Using ResNext & LSTM

## Overview
This project focuses on detecting DeepFake videos, particularly those involving face morphing, using deep learning techniques. The model leverages **ResNext** for feature extraction and **LSTM** for sequential analysis, allowing it to detect temporal inconsistencies in video frames. The project includes a web interface for users to upload videos and get real-time detection results.

## Project Components

### 1. **Deep Learning Model**
- **ResNext**: Extracts features from individual video frames.
- **LSTM**: Captures temporal patterns and inconsistencies between video frames.

### 2. **Frontend (HTML/CSS/JavaScript)**
- A simple and intuitive interface for users to upload videos and get detection results.

### 3. **Backend (Python Flask Server)**
- Manages video uploads, processes frames using the model, and returns results.

## Technologies Used
- **Python**: Core language for deep learning and backend.
- **TensorFlow/Keras**: For building and training the ResNext and LSTM model.
- **Flask**: For handling requests and serving the model.
- **HTML/CSS/JavaScript**: Used to build the user interface.
- **OpenCV**: For extracting frames from videos.

## Key Highlights
- **ResNext for Feature Extraction**: High-quality spatial feature extraction from each video frame.
- **LSTM for Temporal Analysis**: Captures relationships between frames to detect subtle inconsistencies.
- **User-Friendly Web Interface**: Real-time feedback on video uploads, displaying clear results.
- **Efficient Backend**: The Flask server efficiently handles requests and returns accurate predictions.

## Results
- The model performs well in detecting DeepFake videos, providing accurate predictions in most test cases.
- Users can easily interact with the system, receiving quick, reliable detection results for uploaded videos.
