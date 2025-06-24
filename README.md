# Albanian Legal Contract Extractor

This project extracts structured financial attributes from Albanian-language PDF contracts (both personal and corporate loans). It parses key fields such as loan amount, interest rate, NEI rate, and more, translating the credit purpose and exporting the data to Excel.

## Features
- Classifies PDFs into corporate and personal
- Extracts loan terms, parties, and monetary values
- Translates the loan purpose to English
- Outputs to clean Excel files

## Output
- `Final_Corporate.xlsx`
- `Final_Personal.xlsx`

## Technologies Used
- Python 3
- PyPDF2
- Deep Translator
- Pandas
- Regular Expressions

## Setup
Install dependencies:
```bash
pip install PyPDF2 deep-translator pandas openpyxl
```
Run `ExtractLegalCont.ipynb` in Colab or Jupyter.
