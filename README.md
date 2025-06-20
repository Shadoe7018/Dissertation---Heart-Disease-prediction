Here's a tailored `README.md`-style content for your heart disease prediction project using Logistic Regression, Random Forest, and SVM:

---

# Heart Disease Prediction Using Machine Learning Models

This project presents a comparative analysis of three supervised machine learning algorithms—**Logistic Regression**, **Random Forest**, and **Support Vector Machine (SVM)**—to predict the presence of heart disease based on physiological features collected from smartwatch-like sources.

## Models Used

* **Logistic Regression**: A simple and interpretable linear classifier.
* **Random Forest**: An ensemble model known for robustness and feature importance analysis.
* **Support Vector Machine (SVM)**: A powerful classifier effective in high-dimensional spaces.

## Dataset

* **Heart Disease UCI Dataset** (sourced from IEEE DataPort).
* 303 patient records with 14 features + 1 target variable.
* Features include:

  * Demographic: `age`, `sex`
  * Clinical: `cp`, `chol`, `thalach`, `restecg`, `exang`, `oldpeak`, etc.

## Preprocessing Steps

* Handled missing values using **mean imputation**.
* Applied **one-hot encoding** to categorical features.
* Standardized numerical features using **StandardScaler**.
* Split data into **80% training** and **20% testing** sets.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* ROC Curve

## Key Findings

* **Random Forest** outperformed others with highest accuracy (86.9%) and F1-score (0.87).
* **SVM** showed excellent **recall**, especially for heart disease detection (88%), ideal for clinical settings.
* **Logistic Regression** provided simplicity and interpretability, with balanced metrics and fast execution.

## Dependencies

* Python 3.9+
* scikit-learn
* pandas
* matplotlib
* seaborn
* Jupyter Notebook (or Google Colab)


**Author:** Sakthivel Mohankumar
**University of Hertfordshire – MSc Data Science**
**Supervisor:** Ashley Spindler

