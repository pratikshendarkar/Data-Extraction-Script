# Data-Extraction-Script

This Python script is designed to extract specific information from PDF and DOCX resume files. The main features of this script include extracting contact information (mobile number, email), GitHub and LinkedIn links, and dates associated with experience sections from resumes. Additionally, it includes various methods to detect and parse dates in text.


Convert PDF to Text: Uses pdfminer to convert PDF files into text.
Extract Contact Information: Regex patterns to locate mobile numbers, emails, GitHub, and LinkedIn links.
Experience Extraction: Extracts the "Experience" section from resumes and attempts to parse dates.
Date Parsing: Multiple methods for date detection using libraries like dateparser, dateutil, pygrok, and nltk
