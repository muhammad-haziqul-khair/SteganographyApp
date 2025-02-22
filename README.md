# SteganographyApp

SteganographyApp is a Python application built using Tkinter and PIL (Python Imaging Library) for encoding and decoding messages into images using the LSB (Least Significant Bit) technique.

## Features

- **Encode Message:** Embed a textual message into an image file without perceptible changes.
- **Decode Message:** Extract a hidden message from an encoded image file.
- **Supported Image Formats:** PNG, JPG, JPEG.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/muhammad-haziqul-khair/Steganographer.git
   cd SteganographyApp
2. Install Dependencies
   ```bash
   pip install -r requirements.txt

## Usage
1. Run the application:
   ```bash
   python main.py

### Encode

- Click on the "Encode" button to open the encoding window.
- Browse and select an image file (PNG, JPG, JPEG).
- Enter the message you want to hide in the image.
- Click "Encode" and choose a location to save the output image file.

### Decode
- Click on the "Decode" button to open the decoding window.
- Browse and select the encoded image file.
- Click "Decode" to reveal the hidden message.

## Screenshots
### Encoding Window
![ScreenShot1](https://github.com/muhammad-haziqul-khair/Steganographer/blob/main/s1.png)

### Decoding Window
![ScreenShot1](https://github.com/muhammad-haziqul-khair/Steganographer/blob/main/s2.png)

## License
This project is licensed under the MIT License 

