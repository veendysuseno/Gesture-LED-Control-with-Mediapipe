# Gesture-LED-Control

This project uses a hand gesture recognition system with a webcam to control an LED connected to an Arduino.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- pyFirmata
- Arduino IDE

## Steps to Set Up

1. **Upload Firmata Code to Arduino**  
   First, upload the Standard Firmata code to your Arduino board.

   - Open the Arduino IDE
   - Go to `File` -> `Examples` -> `Firmata` -> `StandardFirmata`
   - Select the correct port and upload the code to your Arduino

2. **Install Python Libraries**  
   Run the following command to install required libraries:

   ```bash
   pip install opencv-python mediapipe pyfirmata
   ```

3. Connect Arduino
   Ensure your Arduino is connected to the correct COM port (e.g., COM7), and modify the script to match your setup.

4. Run the Gesture Detection Script
   Run the Python script to start controlling the LED using hand gestures.

## How It Works

- The script detects hand gestures using OpenCV and MediaPipe.
- Depending on the number of fingers detected, the LED connected to the Arduino will turn ON or OFF.

## Usage

- 0 fingers: LED OFF
- 1 finger: LED ON

## Author

Developed by Veendy
