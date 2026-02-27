# DocuMind-Ai
Intelligent Document Processing System

DocuMind AI is a full-stack web application that automates document data extraction using OCR (Optical Character Recognition).

It allows users to upload scanned invoices or documents, automatically extracts structured data (Invoice No, Date, Amount, etc.), stores it in a database, and displays the extracted information in a clean dashboard.

This project demonstrates backend development, OCR integration, database management, and frontend design using Python and Web Technologies.

 Features

 Upload scanned documents (PDF / JPG / PNG)

 Extract text using Tesseract OCR

 Detect structured fields:

Invoice Number

Date

Total Amount

 Store extracted data in SQLite database

 Interactive dashboard to view stored records

 Generate PDF reports using ReportLab

 Login & Logout system

 Clean and responsive HTML/CSS UI

 Tech Stack - 
 
🔹 Frontend

HTML5

CSS3

Jinja2 Templates

🔹 Backend

Python

Flask

🔹 OCR Engine

Tesseract OCR

pytesseract

🔹 Database

SQLite

🔹 PDF Generation

ReportLab

⚙️ Installation & Setup - 

1️⃣ Clone the Repository

git clone https://github.com/your-username/documind-ai.git

cd documind-ai

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Install Tesseract OCR

Download from:

👉 https://github.com/tesseract-ocr/tesseract

After installation, make sure Tesseract is added to your system PATH.

If not, add manually in app.py:

pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"

4️⃣ Run the Application

python app.py

Open in browser:

http://127.0.0.1:5000

How It Works -

User uploads a scanned invoice.

The backend saves the file in /uploads.

Tesseract OCR extracts raw text.

Python processes the text to identify structured fields.

Extracted data is stored in SQLite.

Dashboard displays all extracted records.

Optional PDF report can be generated.

Use Cases - 

Invoice Automation

Small Business Accounting

Document Digitization

Learning OCR + Flask Integration

Hackathon Projects

