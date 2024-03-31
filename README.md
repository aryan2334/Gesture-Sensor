Gesture Sensor Video Player

This project utilizes an Arduino board and a PAJ7462 gesture sensor to capture user gestures, which are then interpreted by a Python script to control media playback on a computer.


Requirements

Arduino board

PAJ7462 gesture sensor

Python (version 3.x)

PyAutoGUI library (install via pip: pip install pyautogui)

Arduino IDE (for uploading code to Arduino board)


Installation and Setup
Connect the PAJ7462 gesture sensor to the Arduino board.

Upload the provided Arduino code (gesture_sensor.ino) to the Arduino board using the Arduino IDE.

Ensure the Python script (gesture_sensor_controller.py) and the Arduino code are in the same directory.

Install the PyAutoGUI library by running pip install pyautogui in your terminal or command prompt.


Usage

Run the Python script gesture_sensor_controller.py.

The script will automatically detect the connected Arduino board and establish communication.

Perform gestures in front of the gesture sensor to control media playback on the computer.

Supported gestures and their corresponding actions:

Left: Previous track

Right: Next track

Clockwise: Increase volume

Anti-clockwise: Decrease volume

Up: Play/pause

Down: Mute/unmute

Forward: Start gesture recognition

Backward: Stop gesture recognition and exit the program


Troubleshooting

If the Arduino board is not detected, ensure it is properly connected to the computer and the correct device name is specified in the Python script.
Make sure the correct COM port is selected in the Python script.
Ensure the PyAutoGUI library is installed correctly.
