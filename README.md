# 🖐️ Finger Counter using OpenCV and HandDetector 🤚

This Python program utilizes OpenCV and HandDetector to count the number of fingers displayed in front of a webcam.

## Features:
- Detects and tracks the user's hand in real-time.
- Counts the number of fingers displayed by the user.
- Provides visual feedback by overlaying images based on the number of fingers.
- Simple and intuitive user interface.

## Technologies Used:
- **OpenCV**: Library for computer vision and image processing tasks.
- **HandDetector**: Custom module for hand tracking and finger counting.
- **Python**: Programming language used for development.

## How it Works:
1. **Hand Detection**: The program uses OpenCV to detect and track the user's hand in real-time using a webcam.
2. **Finger Counting**: Once the hand is detected, the program counts the number of fingers displayed by the user using the HandDetector module.
3. **Visual Feedback**: Based on the number of fingers counted, the program overlays corresponding images to provide visual feedback.
4. **User Interaction**: Users can interact with the program by displaying different finger configurations in front of the webcam.

## Usage:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Python script `finger_counter.py`.
4. Display your hand in front of the webcam and observe the finger counting in real-time.

## Dependencies:
- Python 3.x
- OpenCV
- HandDetector module

## Future Enhancements:
- Improve accuracy and robustness of finger counting algorithm.
- Add support for multiple hand tracking.
- Implement gesture recognition for advanced interactions.

Feel free to contribute to the project or suggest improvements! 🚀
