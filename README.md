# ATS Resume Expert

## Overview

**ATS Resume Expert** is a Streamlit application designed to help job seekers evaluate their resumes against job descriptions using AI. The application leverages Google’s generative AI to provide insights on how well a resume matches a job description and offers professional evaluations on strengths and weaknesses.

## Features

- Upload your resume in PDF format.
- Input a job description to evaluate against your resume.
- Get a percentage match and feedback on your resume's alignment with the job description.
- Professional evaluation of strengths and weaknesses.

## Prerequisites

- Python 3.6 or higher
- Required packages:
  - `streamlit`
  - `python-dotenv`
  - `Pillow`
  - `pdf2image`
  - `google-generativeai`

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/ATS-Resume-Expert.git
   cd ATS-Resume-Expert
   
2. Install the required packages:
   ```bash
    pip install -r requirements.txt

3. Create a .env file in the root directory and add your Google API key:
  ```bash
    GOOGLE_API_KEY=your_api_key_here


## Usage

1. Run the Streamlit application:
  ```bash
      streamlit run app.py

2. Open your browser and navigate to http://localhost:8501.

3. Input the job description and upload your resume in PDF format.

4. Click on "Tell Me About the Resume" or "Percentage Match" to get the evaluation.

## Code Structure

- `app.py: The main Streamlit application file.`
- `.env: Environment variables for API keys and configurations.`
- `requirements.txt: Python package dependencies.`




    

