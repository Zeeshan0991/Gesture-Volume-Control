
# Gesture Volume Control

Gesture Volume Control is a Python project that allows you to control your computer's volume using hand gestures detected by a webcam. This project utilizes OpenCV and MediaPipe for hand tracking and PyCaw for controlling the audio volume.

## Features

- Real-time hand detection and tracking
- Volume control using finger distance
- Visual feedback of hand landmarks and volume level

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyCaw

## Setup and Installation

### Prerequisites

Make sure you have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/gesture-volume-control.git
    ```
2. Navigate to the project directory:
    ```bash
    cd gesture-volume-control
    ```
3. Install the required dependencies:
    ```bash
    pip install opencv-python mediapipe pycaw
    ```

## Usage

1. Run the `VolumeHandControl.py` script:
    ```bash
    python VolumeHandControl.py
    ```

2. A window will open showing the webcam feed with hand landmarks. Use your thumb and index finger to control the volume by varying the distance between them.

### Script Descriptions

- `HandTrackingMin.py`: Basic hand tracking script using MediaPipe and OpenCV.
- `HandTrackingModule.py`: A module for hand detection with helper functions to find hand landmarks and positions.
- `VolumeHandControl.py`: Main script to control volume using hand gestures.

## Examples

Here's how the interface looks when the script is running:

![Demo](path-to-your-demo-image.gif)

## Contribution

Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
