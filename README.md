# Virtual Mouse Interface Using Hand Gestures



## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is a **Virtual Mouse Interface** that allows users to control their computer's mouse using hand gestures. Utilizing computer vision and machine learning libraries, this tool tracks hand movements in real-time through a webcam, translating specific gestures into cursor movements and actions (e.g., left-click, right-click, and drag).

## Features
- **Real-Time Hand Tracking**: Uses the webcam to capture hand gestures in real-time.
- **Cursor Control**: Move the cursor by moving your hand.
- **Click Actions**: Perform left-click, right-click, and drag actions using specific gestures.
- **Smooth Interaction**: Optimized for low latency and high accuracy in gesture recognition.

## Technologies Used
- **Python**
- **OpenCV**: For capturing and processing webcam video feed.
- **Mediapipe**: For robust hand-tracking and gesture recognition.
- **PyAutoGUI**: For simulating mouse movements and clicks.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Deepu1004/Virtual_Mouse_Interface_Using_Hand_Gestures.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Virtual_Mouse_Interface_Using_Hand_Gestures
    ```


## Usage
1. **Run the Script**: Start the virtual mouse interface by running:
    ```bash
    python virtual_mouse.py
    ```
2. **Perform Gestures**:
    - **Move Cursor**: Move your hand within the frame to control the cursor position.
    - **Left Click**: Use index and thumb finger to perform a left click
    - **Right Click**: Use index and middle finger to perform a left click
    - **Volume Up**: Point out 3 fingers to increase the volume
    - **Drag and Drop**: Point out 4 fingers to decrease the volume


## Future Enhancements
- **Enhanced Gesture Library**: Add more gestures for additional actions.
- **Voice Integration**: Combine voice commands for additional control options.
- **Customizable Gestures**: Allow users to set up custom gestures for different actions.


