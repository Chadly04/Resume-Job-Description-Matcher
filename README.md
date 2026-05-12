# Resume Job Description Matcher

## Description
The Resume Job Description Matcher is an NLP project that compares a resume with a job description and calculates how closely they match. The project uses text preprocessing, keyword extraction, vectorization, and cosine similarity to generate a match score and identify missing keywords.

This project was built to help users understand how well their resume aligns with a specific job description and what skills or keywords they may need to add.

## Features
- Cleans and preprocesses resume and job description text
- Extracts important keywords from both documents
- Compares resume keywords with job description keywords
- Calculates a match score using TF-IDF and cosine similarity
- Identifies missing keywords from the resume
- Helps suggest areas where the resume can be improved

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

## How It Works
1. The user provides resume text and job description text.
2. The text is cleaned by removing unnecessary characters and converting words to lowercase.
3. Important keywords are extracted from both the resume and job description.
4. The keywords are converted into numerical vectors using TF-IDF.
5. Cosine similarity is used to compare the resume vector and job description vector.
6. A match score is calculated as a percentage.
7. Keywords found in the job description but missing from the resume are displayed.

## Example Output
```text
TF-IDF Cosine Similarity: 0.82
Match Score: 82.35%

Missing Keywords:
- REST API
- Bag of Words
- text classification
- code reviews