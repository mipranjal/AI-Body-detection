# Body-Language-Decoder
This code is a Python script that demonstrates the use of the MediaPipe library to capture video from a webcam and perform pose detection, facial detection, and hand detection in real-time.
The project also allows capturing the detected landmarks and exporting them to a CSV file for further analysis.

## Installation
To run this code, you need to install the following dependencies:

mediapipe
opencv-python
pandas
scikit-learn
You can install these dependencies using pip:
code
!pip install mediapipe opencv-python pandas scikit-learn

## Usage
To use this code, simply run the Python script. The code will capture the webcam stream and start detecting the facial landmarks, hand gestures, and body poses in real-time. The detected landmarks will be displayed on the video stream as different colored dots connected by lines to form a skeleton.

To exit the code, press the "q" key.

The detected landmarks can also be captured and exported to a CSV file for further analysis. The exported CSV file will contain the x, y, and z coordinates of each detected landmark, as well as a visibility score.

## License
This code is licensed under the MIT 
