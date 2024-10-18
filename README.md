# OCR System using OpenCV and Pytesseract

## Introduction

This project implements an Optical Character Recognition (OCR) system using OpenCV for image preprocessing and Pytesseract for text extraction. It demonstrates various techniques for image enhancement, such as grayscale conversion, thresholding, dilation, and edge detection, to improve the accuracy of the OCR process. The system can also evaluate the confidence score of detected text and perform template matching for specific patterns, such as dates.

The code runs in a Jupyter Notebook format on Google Colab and is designed to work with images stored in Google Drive. The goal of the project is to efficiently extract text from images while optimizing for both speed and accuracy.

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
