# FUTURE_DS_03

📊 **Task 3 – College Event Feedback Analysis**

## 🚀 Project Overview

* This repository contains the completed work for **Task 3** of the **Future Interns – Data Science & Analytics Internship**.
* The objective is to analyze **student satisfaction survey data** to uncover trends and recommend data-driven improvements.
* The analysis is based on **Likert-scale (1–5)** responses and includes data cleaning, exploratory analysis, and visualizations.

> **Note:** Although the task title refers to *College Event Feedback*, the provided dataset contains structured **student satisfaction survey responses**. Hence, insights are derived from quantitative survey metrics rather than open-ended comments.

---

## 📁 Dataset Used

* **Source:** Institutional Student Satisfaction Survey (CSV)
* **Scale:** 5-point Likert scale
* **Coverage:** Aggregated responses across multiple courses and departments

### Key Fields

* `SN` – Question Serial Number
* `Questions` – Survey parameters
* `Weightage 1–5` – Response counts for each rating
* `Total Feedback Given`
* `Total Configured`
* `Average / Percentage`
* `Course Name`
* `Basic Course`

---

## 🛠️ Data Cleaning & Preparation (pandas)

### ✔ Cleaning & Preprocessing Steps

* Removed unnecessary/unnamed columns
* Standardized column names (trimmed extra spaces)
* Extracted numeric averages from mixed text fields
* Converted extracted values to numeric data types
* Checked for missing values and ensured data consistency

### 🔎 Data Quality Note

> The dataset contains **aggregated responses**; individual student-level records and open-ended feedback were not available.

---

## 📊 Analysis & Insights

### 📌 Satisfaction Interpretation

* **High Satisfaction:** Scores **4–5**
* **Moderate Satisfaction:** Score **3**
* **Low Satisfaction:** Scores **1–2**

### 📈 Key Insights

* Most courses show **above-average satisfaction**
* Teaching and mentoring parameters tend to score **comparatively lower**
* Satisfaction varies across programs, indicating a need for **standardization**
* **Student-centric and experiential learning** parameters score higher

---

## ☁️ Word Cloud Analysis

* A word cloud was generated using **low-scoring survey questions**
* Highlights recurring themes that require improvement
* Helps compensate for the absence of open-ended feedback

---

## 📊 Visualizations Included

* Correlation heatmap of survey metrics
* Average feedback scores (bar chart)
* Satisfaction score distribution (pie chart)
* Course-wise average satisfaction comparison
* Word cloud of low-satisfaction parameters

---

## 📌 Recommendations

* Strengthen mentoring and feedback mechanisms
* Improve consistency in teaching quality across departments
* Expand experiential and student-centric learning practices
* Prioritize improvement areas with consistently low scores

---

## ⚠️ Limitations

* Aggregated data; no individual-level analysis
* No open-ended feedback for NLP-based sentiment analysis
* Possible response bias due to self-reported scores

---

## 🛠 Tools & Technologies

**Google Colab | Python | pandas | matplotlib | seaborn | WordCloud | CSV**

---

## 📂 Repository Structure

```
FUTURE_DS_03/
│
├── dataset/
│   └── dataset.zip
│
├── notebook/
│   └── DS_3.ipynb
│
├── visuals/
│   └── DS_3.mp4
│
├── README.md
```

---

## 📦 How to Run the Project

1. Open **Google Colab**
2. Upload `DS_3.ipynb`
3. Upload `dataset.zip` from the `dataset/` folder
4. Extract the ZIP to access the CSV file
5. Run all cells sequentially

> **Note:** Ensure the extracted CSV is in the same directory as the notebook or update the file path accordingly.

---

## 💡 Key Learning Outcomes

* Data cleaning and preprocessing with pandas
* Likert-scale survey analysis
* Visualization for decision-making
* Insight generation from structured survey data
* Translating analysis into actionable recommendations
