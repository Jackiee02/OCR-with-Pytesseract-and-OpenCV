# OCR System using Pytesseract and OpenCV

This project demonstrates the implementation of an Optical Character Recognition (OCR) system using Pytesseract and OpenCV. The system is designed to preprocess images, extract text from images using Tesseract OCR, and evaluate the accuracy of the detected text. The preprocessing techniques include grayscale conversion, thresholding, noise removal, and edge detection to optimize OCR results.

## Features

- **Image Preprocessing**: Includes techniques like grayscale conversion, noise removal, thresholding, and edge detection to enhance the image for better OCR accuracy.
- **Text Detection and Extraction**: Pytesseract is used to detect and extract text from images. Various configurations are applied to customize the OCR process.
- **Bounding Boxes**: Bounding boxes are drawn around detected text to visually represent the location of the extracted text.
- **Text Accuracy Evaluation**: The confidence score of the extracted text is calculated to measure the accuracy of the OCR process.

## Prerequisites

Before running the notebook, ensure that you have installed the following:

- OpenCV
- Tesseract OCR
- Pytesseract
- Numpy

You will also need access to Google Colab or Jupyter Notebook to run the code.

## Setup

To run this project, follow these steps:

1. Clone the repository to your local machine.
2. Upload the Jupyter Notebook file to Google Colab or open it in Jupyter Notebook.
3. Install the required dependencies as outlined in the notebook.

## Usage

This notebook includes a step-by-step guide for:

1. Preprocessing images for optimal OCR results.
2. Extracting text from images using Pytesseract.
3. Visualizing text detection with bounding boxes.
4. Evaluating the accuracy of the extracted text.

## License

This project is licensed under the MIT License.
