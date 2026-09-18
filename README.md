# 📄Resume Role Classifier

An NLP-powered multiclass classification project that automatically predicts the job-role category of a resume using TF-IDF and Support Vector Machine (SVM).

## Project Overview

Recruiters often need to process a large number of resumes and identify the most relevant job-role category for each candidate.

This project uses Natural Language Processing (NLP) and Machine Learning to classify resumes into **25 different job-role categories** based on their textual content.

### Classification Type

This is a **Multiclass Classification** problem because the model predicts one category from multiple possible classes.

## Project Workflow

```text
Resume Text
     ↓
Text Cleaning & Preprocessing
     ↓
Handling Class Imbalance
     ↓
Label Encoding
     ↓
TF-IDF Feature Extraction
     ↓
Train-Test Split
     ↓
SVM with One-vs-Rest
     ↓
Predicted Job Role
