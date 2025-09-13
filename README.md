🚦 Uber Data Analysis

📌 Project Overview

This project focuses on analyzing Uber traffic data and building machine learning models to predict traffic congestion levels based on factors like:

Date & Time

Junctions (road intersections)

Weather conditions (Temperature, Humidity, Rainfall)

Holiday/Events

The goal is to help Uber optimize driver allocation, reduce passenger wait times, and improve overall traffic management.

🔍 Exploratory Data Analysis (EDA)

Checked for missing values and data quality.

Analyzed traffic patterns across different junctions, weekdays, and time of day.

Visualized how weather & holidays impact traffic volume.

Created a new feature traffic_level (Low / Medium / High / Very High) for classification.

🤖 Models Implemented

Logistic Regression

Random Forest Classifier

XGBoost (if available)

Evaluation Metrics:

Accuracy

F1-score (Macro)

Confusion Matrix

📈 Results & Insights

Traffic peaks during rush hours (morning & evening).

Holidays/events significantly reduce traffic volumes.

Weather (rainfall & humidity) has a moderate effect on congestion.

Random Forest outperformed Logistic Regression with better overall accuracy & balance across traffic levels.

✅ Conclusion

The project demonstrates how EDA + ML can provide actionable insights for Uber:

Better driver allocation during high-traffic times.

Proactive planning during holidays & bad weather.

Improved customer satisfaction by reducing wait times.

🛠 Tech Stack

Python (Pandas, NumPy, Scikit-learn, XGBoost)

Seaborn & Matplotlib (Visualizations)

Jupyter Notebook
