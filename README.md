# 📄 AI Resume Parser

An AI-powered Resume Parser built with Flask that extracts and organizes key sections like **Skills**, **Experience**, **Education**, and **Projects** from uploaded PDF resumes. This tool helps streamline the resume screening process by converting unstructured resume data into clean, structured output.

---

## 🚀 Features

- 📤 Upload PDF resumes via a user-friendly web interface  
- 📌 Automatically extract:
  - Contact Info
  - Skills
  - Work Experience
  - Education
  - Projects
- 🧠 Built using **PyMuPDF** for fast and accurate text extraction
- 🌐 Flask-based backend for rapid deployment
- 📱 Responsive frontend design

---

## 📦 Tech Stack

- **Python 3.10+**
- **Flask**
- **PyMuPDF (`fitz`)**
- **HTML/CSS with Font Awesome**

---

## 🖼️ UI Preview

![Screenshot](screenshot.png) <!-- Add your screenshot image in the root directory -->

---

## 🛠️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/resume-parser.git
   cd resume-parser
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask server:

bash
Copy
Edit
python main.py
Open in browser:
Visit http://127.0.0.1:5000

📂 Folder Structure
vbnet
Copy
Edit
resume-parser/
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── main.py
├── requirements.txt
└── README.md
