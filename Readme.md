# Hand Gesture Recognition using MediaPipe and TensorFlow

This project is a real-time hand gesture recognition system using the MediaPipe library for hand landmark detection and TensorFlow for gesture classification.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- MediaPipe (`mediapipe`)
- TensorFlow (`tensorflow`)

You can install the required Python packages using pip:

```bash
pip install opencv-python numpy mediapipe tensorflow
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/amarmurmu001/hand-gesture-recognition.git
```

2. Navigate to the project directory:

```bash
cd hand-gesture-recognition
```

3. Download the pre-trained model (`mp_hand_gesture`) and class names (`gesture.names`) into the project directory.

4. Run the Python script:

```bash
python hand_gesture_recognition.py
```

5. The script will open your webcam and display real-time hand gesture recognition results.

## About the Code

- `hand_gesture_recognition.py`: This script contains the main implementation of the hand gesture recognition system. It uses MediaPipe to detect hand landmarks and TensorFlow to classify gestures based on the detected landmarks.

- `mp_hand_gesture`: This file contains the pre-trained gesture recognition model.

- `gesture.names`: This file contains the class names corresponding to the gestures recognized by the model.

## Acknowledgments

- This project utilizes the MediaPipe library for hand landmark detection.

- The hand gesture recognition model is implemented using TensorFlow.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
