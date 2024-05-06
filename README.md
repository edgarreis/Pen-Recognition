# Object Detection with Webcam

This program redirects standard output to a file while loading a pre-trained AI model, creates a JavaScript function to stream video from a webcam, and defines functions to convert JavaScript image data to an OpenCV image and to send a JavaScript command to the browser to handle video streaming.

## Files Required:
- `keras_model.h5`: AI model imported from [Teachable Machine](https://teachablemachine.withgoogle.com/train/image).
- `labels.txt`: Labels with classifications.

## Instructions:
1. Upload `keras_model.h5` and `labels.txt` to your Colab environment.
2. Run the program to start streaming video from your webcam.
3. The program will detect objects in the video stream and display the object name and confidence score.

## Dependencies:
- `keras`
- `IPython`
- `opencv-python`
- `numpy`

## Usage:
1. Clone the repository or download the files.
2. Upload `keras_model.h5` and `labels.txt` to the same directory as the notebook.
3. Open the notebook and run the cells.

Enjoy object detection with your webcam!
