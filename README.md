# Offer Generator V1.0

Streamlit app to generate quotations:
- Enter part numbers + quantities (PN,Qty per line).
- Looks up price from PL102025.xlsx (USD/EUR blocks).
- Auto-fills Word template (quotation_templateR.docx).
- Logs offers in offer_log.xlsx.
- Manages customers in customers.xlsx.

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```
