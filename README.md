Document Research & Theme Identification Chatbot
Overview
This FastAPI application allows users to upload documents and query them for information using a chatbot interface.

Requirements
Python 3.x
FastAPI
Uvicorn
Ngrok
Tesseract OCR
pdf2image
Pillow
Setup Instructions
Clone the Repository:

bash
Run
Copy code
git clone https://github.com/your-username/document-chatbot.git
cd document-chatbot
Install Dependencies:

bash
Run
Copy code
pip install -r requirements.txt
Run the Application:

bash
Run
Copy code
uvicorn app.main:app --host 0.0.0.0 --port 8000
Expose with Ngrok:

bash
Run
Copy code
ngrok http 8000
Copy the ngrok URL provided.

Usage Instructions
Open the ngrok URL in your web browser.
Upload Documents: Use the upload form to submit at least 75 documents (PDFs or images).
Query Documents: Enter your query in the input field and submit to receive answers.
License
This project is licensed under the MIT License.
