# VOIS-TeamNo.320
Repository for project of VOIS, made by Team no 320.
Text Curator
We created a model to extract meaningful information from provided bill image by,
1) extracting text from image using a OCR (optical character recognition) model like Pytesseract.
2) Creating a NLP model to extract information from text using Spacy’s NER (named entity recognition) model.
3) Use Regex expressions for extracting emails, phone numbers etc where it can be used
4) Convert the output into extractable form
5) Finally, export the data into json format for further use.

Technologies we used to make this project are:
Pytesseract - OCR engine for OCR\n
Open CV - reading and manipulating image\n
Spacy - NLP library for NER model\n
JSON module - output the file in JSON format\n
Python - programming language
