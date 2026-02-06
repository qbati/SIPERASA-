# SIPERASA (Prediction System Student Academy)

**SIPERASA** is a web-based machine learning application designed to analyze and predict student academic performance. Built with **Python** and **Streamlit**, this tool allows educators and researchers to compare the efficacy of **Decision Tree** and **Random Forest** algorithms in real-time.

## Project Overview

* **Objective:** To develop a comparative analysis tool for educational data mining, specifically focusing on predicting student success metrics.
* **Key Insight:** The project demonstrated that ensemble methods (Random Forest) offer superior predictive stability over single decision trees when applied to small-to-medium-sized educational datasets.

## Key Features

* **Real-Time Model Selection:** Dynamically switch between Decision Tree and Random Forest classifiers to observe differences in prediction logic.
* **Hyperparameter Tuning:** Interactive controls to adjust model parameters (e.g., tree depth, n_estimators) and instantly visualize the impact on performance.
* **Performance Comparison:** Side-by-side analytics of model accuracy, precision, and recall.
* **Interactive Visualization:** Data visualization tools to explore the underlying dataset and feature importance.

## Model Performance

The models were trained and evaluated on a Kaggle dataset consisting of **395 student records**.

| Model | Accuracy |
| :--- | :--- |
| **Random Forest** | **98.7%** |
| Decision Tree | 97.4% |

*The Random Forest algorithm outperformed the Decision Tree classifier, demonstrating higher accuracy and robustness in predicting student outcomes.*

## Tech Stack

* **Language:** Python
* **Framework:** Streamlit
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy

## Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/qbati/SIPERASA-.git](https://github.com/qbati/SIPERASA-.git)
    cd SIPERASA-
    ```

2.  **Install dependencies:**
    ```bash
    install requirements (In case)
    ```

3.  **Run the application:**
    ```bash
    streamlit run app.py
    ```

## Support

If you find this project helpful, please support it by leaving a star.

[![GitHub stars](https://img.shields.io/github/stars/qbati/SIPERASA-?style=social)](https://github.com/qbati/SIPERASA-/stargazers)
