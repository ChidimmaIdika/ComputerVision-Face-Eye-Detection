# ComputerVision-Face-Eye-Detection

![image](https://github.com/ChidimmaIdika/ComputerVision-Face-Eye-Detection/assets/137975543/836b9986-7bc8-42f5-bf09-544c6fb3bc26)

# Face and Eye Detection using OpenCV

## Table of Contents
1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [How to Use](#how-to-use)
4. [Implementation Details](#implementation-details)
5. [Sample Output](#sample-output)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Author](#author)
9. [Contact](#contact)


## Overview
This project demonstrates real-time face and eye detection using Python and the OpenCV library. I leveraged Haar-cascade classifiers to detect faces and eyes in a webcam feed and draw rectangles around them.

## Prerequisites
Before running the code, ensure you have the following dependencies installed:

- Python (>=3.6)
- OpenCV (4.8.1.78 or higher)
- NumPy (>=1.21.2)

You can install OpenCV and NumPy using pip:   
!pip install opencv-python   
!pip install numpy

## How to Use
1. Clone this repository:   
git clone https://github.com/ChidimmaIdika/ComputerVision-Face-Eye-Detection.git
cd face-eye-detection
3. Run the face_eye_detection.py script:   
   python face_eye_detection.py
4. Press the 'q' key to exit the webcam feed.

## Implementation Details
The key components of this project are as follows:

I used Haar-cascade classifiers provided by OpenCV to detect frontal faces and eyes.
The detect function takes the grayscale image and the original frame and returns the frame with rectangles drawn around detected faces and eyes.

## Sample Output
![chi](https://github.com/ChidimmaIdika/ComputerVision-Face-Eye-Detection/assets/137975543/feed5181-2403-4d66-8a85-8eb2471c23ad)

## License
This project is licensed under the MIT License.

## Acknowledgments
- [OpenCV](https://github.com/opencv/opencv/tree/4.x/data/haarcascades) for providing the Haar-cascade classifiers.
- [10Alytics](https://github.com/10Alytics)

## Author
[Chidimma Idika](https://github.com/ChidimmaIdika)

## Contact
For any inquiries or suggestions, please [send me an email](chidimmaidika@gmail.com).
