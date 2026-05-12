Resume Matching Engine

A Python-based resume matching engine that uses TF-IDF and cosine similarity to rank candidates for a given job description.

Introduction

This project aims to develop a resume matching engine that can efficiently match candidates with job descriptions based on their skills and experience. The engine uses a combination of TF-IDF and cosine similarity to rank candidates and provide the top 3 matches for a given job description.

Features
Skill Normalization: Normalizes skills in resumes and job descriptions using a predefined dictionary of skill aliases.
TF-IDF Vectorization: Computes TF-IDF vectors for resumes and binary vectors for job descriptions.
Cosine Similarity: Calculates cosine similarity between resume TF-IDF vectors and job description binary vectors to rank candidates.
Ranking: Ranks candidates based on their cosine similarity with the job description and provides the top 3 matches.

Requirements
Python 3.8+: The project is built using Python 3.8+ and requires a compatible version to run.
No external libraries: The project does not use any external libraries and relies solely on built-in Python libraries.

Usage
Clone the repository: git clone https://github.com/your-username/resume-matching-engine.git
Navigate to the project directory: cd resume-matching-engine
Run the project: python main.py

Data

The project uses two datasets:
Resumes: A list of resumes with their corresponding skills and experience.
Job Descriptions: A list of job descriptions with their required and preferred skills.

Example Output

The project outputs the top 3 candidates for each job description, along with their cosine similarity score: