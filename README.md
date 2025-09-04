 COVID-19 Cases Rate Prediction

This project is a predictive modeling and data analysis exercise focused on forecasting COVID-19 case rates using **Python** and a **Multiple Linear Regression** model. It showcases a complete data science workflow, from data preprocessing to model evaluation and visualization.

---

 Project Objective

The primary objectives of this project were to:
* Conduct data analysis and predictive modeling to forecast the rate of COVID-19 cases over time.
* Perform essential data preprocessing steps to prepare the dataset for machine learning.
* Build a predictive model using **Multiple Linear Regression**.
* Visualize data trends and the model's predictions using **Matplotlib**.

---

Methodology and Key Findings

 Data Preprocessing
 I used the **Pandas** library to load and handle the dataset.
 I defined the independent variables (`x`) as **cases**, **increasing rate**, and **decreasing rate**, while the dependent variable (`y`) was **time**.              The data was prepared for modeling by applying a **train-test split**, a crucial step to evaluate the model's performance on unseen data.

 Predictive Model
 I used the **Multiple Linear Regression** algorithm from `scikit-learn` to build the predictive model. This model is suitable for forecasting a continuous       variable (time) based on multiple independent input variables.

 Results and Evaluation
 The model achieved a prediction efficiency of **86%**, as shown by the `reg.score()` method. This indicates a strong capability to forecast future trends.
 The relationship between the independent variables and time was successfully visualized using a **Matplotlib 2D graph**, which clearly represents the data and the model's predictions.

---

 Technologies Used

 **Python**
 **Libraries:**
    * `pandas`
    * `numpy`
    * `scikit-learn`
    * `matplotlib`

