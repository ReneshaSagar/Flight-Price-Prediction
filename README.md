# ✈️ Flight Price Category Prediction

## 🚀 Project Overview

This project implements a machine learning model to predict flight price categories (`Cheap` or `Expensive`) based on various flight attributes. The goal is to provide insights into flight pricing and assist users in making informed booking decisions.

The model is built using Python and leverages key data science libraries to preprocess data, train a classifier, and evaluate its performance.

## 🛠️ Technical Skills Demonstrated

* **Python:** The core programming language used for the project.
* **Machine Learning:** Applied a **Random Forest Classifier** for supervised learning.
* **Data Manipulation:** Used **Pandas** for data cleaning, transformation, and binning continuous data into categories.
* **Data Visualization:** Created informative plots with **Matplotlib** and **Seaborn** to visualize model performance.
* **Model Evaluation:** Calculated and interpreted a **Confusion Matrix** and **Classification Report** to assess the model's accuracy, precision, and recall.

## 📈 Key Results

The model achieved high accuracy in classifying flight prices. Here are the key performance metrics:

| Metric | Cheap | Expensive |
| :--- | :--- | :--- |
| **Precision** | 0.98 | 0.97 |
| **Recall** | 0.98 | 0.97 |
| **F1-Score** | 0.98 | 0.97 |
| **Accuracy** | 0.98 | - |

### Confusion Matrix

The confusion matrix visually confirms the model's strong performance, with a high number of correct predictions (34036 and 24530) and a low number of misclassifications (733 and 732).



### Actual vs. Predicted Plot

A sample plot comparing the actual and predicted price categories shows that the model's predictions closely align with the true values.



## 📁 How to Run the Project

1.  **Download the dataset:**
    Download the `FlightBooking.csv` file from the following Kaggle link and place it inside the `data/` folder.
    -   **Dataset Link:** https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

2.  **Setup the environment:**
    Install the required libraries using pip:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    Launch the Jupyter Notebook and run all the cells to see the complete analysis, from data loading to model evaluation and visualization.
    ```bash
    jupyter notebook Flight_Price_Prediction.ipynb
    ```
