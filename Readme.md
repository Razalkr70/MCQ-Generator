
MCQ Generator is a Flask-based web application that allows users to generate multiple-choice questions (MCQs) from text input. This tool is useful for educators, students, and content creators looking to automate quiz generation.  

## Features  
✅ Accepts text input via URL, manual entry, or file uploads (PDF/TXT)  
✅ Generates multiple-choice questions dynamically  
✅ Users can select the number of questions to generate  
✅ Displays correct answers for review  
✅ Allows MCQ download as a PDF  
✅ Simple and user-friendly interface  

## Technologies Used  
- Flask (Backend)  
- BeautifulSoup & Requests (Web Scraping)  
- PyPDF2 (PDF Processing)  
- Spacy (NLP Processing)  
- ReportLab (PDF Generation)  
- Bootstrap (Frontend UI)  

## Features

- **MCQ Generation:** Automatically generates MCQs by processing input text, PDFs, or URLs.
- **NLP & Deep Learning:** Uses spaCy for text processing and a TensorFlow/Keras LSTM model to understand sentence structures.
- **PDF Download:** Allows users to download the generated MCQs as a PDF.
- **Responsive UI:** Utilizes Flask-Bootstrap for a clean, responsive web interface.

### Generate MCQs:

- Provide input via a URL, manual text, or by uploading PDF/TXT files.
- Select the number of questions to generate.
- Click on Generate MCQs.
-View the generated questions and optionally download them as a PDF.

### View Detailed Results:

- A detailed view is available which shows each question, its options, and the correct answer.
