# IBM Applied Data Science Capstone – SpaceX Launch Prediction

This repository contains the final capstone project for the IBM Data Science Professional Certificate on Coursera. The objective is to predict the successful landing of SpaceX Falcon 9 first stages using machine learning techniques.

---

Project Overview

The project follows a structured data science workflow:

1. Data Collection
   - Data from the SpaceX API.
   - Web scraping from Wikipedia for Falcon 9 launch records.

2. Data Wrangling
   - Cleaning and formatting the data for analysis.

3. Exploratory Data Analysis (EDA)
   - Identify patterns and correlations in launch data.

4. Data Visualization
   - Interactive dashboards built with Dash.
   - Charts and maps using Matplotlib, Seaborn, and Folium.

5. Machine Learning
   - Models applied: Logistic Regression, Support Vector Machine (SVM), Decision Tree, K-Nearest Neighbors (KNN).
   - Goal: Predict whether a Falcon 9 first stage landing will be successful.

---


Installation

To run the notebooks and dashboards locally:

1. Clone the repository:
   git clone https://github.com/BookerSK/IBM-Applied-Data-Science-Capstone.git

2. Create a virtual environment and activate it:
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install required packages:
   pip install -r requirements.txt

   > If requirements.txt does not exist, install packages manually:
   pip install pandas numpy matplotlib seaborn plotly dash scikit-learn statsmodels requests

---

Key Findings

- Exploratory Data Analysis revealed patterns in SpaceX launch outcomes.
- Logistic Regression, SVM, Decision Tree, and KNN models were tested to predict first-stage landing success.
- The dashboard allows for interactive exploration of launch outcomes by site and payload.

---

References

- IBM Data Science Professional Certificate – Coursera
- SpaceX API: https://github.com/r-spacex/SpaceX-API
- Wikipedia – Falcon 9 Launch Records: https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

---

Notes

- This project is for educational purposes only.
- Some datasets may change over time, which could affect reproducibility.
- Proper citation of data sources is recommended if used for reporting.
