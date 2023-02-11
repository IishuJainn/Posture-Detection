# Posenet Demo
This project is a demo of using the Posenet machine learning model in JavaScript using the p5.js and ml5.js libraries.

## Features
The model uses the Posenet model to detect human pose in real-time from a webcam.
The model uses the keypoints detected by the Posenet to draw skeleton lines on the human pose.
The model overlays images of spectacles and smoke on the nose keypoint.

## Requirements
A modern web browser with webcam access.
A good internet connection to load the ml5 and Posenet models.
Usage
To run the demo, simply open the index.html file in a web browser.

## Code Explanation
The setup() function loads the Posenet model, captures video from the webcam using the createCapture() function and hides it. The images of spectacles and smoke are also loaded in the setup function.

The receivedPoses() function receives an array of poses detected by Posenet and saves the first pose (poses[0]) as singlePose and the skeleton of the pose as skeleton.

The modelLoaded() function logs a message to the console indicating that the Posenet model has loaded successfully.

The draw() function displays the video capture and then draws the keypoints as circles and the skeleton as lines. It also overlays the images of spectacles and smoke on the nose keypoint.

The code also logs the poses detected by Posenet to the console for debugging purposes.

# Posture-Detection-Demo

![Face png](https://user-images.githubusercontent.com/102272183/213777258-8b2490b4-6018-4407-b38f-c2dc04f34f38.png)
![Screenshot (73)](https://user-images.githubusercontent.com/102272183/213777378-f96567be-2002-43a9-a27b-cc8761e1666c.png)

