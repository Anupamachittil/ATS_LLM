# Smart ATS

## Overview

Smart ATS is a Streamlit application designed to evaluate resumes against job descriptions using Google Generative AI. It helps users improve their resumes by providing insights on how well they match a given job description.

## Features

- **Resume Evaluation:** Upload a PDF resume and get a detailed evaluation.
- **Job Description Matching:** Paste the job description to see how well the resume matches.
- **Percentage Match:** Get a percentage indicating how well the resume matches the job description.
- **Missing Keywords:** Identify missing keywords that are critical for the job role.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
## Installation

2. **Set Up Environment:**

   Ensure you have Python 3.7 or later installed.

   Create a virtual environment and activate it:

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
3. **Install the required dependencies:**
    
    You can install it by 
    ```bash
   pip install -r requirements.txt


4. **Configure API Key:**

   Replace `your_api_key_here` with your actual Google API key in the `app.py` 
   Simply create an api key by https://makersuite.google.com/app/apikey clicking this link and create your api key
5. **Usage**
    Run the application using the command below
    ```bash
   streamlit run app.py
   