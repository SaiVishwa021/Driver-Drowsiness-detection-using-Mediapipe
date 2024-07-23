# **Driver Drowsiness Detection Using Mediapipe**

## **Introduction**

Driving for extended periods can be tiresome and lead to drowsiness, increasing the risk of nodding off. To tackle this issue, we'll develop a drowsy driver detection system using Python, leveraging Mediapipe's Face Mesh solution and the Eye Aspect Ratio formula. Our objective is to build a reliable application that can detect when a driver's eyes remain closed for an extended duration, providing timely alerts to prevent potential accidents.

## **Project Overview**

**Driver Drowsiness Detection and Alerting System using Mediapipe’s Face Mesh Solution API in Python**

This project leverages the power of MediaPipe to accurately identify signs of drowsiness in drivers in real-time. The core functionality of this system is built around the detection of sustained eye closure, rather than simple blinks. By doing so, we can effectively monitor the driver's state and provide timely alerts to ensure safety.

## **How Can We Detect Drowsiness?**

Detecting drowsiness involves determining if the eyes are closed for a sustained period, rather than just identifying "blinks." We don't need to perform any training for this. Instead, we'll rely on a straightforward observation: "Our eyes close when we feel drowsy." To develop a driver drowsiness detection system, we simply need to check if the eyes stay closed for an extended interval.

## **Features**

- **Real-Time Detection**: Leveraging Mediapipe’s Face Mesh solution, the system processes and analyzes facial expressions and eye movements in real-time.
- **Accurate Detection**: By using the Eye Aspect Ratio formula, the system can accurately detect drowsiness patterns.
- **Automated Alerts**: The system provides automated alerts to minimize the chances of human error caused by impaired attention or reaction times.

## **Implementation Details**

The heart of this project lies in the implementation of MediaPipe, a powerful open-source library. Through its robust features, we can efficiently process and analyze facial expressions and eye movements, allowing for accurate detection of drowsiness patterns.

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/SaiVishwa021/Driver-Drowsiness-detection-using-Mediapipe.git
   ```
2. Locate the correct directory
   ```bash
   cd Driver-Drowsiness-detection-using-Mediapipe-in-Python
   ```
3. Install the required dependencies
   ```bash
   pip install -r requirements.txt
   ```
5. Run the file using the code
   ```bash
   python drowsy_detection.py
   ```

## **Contribution**

Contributions are welcome! If you have any ideas, suggestions, or bug reports, feel free to open an issue or submit a pull request.

## **Acknowledgements**

**Mediapipe** for providing an excellent open-source framework for face and hand tracking.
The Python community for their invaluable resources and libraries.

