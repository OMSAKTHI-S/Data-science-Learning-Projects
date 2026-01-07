# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview
SpaceX advertises Falcon 9 rocket launches at a cost of **$62 million**, significantly lower than other providers that charge **$165 million or more**. This cost efficiency is largely due to SpaceX’s ability to **reuse the first stage** of the rocket.

If we can **predict whether the first stage will successfully land**, we can estimate the **actual launch cost**. This insight is valuable for competing aerospace companies when bidding against SpaceX for commercial launches.

In this project, we collect, clean, explore, and model SpaceX launch data to **predict first-stage landing success** using machine learning.

---

## Objectives
- Collect SpaceX launch data using **API requests** and **web scraping**
- Perform **data cleaning and preprocessing**
- Conduct **Exploratory Data Analysis (EDA)** using visualization tools
- Build a **machine learning pipeline**
- Predict whether the Falcon 9 **first stage will land successfully**

---

## Machine Learning Problem
**Type:** Binary Classification  
**Target Variable:**  
- `1` → Successful landing  
- `0` → Unsuccessful landing  

---

## Tools & Technologies Used
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Plotly Dash**
- **Folium**
- **Scikit-learn**
- **SQL**
- **BeautifulSoup**
- **Jupyter Notebook**

---

## Models Implemented
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Model performance was evaluated using:
- Accuracy
- Confusion Matrix
- Cross-validation

---

## Key Insights
- Launch success increases with higher payload mass (up to a limit)
- Certain launch sites show higher landing success rates
- Reused boosters significantly improve landing probability

---

## Conclusion
This project demonstrates how **data science and machine learning** can be applied to real-world aerospace problems. By predicting first-stage landing success, we gain insights into **cost efficiency** and **competitive bidding strategies** in the commercial space industry.

---

## Acknowledgements
- SpaceX public API
- IBM Data Science Professional Certificate
- Coursera Labs

---

## Author
**Omsakthi**  
