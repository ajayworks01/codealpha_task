# Credit Scoring Model – CodeAlpha Internship (Task 1)

## Objective
To predict an individual's creditworthiness using past financial data.

The model classifies whether a person is likely to default on credit
based on financial and demographic features.

---

## Dataset
- Source: Kaggle  
- Dataset Name: Give Me Some Credit  
- File Used: cs-training.csv  

Target Variable:
- SeriousDlqin2yrs  
  - 1 → Bad Credit
  - 0 → Good Credit

Dataset was downloaded manually from Kaggle as a ZIP file and uploaded to Google Colab.

---

## Approach
1. Data loading and cleaning
2. Handling missing values using median
3. Feature scaling using StandardScaler
4. Train-test split
5. Logistic Regression model training
6. Model evaluation using standard classification metrics

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## How to Run the Project
1. Open `credit_scoring_model.ipynb` in Google Colab
2. Upload the Kaggle ZIP dataset
3. Run all cells in order
4. View evaluation metrics and confusion matrix

---

## Output
- Trained Logistic Regression model
- Saved model file (`credit_scoring_model.pkl`)
- Scaler file (`scaler.pkl`)

---

## Internship
This project was completed as **Task 1** for the **CodeAlpha Data Science Internship**.
