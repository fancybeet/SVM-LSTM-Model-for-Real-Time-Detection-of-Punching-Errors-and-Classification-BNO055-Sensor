Project Title
# SVM-LSTM-Model-for-Real-Time-Detection-of-Punching-Errors-and-Classification-BNO055-Sensor

Overview
Real-time boxer form analysis system using Kinect v2 and glove-mounted BNO055 sensors. Combines SVM and LSTM models for punch classification and error detection, with accuracy up to 0.93. Published in IICAIET 2025.

Key Features
Real-time motion classification using LSTM
Form error detection using SVM models
Sensor and camera data synchronization
Pose estimation using MediaPipe
Multi-threaded real-time processing pipeline
UDP communication with ESP32 devices
Desktop GUI for live monitoring and feedback
System Architecture

ESP32 Sensor → UDP Streaming → Python Real-Time Pipeline → ML Inference → GUI Visualization

Technologies

Python, TensorFlow, Scikit-learn, OpenCV, MediaPipe, PyQt5, NumPy, Pandas, ESP32, BNO-055 IMU sensor
