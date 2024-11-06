# PRODIGY_ImageEncryption_Task02
# Pixel Manipulation for Image Encryption

This project is part of the Prodigy Infotech internship, where we explore image encryption through pixel manipulation techniques in Python. This tool allows users to encrypt and decrypt images by applying pixel-level transformations, providing a basic layer of image security.

## Features
- **Pixel Value Manipulation**: Encrypts an image by altering the RGB values of each pixel based on a mathematical operation.
- **Key-Based Encryption**: Users can set a numeric key (shift value) to customize the encryption, adding an extra layer of security.
- **Reversible Transformation**: The same key can be used to decrypt the image, restoring it to its original form.

## How It Works
This tool uses a Caesar cipher-inspired method, but instead of text, it modifies pixel values in an image:
- During encryption, the program applies a specific transformation to each pixel's RGB values.
- During decryption, the program reverses this transformation using the same key, restoring the original pixel values.

## Technologies Used
- **Python 3.x**
- **Pillow** library for image manipulation

## Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone https://github
