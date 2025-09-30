# Loan Approval Prediction

This project contains a machine learning model to predict loan approval based on applicant details.  
The notebook is implemented in **Google Colab**.

## File
- `loan_approval.ipynb` → Main notebook with preprocessing, model training, and evaluation.

## How to Use
1. Open the notebook in google colab
2. Run all cells to see the workflow and results.

## Requirements
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seabo
## 📊 Results & Insights

- The machine learning model was trained to classify whether a loan should be **Approved** or **Rejected**.  
- After training and evaluation:
  - Accuracy achieved: ~77%.  
  - Precision: The model correctly identified approved loans with good reliability.  
  - Recall: The model was able to capture most of the truly approved applicants.  

### Key Insights
- **Applicant Income** and **Credit History** were the most important features influencing loan approval.  
- Applicants with a **good credit history** had a significantly higher chance of approval.  
- Income level and loan amount balance also played a major role in prediction accuracy.  
- Gender and marital status showed less impact compared to financial features.  

These insights can help banks/financial institutions in designing fairer and more efficient loan approval processes.
