# ATS Resume Expert

A Streamlit app that utilizes Google's Generative AI to evaluate resumes against job descriptions.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [How it Works](#how-it-works)
- [Installation and Usage](#installation-and-usage)
- [Dashboard Image](#dashboard-image)

## About the Project

ATS Resume Expert is a web application designed to help job seekers and recruiters evaluate resumes against specific job descriptions. The app uses Google's Generative AI to analyze the resume and provide feedback on its relevance to the job requirements.

## Features

- Evaluate resumes against job descriptions using Google's Generative AI
- Provide feedback on resume strengths and weaknesses
- Calculate the percentage match between the resume and job description
- Identify missing keywords in the resume

## How it Works

1. User uploads their resume (PDF) and inputs the job description
2. The app converts the PDF to an image and sends it to Google's Generative AI API
3. The API analyzes the resume and job description, providing feedback and a percentage match
4. The app displays the results to the user

## Installation and Usage

### Prerequisites
- Python 3.8+
- Streamlit
- Google API credentials
- pdf2image

### Steps
1. Clone the repository:
```
https://github.com/jkp007/ats-resume-checker.git
```
2. Install the required libraries:
```
pip3 install -r requirements.txt
```
3. Store GOOGLE_API_KEY in a .env file:
```
GOOGLE_API_KEY=your-api-key
```
4. Run the app:
```
streamlit run app.py
```
## Dashboard Image
![image](https://github.com/user-attachments/assets/3c3bef64-076e-49e2-918e-9513627f2b49)

