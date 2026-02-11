# Salary Prediction Model using Linear Regression

This project implements a **Multiple Linear Regression** model to automate salary estimations for an HR department. The model predicts a candidate's salary based on three key factors: experience, written test score, and personal interview score.

## 📌 Project Overview

The goal is to provide a data-driven approach to hiring by analyzing historical recruitment statistics. This helps ensure fair and consistent salary offerings for future candidates.

### Features:

* **experience**: Professional background (handles both text and numeric formats).
* **test_score**: Score out of 10 from a technical written test.
* **interview_score**: Score out of 10 from the personal interview.
* **salary($)**: The target variable the model aims to predict.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** * `Pandas`: For data manipulation and cleaning.
* `Scikit-Learn`: For building and training the Linear Regression model.
* `Word2Number`: To convert text-based experience (e.g., "five") into integers.


---

## 🚀 Workflow

The project follows a standard machine learning pipeline:

1. **Data Cleaning:** Handling missing values. Missing experience is filled with "zero," and missing test scores are filled with the column **median**.
2. **Data Transformation:** Converting word-based numbers into numerical data.
3. **Model Training:** Fitting a Linear Regression model to the historical data.
4. **Prediction:** Generating salary estimates for new candidate profiles.

---

## 📊 Results

The model was tested with two sample candidates:

| Candidate | Experience | Test Score | Interview Score | Predicted Salary |
| --- | --- | --- | --- | --- |
| **New Hire 1** | 2 Years | 9 / 10 | 6 / 10 | **$53,205.97** |
| **New Hire 2** | 12 Years | 10 / 10 | 10 / 10 | **$92,002.18** |

---

## 💻 How to Run

1. Clone this repository.
2. Ensure you have `hiring (1).csv` in the same directory.
3. Install dependencies:
```bash
pip install pandas scikit-learn word2number

```


4. Run the Jupyter Notebook or Python script to see the results.

---

