# ATS Resume Tracker

## Overview
The ATS Resume Tracker is a tool built using Streamlit that allows users to upload their resumes in PDF format and assess how well they align with job descriptions, ensuring they meet Applicant Tracking System (ATS) criteria. The tool processes resumes, extracts key information, and compares them against job-specific keywords to improve their chances of passing ATS filters. It utilizes Google Generative AI for generating suggestions and improvements for the resume.

## Features
- Resume Upload: Upload resumes in PDF format.
- Keyword Extraction: Extract and compare keywords from resumes and job descriptions.
- Generative AI Suggestions: Get resume improvement suggestions using Google Generative AI.
- User-Friendly Interface: Built with Streamlit for an easy-to-use web interface.
## Technologies Used
- Streamlit: For creating the user interface.
- PyPDF2: For parsing and extracting text from PDF resumes.
- google.generativeai: To generate suggestions for improving resume alignment with job descriptions.
- python-dotenv: For managing environment variables securely.
## Installation
1. Clone the repository:
   ``` bash
   git clone https://github.com/harsha0603/ATS-resume-tracker
   cd ATS-resume-tracker
   ```
2. Install dependencies:
   ``` bash
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   Create a .env file and add your Google API credentials.
   Add the following to your .env file:
   ``` bash
   GOOGLE_API_KEY=your_google_api_key
   ```
4. Run the app:
   ``` bash
   streamlit run app.py
   ``` 
