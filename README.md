# Image-Encryption-and-Decryption-Linear-Algebra-Project
This repository contains a Linear Algebra project on image encryption and decryption. It includes: 
Presentation: An overview of objectives, methods, and results.
Report: Detailed background, implementation, and conclusions.
Source Code: Python scripts for encrypting and decrypting images. The project applies linear algebra to secure image data.

**Project Overview**

This project demonstrates the application of linear algebra techniques in the field of image processing, specifically focusing on image encryption and decryption. The project includes a detailed report, a presentation, and the source code implemented in Python.

Contents The repository contains the following files:

**Presentation:** A PowerPoint presentation, outlining the objectives, methods, and results of the project. Report: A comprehensive report detailing the project, including the theoretical background, methodology, results, and conclusions. Source Code: Python scripts that implement the image encryption and decryption algorithms.

Project Description Image Encryption The image encryption process involves the following steps:

**Loading the Image:** The image is loaded and converted to a NumPy array. Quadrant Division: The image is divided into 256 equal-sized quadrants. Row and Column Swapping: Each quadrant undergoes row and column swapping to encrypt the image. Reconstruction: The encrypted quadrants are combined to form the final encrypted image.

Image Decryption The image decryption process involves the reverse of the encryption steps:

**Loading the Encrypted Image:** The encrypted image is loaded and converted to a NumPy array.
**Quadrant Division:** The encrypted image is divided into 256 equal-sized quadrants.
**Row and Column Swapping:** Each quadrant undergoes row and column swapping to decrypt the image.
**Reconstruction:** The decrypted quadrants are combined to form the final decrypted image.

**How to Run the Code**

Ensure you have Python and the required libraries installed (PIL and numpy). Place the image file (gray.png) in the same directory as the Python script. Run the encrypt_decrypt.py script to perform the encryption and decryption:

**python encrypt_decrypt.py**

The script will save encrypted_image.png and decrypted_image.png in the same directory.

**Dependencies**

Python 3.x NumPy PIL (Pillow)




