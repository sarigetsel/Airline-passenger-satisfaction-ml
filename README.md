# Airline Passenger Satisfaction Analysis

An end-to-end Data Analysis and Machine Learning project designed to explore passenger feedback, identify key satisfaction drivers, and predict whether a passenger is satisfied or dissatisfied.

---

## 📸 Key Data Visualizations

<p align="center">
  <img width="1075" height="595" alt="Screenshot 2026-11-08 154509" src="https://github.com/user-attachments/assets/4bafcc0d-8f33-4a77-a434-11fbd44f19f5" />
  <img width="700" height="815" alt="Screenshot 2026-11-08 154535" src="https://github.com/user-attachments/assets/aed3f59f-9f71-4443-994b-aabd31a2599b" />
</p>

---

## 📊 Project Overview & Pipeline

The project follows a structured data science pipeline:
1. **Data Loading & Initial Exploration:** Inspected dataset dimensions ($103,904$ rows, $25$ columns), data types, and structural integrity using Pandas.
2. **Exploratory Data Analysis (EDA):** Separated numerical and categorical features, generated statistical summaries (mean, min, max, std), and detected missing values (e.g., in arrival delays).
3. **Data Visualization:** Plotted histograms, bar charts, and correlation heatmaps with Matplotlib and Seaborn to uncover patterns.
4. **Data Preprocessing & Cleaning:** Handled missing values, encoded categorical features, and prepared data for modeling.
5. **Model Building & Training:** Trained machine learning classification models using Scikit-learn.
6. **Model Evaluation & Metrics:** Evaluated performance metrics to assess accuracy and reliability.
7. **Feature Importance:** Analyzed which factors most significantly impact passenger satisfaction.

---

## 🛠️ Tech Stack

* **Language:** Python 3
* **Libraries & Frameworks:** 
  * `Pandas` & `NumPy` (Data manipulation & cleaning)
  * `Scikit-learn` (Machine learning models & preprocessing)
  * `Matplotlib` & `Seaborn` (Data visualization)
* **Environment:** Jupyter Notebook

---

## 🚀 Project Steps & Quick Run

To run the analysis locally:
1. Clone the repository.
2. Ensure you have Python and Jupyter installed along with dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
