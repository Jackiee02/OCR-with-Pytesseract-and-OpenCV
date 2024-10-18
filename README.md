# OCR System using OpenCV and Pytesseract

## Introduction

The goal of this project is to detect and extract text from images using OpenCV and Pytesseract. Optical Character Recognition (OCR) is a technology used for converting different types of images that contain text into machine-readable formats. OpenCV is used for preprocessing the images, while Pytesseract handles the OCR part. This project evaluates the efficiency and effectiveness of the OCR system, using various image preprocessing techniques to improve accuracy.

The code runs in a Jupyter Notebook format on Google Colab and is designed to work with images stored in Google Drive. The goal of the project is to efficiently extract text from images while optimizing for both speed and accuracy.

## Project Outline

This notebook includes a step-by-step guide for:

1. Preprocessing images for optimal OCR results.
2. Getting boxes around text
3. Getting boxes around text words
4. Text template matching
5. Custom detection, only numbers
6. Blacklisting characters
7. Script, run in loop for read pages
8. Evaluate the accuracy of detected text
   
## Features

- Image preprocessing (grayscale, noise removal, thresholding, etc.)
- Text extraction using Pytesseract
- Bounding box creation around detected text
- Confidence score evaluation of the detected text
- Custom text detection (e.g., numbers only, blacklisting characters)
- Template matching for specific patterns (e.g., dates)
- Performance evaluation in terms of time taken for each process

## Prerequisites

- Google Colab or Jupyter Notebook environment
- OpenCV and Pytesseract libraries installed
- Tesseract-OCR installed on the system

## Usage

Upload the notebook to Google Colab or any Jupyter Notebook environment and ensure that the necessary libraries are installed. The notebook contains cells that can be run sequentially to process images and extract text.

Ensure that images are stored in a Google Drive directory if working in Colab, and update the paths to match your directory structure.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
