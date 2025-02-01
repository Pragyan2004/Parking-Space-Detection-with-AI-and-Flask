# Parking Space Detection with AI and Flask

This project implements a parking space detection system using a Convolutional Neural Network (CNN) built with Keras and TensorFlow. The system detects free and occupied parking spaces in a given parking lot from a video feed. The app uses computer vision techniques with OpenCV to predict car presence in each parking slot.

# Features:
AI Model: Uses a pre-trained VGG16 model (fine-tuned for parking space detection) for classifying images into two categories: car and no_car.
Real-Time Detection: The model analyzes frames from a video feed, detecting free and occupied parking spaces in real-time.
Flask Web Application: The app serves the video feed and updates the parking space count dynamically on a webpage.
Car Position Marking: Users can mark positions of parking spaces manually in the image by clicking on them, which is saved for further processing.
Front-End Interface: Built using HTML, CSS, and Bootstrap, displaying the live video feed and the current count of free and occupied parking spaces.

# Technologies Used:
Backend: Flask, Keras (TensorFlow)
Frontend: HTML, CSS, Bootstrap, jQuery
Computer Vision: OpenCV
Model: VGG16 for image classification

# How to Use:
Clone the repository and install the required dependencies.
Train the model with your own dataset or use the pre-trained model (model_final.h5).
Run the Flask application to visualize the video feed with real-time parking space status.

# Instructions:
The system uses a car_test.mp4 video for parking space detection.
The parking spaces are defined by manually selecting positions, which are saved in carposition.pkl.

# Run :
        python main.py

# Screenshoot:

![Screenshot (516)](https://github.com/user-attachments/assets/544c118d-7ba4-4b45-aa9c-5a612c10d225)
