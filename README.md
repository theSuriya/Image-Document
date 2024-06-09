# Image-to-Document Converter

## Overview

This project is an Image-to-Document converter application built using the Gemini API and Streamlit. The app allows users to convert images into editable text documents, maintaining the font and layout of the original image. It's a perfect addition to your resume to showcase your skills in tech and programming.

## Features

- Convert images (PNG, JPG, JPEG) to editable Word documents.
- Preserves the font and layout of the original image.
- User-friendly interface with Streamlit.
- Open-source code for customization and learning.

## Demo

![APP Screenshot](image-document.png)

## Getting Started

### Prerequisites

- Python 3.x
- Streamlit
- Google Generative AI (`google-generativeai`)
- Tesseract OCR (if required)
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/theSuriya/Image-Document.git
    cd Image-Document
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up the Google API Key:
    - Obtain an API key from Google Generative AI.
    - Set the environment variable `GOOGLE_API_KEY` with your API key.

### Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open the app in your browser and upload your image file.
3. Click "Generate Document" to convert the image to a Word document.
4. Download the generated document.

### Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Contact
For any questions or feedback, feel free to reach out:

contact [Email:](thesuriya3@gamil.com)

### Acknowledgments
- Gemini API for their powerful OCR tool.
- Streamlit for providing an easy-to-use web app framework.
- Open source community for providing valuable resources and support.
