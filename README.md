# Resume Parser

## Overview
**Resume Parser** is a Python tool that extracts key information from resumes such as contact details, work experience, education, and skills. It simplifies resume screening for recruiters or developers creating job application systems.

## Features
- Extracts contact info (name, email, phone, LinkedIn).
- Parses work experience (job title, company, dates).
- Extracts education (degree, institution, graduation).
- Identifies skills using predefined patterns.
- Customizable for additional sections (certifications, projects).

## Installation
1. Install Python 3.x and required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Download spaCy language model:
    ```bash
    python -m spacy download en_core_web_sm
    ```

## Usage
1. Place resumes in `.pdf`, `.docx`, or `.txt` format.
2. Run the parser:
    ```bash
    python parse_resume.py --input path/to/resume.pdf
    ```
3. Output will be displayed in the terminal or saved to a file.

## File Structure
