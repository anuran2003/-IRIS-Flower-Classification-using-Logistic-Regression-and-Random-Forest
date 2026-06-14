# -IRIS-Flower-Classification-using-Logistic-Regression-and-Random-Forest
"Iris flower multi-class classification using Logistic Regression and Random Forest. Summer Internship Project for IDEAS Foundation, ISI Kolkata (May–June 2026)."
## 📌 Project Overview
This project builds an automated end-to-end machine learning pipeline to classify plant species using continuous morphometric biological measurements. Utilizing the classic Iris dataset, the system extracts predictive patterns from sepal and petal dimensions to perform multi-class predictive modeling. 

Two distinct architectural approaches were implemented and compared:
1. **Logistic Regression** (A parametric linear classifier optimized with the LBFGS solver)
2. **Random Forest Classifier** (A non-parametric tree-based ensemble framework using bagging mechanics)

Both frameworks successfully achieved an ideal baseline performance of **100% classification accuracy** on unseen test data.

---

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python 3.x
* **Data Manipulation:** Pandas & NumPy
* **Machine Learning Engine:** Scikit-Learn (Sklearn)
* **Development Environment:** Google Colab / Jupyter Notebook

---

## 📂 Repository Structure
* `Iris_Flower_Classification.ipynb` -> The fully commented and executed Google Colab assignment notebook containing the source code, training logs, and valuation metrics.
* `README.md` -> Project documentation and setup overview.

---

## 📈 Key Methodology & Results
### 1. Workflow Pipeline
[Raw Ingestion] ➔ [Pandas DataFrame Restructuring] ➔ [80/20 Deterministic Split] ➔ [Model Fitting] ➔ [Evaluation Metrics Extraction]
### 2. Experimental Performance Breakdown
* **Data Split Configuration:** 120 samples utilized for training optimization; 30 samples held back for validation.
* **Logistic Regression Test Accuracy:** 1.00 (100%)
* **Random Forest Test Accuracy:** 1.00 (100%)

Both models converged cleanly without showing structural signs of overfitting, demonstrating that petal dimensions provide robust predictive margins for taxonomic segmentation.
