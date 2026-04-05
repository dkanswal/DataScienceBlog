# Stack Overflow Developer Survey – AI Adoption Analysis

## Project Motivation

With the rise of AI-assisted development tools, it is important to understand what drives developers to adopt these tools. This project analyzes the Stack Overflow Developer Survey dataset to identify key factors influencing AI adoption and to build a predictive model.

---

## CRISP-DM Process

### 1. Business Understanding
The goal of this project is to understand what factors influence the adoption of AI tools among developers and to predict whether a developer is likely to adopt AI-assisted tools.

---

### 2. Data Understanding
The dataset used is the Stack Overflow Developer Survey, which contains responses from thousands of developers worldwide. It includes information such as experience, technologies used, and attitudes toward AI.

---

### 3. Data Preparation
The dataset required several preprocessing steps:
- Handling missing values
- Converting experience-related columns into numeric format
- Encoding categorical variables for machine learning models

---

### 4. Modeling
A Random Forest classifier was used due to its ability to handle non-linear relationships and mixed data types effectively.

---

### 5. Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

The model demonstrated strong performance in predicting AI adoption.

---

## Business Questions

1. What factors influence the adoption of AI tools among developers?
2. Does developer experience impact AI tool adoption?
3. How do attitudes toward AI affect adoption behavior?
4. Can we accurately predict whether a developer will adopt AI tools?

---

## Key Results

- Developers with positive attitudes toward AI are more likely to adopt AI tools
- Experience and exposure to multiple technologies increase adoption likelihood
- Behavioral and attitudinal features are stronger predictors than demographics

---

## Files in Repository

- `StackOverflowSurvey.ipynb` → Main analysis notebook
- `README.md` → Project documentation
- `requirements.txt` → Required libraries

---

## Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Blog Post

Read the full blog here:  
https://medium.com/@dkanswal/this-blog-will-make-you-re-think-not-using-ai-for-software-development-bd0db110e793

---

## Acknowledgements

- Stack Overflow Developer Survey Dataset
- scikit-learn documentation
- Online ML learning resources