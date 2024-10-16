# Prerequisites
All scripts rely on several Python libraries. Below is a list of the libraries required for each script. You can install the dependencies via pip:
```bash
pip install pandas scikit-learn pymongo certifi requests beautifulsoup4 nltk joblib Pillow pytesseract tensorflow
```
Additionally, ensure you have **Tesseract-OCR** installed for the OCR functionalities, and **Docker** is configured properly to run the containerized services.



**Overview:** Developed a script to automatically extract temporal data (dates, timestamps) from images, integrating OCR, image processing, and pattern recognition techniques.

**Steps and Tools:**

1. **Image Processing:** Used PIL (Python Imaging Library) to preprocess images, including resizing, grayscale conversion, and noise reduction.
2. **Text Extraction:** Integrated Tesseract OCR to convert image content to text.
3. **Pattern Recognition:** Employed regular expressions (regex) to identify and extract temporal data patterns such as dates and timestamps from the OCR output.

**Impact:** This script automated the extraction of temporal information from images, enhancing data processing capabilities in scenarios where dates and times need to be extracted from scanned documents or photos.
