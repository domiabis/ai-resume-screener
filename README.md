# ai-resume-screener
An NLP-based project that ranks resumes against a given job description using TF-IDF and cosine similarity.

## Features
- Extracts text from PDF resumes
- Cleans and preprocesses text using NLTK
- Calculates similarity scores between resumes and JD
- Extracts key skills found in each resume

## Tech Stack
Python, Pandas, NLTK, Scikit-learn, pdfplumber

## Example Output
| Candidate | Match Score (%) | Key Skills Found |
|------------|----------------|------------------|
| resume_alice.pdf | 87.4 | sql, python, power bi, data cleaning |
| resume_rahul.pdf | 63.2 | excel, tableau, sql |
| resume_sneha.pdf | 22.1 | No major skills found |

## Future Improvements
- Streamlit web app for interactive uploads
- Resume scoring dashboard
