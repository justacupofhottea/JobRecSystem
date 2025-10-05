# Fair Job Recommendation System

## Overview
Traditional job recommendation systems often struggle with **biases**, which can lead to unequal opportunities for candidates from different demographic groups. This project develops a **fair and accurate job recommendation system** designed to generate high-quality, real-time recommendations while mitigating bias.  

Conducted in collaboration with **Laboratoire Hubert Curien** and **Inasoft**, the project focuses on addressing fairness and improving candidate-job matching efficiency for millions of users.

---

## Key Features
- **Fairness-Aware Recommendations:** Integrates bias mitigation strategies to ensure equitable opportunities across demographics.  
- **Ranking-Based Approach:** Assigns ranks to candidates for each job based on similarity scores.  
- **Similarity Matching:** Uses embeddings of job descriptions and candidate profiles for candidate-job matching.  
- **Evaluation Metrics:** Employs **Max Accuracy, Precision, Recall**, and plans to integrate **Precision@k, Recall@k, and NDCG** for refined evaluation.  
- **Real-Time Recommendations:** Scales to handle hundreds of job postings and millions of candidates.  

---

## Problem Formulation
- Let **J** be the set of jobs:  
  `J = {j1, j2, ..., jn}`  
- Each job **j** has a corresponding set of candidates **Cj**:  
  `Cj = {c1, ..., cm}`  
- Candidate and job embeddings are computed from textual descriptions (CVs, job titles, required profiles).  
- The goal is to define a ranking function **Φ** such that accepted candidates are ranked within a specified limit (e.g., Top 5) for each job:  

