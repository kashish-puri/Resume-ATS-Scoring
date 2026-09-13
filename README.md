# Resume ATS Scoring System

## Overview

The **Resume ATS Scoring System** is an NLP-based project that evaluates how well a resume matches a given job description. It uses **TF-IDF vectorization** and **Cosine Similarity** to calculate a matching score between the resume and job requirements.

The project aims to simulate the basic functionality of an **Applicant Tracking System (ATS)** used during the recruitment process.

## Objectives

* Automate basic resume screening.
* Extract and identify relevant skills from resumes and job descriptions.
* Convert textual information into numerical features using TF-IDF.
* Calculate resume-job similarity using Cosine Similarity.
* Generate an ATS-style matching score.

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* TF-IDF
* Cosine Similarity
* Google Colab

## Dataset

The project uses the **Resume Dataset** available on Kaggle.

**Dataset:** Resume Dataset
**Source:** Kaggle

The dataset contains resumes belonging to multiple job categories and is used for text preprocessing, feature extraction, and analysis.

## Methodology

The project follows these major steps:

1. **Dataset Collection**

   * Load the resume dataset from Kaggle.

2. **Data Cleaning**

   * Remove unnecessary columns.
   * Handle duplicate records.
   * Clean the resume text.

3. **NLP Preprocessing**

   * Convert text to lowercase.
   * Remove unwanted characters.
   * Tokenize text.
   * Remove stopwords.

4. **Skill Extraction**

   * Define job-specific skill taxonomies.
   * Identify relevant technical skills from the text.

5. **TF-IDF Vectorization**

   * Convert resume and job description text into numerical vectors.
   * Generate up to 1500 TF-IDF features.

6. **ATS Matching**

   * Calculate Cosine Similarity between the resume and job description.
   * Use the similarity score to determine the resume-job match.

7. **Result**

   * Generate an ATS-style matching score that indicates how closely the resume matches the given job description.

##Workflow

```text
Resume + Job Description
          ↓
     Text Cleaning
          ↓
   NLP Preprocessing
          ↓
    Skill Extraction
          ↓
    TF-IDF Vectorization
          ↓
   Cosine Similarity
          ↓
     ATS Match Score
```

## How to Run

1. Open the `.ipynb` notebook in **Google Colab**.
2. Download or connect the required Kaggle dataset.
3. Run the notebook cells sequentially.
4. Provide/use the required resume and job description text.
5. View the generated similarity/ATS score.

## Project Structure

```text
Resume-ATS-Scoring/
│
├── Resume_ATS_Scoring.ipynb
└── README.md
```

## Future Scope

* Improve skill extraction using advanced NLP techniques.
* Add semantic similarity using transformer-based models.
* Improve ATS scoring using multiple weighted factors.
* Support multiple job descriptions and resume ranking.
* Include experience, education, and keyword relevance in the scoring process.

## Contributors

* Kashish
