# blood-report-parser
An AI-powered system that extracts key parameters from blood reports and generates a structured Electronic Health Report (EHR).

Features:
1. OCR-based text extraction from scanned reports (images/PDFs).
2. AI-powered Named Entity Recognition (NER) to identify test names, values, and units.
3. Standardization & FHIR-based EHR generation for structured output.
4. REST API for backend processing using FastAPI.
5. User-friendly React frontend for easy file upload and result visualization.

Tech Stack:
1. Backend: Python, FastAPI, Tesseract OCR, OpenCV, spaCy, Transformers
2. Frontend: React.js, Tailwind CSS
3. Database (Optional for storage): PostgreSQL / MongoDB
4. Deployment: Docker, Heroku / AWS
