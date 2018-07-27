							SMART PEN

This folder contains the following files:

1. The video smart_pen.mp4 which demonstrates the working of the pen.

2. The folder Master which contains the arduino file Master.ino. This file contains the code that has been uploaded to arduino mega, which senses the button clicks, and send the information to the HID Arduino through the bluetooth communication, thus making the pen Wireless

3. The folder Slave which contains the arduino file Slave.ino. This file contains the code that has been uploaded to Leonardo board, which is an HID board. This board processes the information recieved through bluetooth and manage the mouse settings appropriately.

4. The file Cursor_movement_detection.py which detects the pink color on the pen and places the cursor appropriately.
