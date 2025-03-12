AI-powered Resume Screening and Ranking System

The AI-powered Resume Screening and Ranking System is designed to automate the resume evaluation process by analyzing candidates' resumes and ranking them based on their relevance to a given job description. It leverages Natural Language Processing (NLP) techniques, specifically TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity, to compare resume content with the job description and rank candidates accordingly.

This system is implemented as a Streamlit web application, allowing recruiters to upload multiple PDF resumes and receive ranked results based on their similarity to the job requirements.

-Extracting Text from Resumes
Candidates typically submit their resumes in PDF format.
The system extracts textual content from these resumes, including details about skills, experience, education, and achievements.
This extracted data is then processed for further analysis.

-Processing the Job Description
The recruiter provides a job description, which outlines the required skills, experience, and qualifications.
The system treats this job description as a reference document to compare against all resumes.

-Transforming Text into a Numerical Format
Both the job description and resumes are converted into a numerical representation using Natural Language Processing (NLP) techniques.
This transformation allows the system to quantify the similarity between job requirements and candidate resumes.

-Comparing Resumes to the Job Description
The system calculates the similarity score between each resume and the job description.
The higher the score, the better the match between a resume and the job role.

-Ranking Candidates Based on Relevance
Once similarity scores are computed, resumes are ranked in descending order based on their relevance to the job description.
This helps recruiters quickly identify the most suitable candidates.

-Displaying Results in an Interactive Web Application
The system presents the ranked resumes in a user-friendly interface, where recruiters can view the results.
Resumes with the highest scores appear at the top, making it easy to shortlist candidates for interviews.

Installation

Prerequisites:

Ensure you have Python installed on your system. Install the required dependencies using:

       pip install streamlit PyPDF2 scikit-learn pandas
Usage:

Run the application using the command:

            streamlit run app.py


