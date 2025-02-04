# Steganography-
Steganography - Hide a Secret Text in Image

Overview

Steganography is a simple steganography tool built using Python and Tkinter that allows users to hide a secret text message inside an image. The tool uses the Least Significant Bit (LSB) steganography method for encoding and decoding messages within images.

Features

Load and display an image.

Hide a secret text message inside the selected image.

Retrieve the hidden text from an encoded image.

Save the image with the hidden message.

Simple and user-friendly GUI.

Technologies Used

Python

Tkinter (GUI framework)

Pillow (PIL) for image processing

Stegano (for LSB steganography)

Installation

Ensure you have Python installed on your system (Python 3.x recommended).

Install the required dependencies using pip:

pip install pillow stegano

Download or clone the project repository.

Run the script using:

python steganography.py

Usage

Open Image: Click the "Open Image" button to select an image file.

Hide Data: Enter the secret message in the text box and click "Hide Data" to encode it in the image.

Save Image: Save the image with the hidden data by clicking "Save Image".

Show Data: Retrieve and display the hidden message by clicking "Show Data".

File Structure

|-- steganography.py (Main Script)
|-- logo.jpg (Application Icon)
|-- logo.png (Application Logo)
|-- hidden.png (Output Image with Hidden Data)

Dependencies

Python 3.x

Tkinter (Built-in with Python)

Pillow (PIL Fork)

Stegano


Author

Phanindra Singarapu
