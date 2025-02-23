Steganography Script
This Python script hides a secret message inside an image and retrieves it using a password.

Requirements
Ensure you have the following installed:

Python 3.x
OpenCV (cv2)
Install OpenCV if not already installed:
pip install opencv-python

How It Works
Encryption:
The script takes an image (mypic.jpg) and a secret message from the user.
It encodes the message into the image pixel values.
The modified image is saved as encryptedImage.jpg.

Decryption:
The user provides the passcode.
If the passcode is correct, the script extracts and displays the hidden message.
Usage
Running the Script
python stego.py

Input Prompts
Enter the secret message.
Set a passcode for decryption.
To decode, enter the correct passcode.
Notes
Ensure mypic.jpg exists in the script directory.
