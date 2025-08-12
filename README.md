# Real or Fake Job Posting Prediction – Data Cleaning & Missing Value Analysis

## Project Overview
This project is part of the IIT Jammu initiative to predict whether an online job posting is **genuine** or **fraudulent**.  
Currently, we have completed the **data cleaning and missing value analysis** phase, which ensures that our dataset is ready for future model training.

---

## 👥 Team Members

| Name           | Email                       | Role |
|----------------|-----------------------------|------|
| Prachi Gautam  | prachi2011gautam@gmail.com  | Data Loading & Missing Value Analysis |
| Harsh Sharma   | harshjnv2@gmail.com         | Data Cleaning Support |
| Akash Lone     | akashmohdlone@gmail.com     | Documentation & Visualization |

---

## Dataset
- **Source**: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
- **Format**: CSV
- **Description**: Contains job posting details such as:
  - `title`
  - `company_profile`
  - `location`
  - `description`
  - `requirements`
  - `salary_range`
  - `fraudulent` (target label)

---

## Approach & Methodology (Current Stage)
1. **Data Loading**
   - Imported dataset using Pandas
   - Inspected dataset shape & column types

2. **Missing Value Analysis**
   - Counted missing values using `.isnull().sum()`
   - Visualized missing data patterns using Seaborn heatmap
   - Dropped columns with more than **50% missing data**
   - Filtered rows containing missing values for inspection
   - Filled missing values:
     - Numerical columns → Median
     - Categorical columns → Mode

3. **Initial Cleaning**
   - Removed duplicate rows
   - Saved incomplete rows separately for reference

---

## Results (So Far)
- Columns with excessive missing values removed
- Dataset size reduced while retaining important features
- Cleaned dataset ready for **feature engineering**

---

## Challenges Faced
- Handling large amounts of missing data
- Deciding between dropping vs imputing columns
- Managing differences in numeric & categorical imputation

---

## Learnings
- Visualizing missing data using Pandas & Seaborn
- Decision-making for data cleaning
- Writing clean and efficient Pandas code

---

## Future Scope
- Feature engineering (text processing, encoding)
- Train ML models for classification
- Model evaluation (accuracy, precision, recall, F1-score)
- Deployment as a web application

---

## References
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- Dataset Source: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

---

## GitHub/Colab Link
https://github.com/Prachichi7/IITJammu
