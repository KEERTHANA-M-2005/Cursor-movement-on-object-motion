# **Geston - Virtual Mouse Using Object Motion**

**Geston** is a project that enables controlling a computer's cursor using hand gestures or object motion. This project leverages **Mediapipe** and **OpenCV** to track motion and translate it into cursor movement, providing an interactive way to navigate your computer without using a traditional mouse.

## **Features**
- **Cursor Control**: Move the cursor by moving your hand or an object in front of the camera.
- **Click Action**: Perform a left-click by making a fist.
- **Zoom**: Pinch-to-zoom gesture for zooming in or out.
- **Speed Control**: Adjust the speed of the cursor movement by changing the distance of the tracked object.
  
## **Technologies Used**
- **Mediapipe**: For hand tracking and gesture recognition.
- **OpenCV**: For image processing and webcam capture.
- **Python**: The primary programming language for the project.

## **Requirements**
Before you begin, ensure you have the following installed on your system:

- **Python 3.9**
- **Mediapipe**: For hand gesture detection.
- **OpenCV**: For computer vision operations.
  
You can install the required libraries using pip:

```bash
pip install mediapipe opencv-python
How It Works
Hand Tracking: Mediapipe is used to track the position of your hand in front of the camera. By analyzing the hand's keypoints, the position is mapped to the screen to move the cursor.

Cursor Movement: The relative position of the hand's wrist is mapped to the screen coordinates, allowing smooth cursor movement.

Clicking: A closed fist (based on the finger landmarks) triggers a click action.

Known Issues
Works best in a well-lit environment.

Performance might be slower on low-end systems due to heavy processing required for hand tracking.

Future Improvements
Implement right-click functionality.

Add support for more gestures like scroll and drag-and-drop.

Optimize performance for low-resource environments.

Contributing
Feel free to fork this project and make improvements! If you'd like to contribute or report any issues, please feel free to open an issue or pull request.

License
This project is open-source and available under the MIT License.

vbnet
Copy
Edit

You can now copy and paste this directly into your GitHub repository's `README.md` file! Let me know if
