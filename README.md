# 💼 Data Professional Salary Prediction – Multi-Model Analysis in Python

📊 **Dashboard Snapshot**  
*Modeling and analysis done in Google Colab across 3 structured notebooks.*  

## 🔗 Clickable Code Notebooks

To see the code for each part, click on the corresponding image below:

<table align="center">
  <tr>
    <td align="center">
      <a href="https://colab.research.google.com/drive/1m2-gHjXLsuhxrOv5BPgGM6YLL4d7TTtz?usp=sharing#scrollTo=paVC4Oy-_Pra" target="_blank">
        <img src="https://github.com/user-attachments/assets/4b5bdc15-720e-41d1-b1f4-728ee99b34cc" width="200px" title="Cleaning, Pre-processing, Feature Eng" />
      </a><br>
      <b>Part 1: Cleaning, Pre-processing, Feature Eng</b>
    </td>
    <td align="center">
      <a href="https://colab.research.google.com/drive/1_dS4rFvlXuede9MJc9Hv92Dz7GrOquK4?usp=sharing#scrollTo=9YulASxdLhul" target="_blank">
        <img src="https://github.com/user-attachments/assets/bd93bd8e-1963-4e82-837a-eeb3146ff59c" width="200px" title="Linear Regression Output" />
      </a><br>
      <b>Part 2: Linear Regression Output</b>
    </td>
    <td align="center">
      <a href="https://colab.research.google.com/drive/19OZFjNbolmb5uYKmX3JhMb79bgbhsaIY?usp=sharing#scrollTo=bml3c4fwaNR3" target="_blank">
        <img src="https://github.com/user-attachments/assets/20d7d11e-2787-4503-b8ae-34007f780149" width="200px" title="ML Classification Accuracy Comparison" />
      </a><br>
      <b>Part 3: Classification Accuracy Comparison</b>
    </td>
  </tr>
</table>

---

## 🔍 Overview  
This project explores and predicts salaries for data professionals (Data Analysts, Data Scientists, Data Engineers, etc.) across various U.S. states. Built in three comprehensive phases, the analysis covers data cleaning, exploratory data analysis (EDA), regression modeling, and classification-based prediction of salary satisfaction.

It helps answer business-critical questions such as:
- How do job titles and locations affect data salaries?
- Can we estimate salary ranges using linear regression?
- Can we predict whether a salary is satisfactory or not using classification models?

---

## ❓ Business Questions Answered
- What are the key factors affecting data professional salaries in the U.S.?
- Can we accurately estimate salary using regression?
- How well do different classification models perform in determining salary satisfaction?
- Which features (job title, rating, location) are most predictive of a “good” salary?

---

## ⚙️ Project Structure

### 🔹 Part 1: Data Preprocessing & EDA  
 
- Imported essential libraries  
- Mounted Google Drive and imported dataset  
- Data understanding and assessment  
- Data cleaning and transformation  
- Exploratory Data Analysis (EDA)  
- Feature engineering for modeling

---

### 🔹 Part 2: Linear Regression Modeling  

- Trained a Linear Regression model to estimate salaries  
- Model performance: **MAE ≈ 23.71**  
- Saved trained model for future use

---

### 🔹 Part 3: Classification Modeling  

Objective: Predict whether a salary is satisfactory (binary classification)

Models applied:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest (Best Model)

---

## 📈 Key Metrics & Results

### 🔢 Regression Model
| Model              | Goal              | Metric         | Value    |
|-------------------|-------------------|----------------|----------|
| Linear Regression | Salary Prediction | MAE            | 23.71    |

### 🧪 Classification Models (Satisfactory Salary Prediction)

| Model                | Accuracy |
|----------------------|----------|
| **Random Forest**    | 0.81     |
| Decision Tree        | 0.64     |
| K-Nearest Neighbors  | 0.65     |
| Logistic Regression  | 0.69     | 

> ✅ *Random Forest* outperformed all other classifiers with the highest accuracy and balanced precision, recall, and F1-score.  
> 📉 Other models show moderate performance, offering comparison for further tuning or ensembling.

---

## 🧠 Tools and Techniques Used  
- Python (Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib)  
- Regression and Classification Models  
- Google Colab  
- Exploratory Data Analysis  
- Feature Engineering

---

## 📎 Clone This Repository

```bash
# Using HTTPS
git clone https://github.com/iman-ezatfar/DataScience-Pipeline-ML-Salary-Prediction.git
```
# Using SSH
```bash
git clone git@github.com:iman-ezatfar/DataScience-Pipeline-ML-Salary-Prediction.git
```
# Using GitHub CLI
```bash
gh repo clone iman-ezatfar/DataScience-Pipeline-ML-Salary-Prediction
```

## Contact

<a href="https://www.linkedin.com/in/imanezatfar"><img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn"/></a>
<a href="mailto:iman.ezatfar89@gmail.com"><img src="https://img.icons8.com/color/48/000000/gmail.png" alt="Gmail"/></a>
