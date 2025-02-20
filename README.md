# Steganograpghy

Overview
This project demonstrates the concept of data hiding in images using steganography, allowing users to securely encode a secret message into an image file. The encoded message can only be decrypted with the correct passcode. This project provides both encryption and decryption functionalities with a user-friendly GUI built using Tkinter.

By leveraging the OpenCV library for image manipulation and Pillow for image resizing, the application ensures that the images are both encrypted and displayed with ease.

Features
Image Encryption: Hide a secret message in an image using a passcode.
Image Decryption: Decrypt the message from the image by entering the correct passcode.
User-Friendly GUI: Easy-to-use interface to select an image, input a secret message, and display the encrypted and decrypted results.
Support for Multiple Image Formats: Works with .jpg, .jpeg, and .png image formats.
Passcode Protection: A passcode is required for both encryption and decryption, adding a layer of security.

Technologies Used
Python: Programming language used for the development.
Tkinter: GUI library for creating the application interface.
OpenCV: Library for reading and writing images and manipulating pixel data.
Pillow (PIL): Python Imaging Library used for resizing images to fit the GUI.
Steganography Algorithm: The core functionality to hide and reveal messages within the image pixels.
Installation
To get started with this project, follow these steps:

Prerequisites
Ensure you have Python installed on your system. You can download it from python.org.

You will also need to install the following Python libraries:

OpenCV: pip install opencv-python
Pillow: pip install pillow
Tkinter (included with Python, but may need to be installed separately on some systems)

Usage
Select Image: Click on "Select Image" to choose an image file from your local machine.
Enter Secret Message: Input the message you want to hide within the image.
Enter Passcode: Set a passcode that will be required to decrypt the image.
Encrypt Image: Click "Encrypt Image" to hide the message in the selected image.
Decrypt Image: To retrieve the hidden message, enter the passcode and click "Decrypt Image".

Future Scope
Enhance Security: Use more advanced encryption algorithms for better data security.
Multiple Message Encoding: Allow users to hide multiple messages within different images.
Support for Other File Formats: Extend the support for more image formats.
Cloud Integration: Enable cloud storage for images and encrypted messages.
