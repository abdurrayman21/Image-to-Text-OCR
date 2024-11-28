
# Optical Character Recognition (OCR) Using Python

This project provides an OCR solution to extract text from images using Tesseract and OpenCV. The solution preprocesses images for improved accuracy and supports multiple configurations for robust text extraction.

## Features

- **Image Upload**: Upload images directly from your system.
- **Advanced Preprocessing**: Enhances image quality using techniques like CLAHE, sharpening, and Otsu's thresholding.
- **Accurate OCR**: Utilizes Tesseract OCR with optimized configurations for improved text recognition.

## Installation

Follow these steps to set up the project:

1. Install Tesseract OCR:
    ```bash
    sudo apt-get update
    sudo apt-get install -y tesseract-ocr
    ```

2. Install required Python libraries:
    ```bash
    pip install pytesseract opencv-python-headless
    ```

## Usage

1. Run the notebook in a Colab environment or locally.
2. Upload an image for text extraction when prompted.
3. The extracted text will be displayed as output.

## Example

### Input Image:
![Example Input](images/example_image.png)

### Output Text:
```
This is an example ofExtracted Text:
Test Results Normal values (dog)
Red blood cells 4.95 5.5-8.5 x 10%/pl
Haemoglobin 11.0 12.0-18.0 g/dl
Monocyte count 10 <85%
Thrombocyte count 39 200-900 x 107/yl
Urea nitrogen 41.0 20-30 mg/dl
Creatinine 1.22 <1.1 mg/dl
Gamma-GT 10 1-9 U/l
Lipase TS 200-700 U/l
Babesia microti IFA IgG 1/2048* <1/16
Babesia microti IFA IgM 1/160* < 1/20
Anaplasma phagocytophilum 1/2048* < 1/64

IFA IgG
Anaplasma phagocytophilum 1/80* < 1/20

IFA IgM
168 cRNA PCR Positive Negative
Leishmaniasis Negative Negative
*Focus Diagnostics (Cypress, CA, USA). text extracted from the image.
```

## License

This project is open-source and available under the MIT License.
