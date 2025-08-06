# Albanian Legal Contract Extractor

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-WebApp-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This project extracts structured financial attributes from **Albanian-language PDF contracts**, covering both **personal** and **corporate loan agreements**. It parses key details such as loan amount, interest rate, NEI rate, and translates the credit purpose, exporting the data into clean Excel files.

> 🟢 **Live Demo**: [yashn.pythonanywhere.com](https://yashn.pythonanywhere.com/)

---

## 🔍 Features
- 🏢 Classifies PDFs into **Corporate** and **Personal** loan types  
- 📄 Extracts fields like **loan terms**, **parties involved**, **monetary values**, and **NEI rate**  
- 🌐 Automatically **translates loan purpose** from Albanian to English  
- 📤 Exports extracted data into clean, structured **Excel files**

---

## 📂 Output
- `Final_Corporate.xlsx` — contains extracted data from corporate loan contracts  
- `Final_Personal.xlsx` — contains extracted data from personal loan contracts  

---

## 🛠 Technologies Used
- Python 3  
- Flask (for web application)  
- PyPDF2  
- Deep Translator  
- Pandas  
- Regular Expressions  
- OpenPyXL

---

## 🚀 Setup Instructions

1. **Install dependencies**:
```bash
pip install Flask PyPDF2 deep-translator pandas openpyxl
```

2. **Run the app**:
```bash
python app.py
```

Or launch the notebook version:
```bash
Open ExtractLegalCont.ipynb in Jupyter/Colab
```

---

## 📎 Usage Notes
- Upload `.pdf`, `.zip`, or `.rar` files containing financial contracts.
- The app automatically detects the type (Corporate/Personal), processes, translates, and provides downloadable Excel outputs.
- Built to streamline multilingual document processing for financial institutions.
