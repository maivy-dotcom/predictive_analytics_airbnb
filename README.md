# Predicting Airbnb Perfect Ratings

## Overview

This project was completed as part of the Data Mining course at the University of Maryland, where we participated in a predictive modeling competition hosted on a real-world Airbnb dataset. The objective was to develop a binary classification model to predict whether a given Airbnb listing would receive a perfect 5-star rating (`perfect_rating_score = YES/NO`).

We competed in Contest 1, where success was defined by achieving the **highest True Positive Rate (TPR)** under a constraint of **no more than 10% False Positive Rate (FPR)**.

---

## Business Understanding

Airbnb hosts rely heavily on perfect guest ratings to improve visibility, increase booking rates, and justify premium pricing. This project aims to provide hosts, property managers, and the Airbnb platform itself with a predictive model that identifies listings likely to receive perfect reviews — enabling:
- Personalized insights for hosts to improve listings
- Performance tracking for property managers
- Quality assurance tools for Airbnb

---

## Project Highlights

- **Model Used**: XGBoost Classifier
- **Key Features**:
  - Host response time and acceptance rate
  - Review sentiment and topic modeling
  - External crime data by state
  - Engineered variables such as price-per-person, host tenure, and booking frequency
- **Evaluation**: Maximized TPR while maintaining FPR ≤ 10%

---

## Project Structure

```plaintext
.
├── data/
│   ├── airbnb_train_X_2025.csv
│   ├── airbnb_train_y_2025.csv
│   └── airbnb_test_X_2025.csv
│
├── notebooks/
│   └── Final_Submission_EDA_intialModels.ipynb
│   └── Final_Submission.ipynb
│
├── report/
│   └── final_project_report.pdf
│
├── output/
│   └── Submitted_labels.csv
│
└── README.md
```

---

## Key Learnings

- **Feature Engineering**: Manually curated features after understanding their business relevance gave better results than automated selection.
- **Data Cleaning**: Early attention to cleaning and organizing the dataset significantly streamlined the modeling phase.
- **Evaluation**: Learned to balance sensitivity (TPR) and specificity (FPR) in real business contexts.

---

## 🧠 Reflections

- With more time, we would have experimented further with neural networks and incorporated richer external data sources.
- We improved significantly in working with missing values, model evaluation metrics, and iterative tuning strategies.

---

## 📁 Deliverables

- Final model code and predictions
- Feature engineering scripts
- Comprehensive report outlining methodology and findings

---

## 📁 Data Access
The datasets used in this project are hosted externally due to size constraints on GitHub.

You can access all data files (training features, training labels, test set) at the following Google Drive folder:

🔗 Airbnb Project Dataset – Google Drive : https://drive.google.com/drive/u/2/folders/1w3VUcwrBnck-drelujJ_vcaAnFvPdW0j

---

## 🔗 Contact

For questions or collaborations, feel free to reach out via LinkedIn or email.
