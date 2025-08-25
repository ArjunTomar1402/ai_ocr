# AI OCR

A lightweight Python-based OCR tool featuring a web interface to upload images and extract text in real time.

---

## Features

- OCR using Python libraries such as **Pillow**, **pytesseract**, and optionally **OpenCV**
- Minimal web interface built with Flask or Streamlit
- Straightforward dependency management via `requirements.txt`
- Live demo available for quick testing

---

## Live Demo

Experience it firsthand:  
**[Live Demo – AI OCR App](https://ai-ocr-v1.streamlit.app/)**

---

## Getting Started

### Prerequisites

- Python 3.7 or later
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) installed, or you can use a cloud-based OCR engine if preferred

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/ArjunTomar1402/ai_ocr.git
   cd ai_ocr
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
python app_v6.py
Visit http://localhost:8501 (Streamlit) or your configured Flask port to start extracting text.

Usage
Upload your image (screenshots, photos, scanned documents)

The app processes it and displays the extracted text instantly

Copy or download the text as needed

Project Structure
csharp
Copy
Edit
.

├── app_v6.py          # Main application script

├── requirements.txt   # Python dependencies

├── static/            # Static assets (CSS, images)

└── README.md          # This file

Contact
For questions or feedback, reach out via GitHub or email me at [arjuntomar.work@gmail.com].
