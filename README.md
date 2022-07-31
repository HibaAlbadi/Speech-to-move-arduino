# Speech-to-move-arduino
The Web Serial API provides a way for websites to read from and write to serial devices. These devices may be connected via a serial port, or be USB or Bluetooth devices that emulate a serial port.

The Web Serial API is one of a set of APIs that allow websites to communicate with peripherals connected to a user's computer. It provides the ability to connect to devices that are required by the operating system to communicate via the serial API, rather than USB which can be accessed via the WebUSB API, or input devices that can be accessed via WebHID API.

And it was applied in our project for converting audio to writing
Let's convert the sound into movement where the robot arm dynamically reacts to the words using a servo motor programmed by the Arduino

# Arduino code
We used a servo motor and sent the value in which the recorded sound was stored and matched with it (right - left) and accordingly the arm moves.
