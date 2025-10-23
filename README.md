# 📉 Telco Customer Churn Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on a telecom customer dataset to identify the main factors and patterns contributing to customer attrition (churn). The goal is to provide data-driven insights to help the business develop effective retention strategies.

## 💡 Key Findings

Based on the analysis performed in `EDA_CHURN_ANALYSIS.ipynb`, the most significant drivers of churn are:

1.  **Contract Type:** Customers on **Month-to-Month** contracts have a significantly higher churn rate compared to those on 1-Year or 2-Year contracts.
2.  **Tenure:** Customers with **low tenure** (new users) are the most likely to churn.
3.  **Payment Method:** The **Electronic Check** payment method shows a strong correlation with churn.

---

## 📁 Project Structure

This repository is organized to ensure reproducibility and clarity:

| Folder/File | Content |
| :--- | :--- |
| `EDA_CHURN_ANALYSIS.ipynb` | The main Jupyter Notebook containing all cleaning, analysis, and conclusions. |
| `data/` | Contains the source dataset (`telecom_churn.csv`) required to run the analysis. |
| `bar & pie chart/` | Visualizations for the distribution of categorical variables and overall churn rate. |
| `histogram/` | Visualizations showing the distribution and skewness of numerical features. |
| `heatmap/` | **Multivariate** correlation analysis between numerical features. |
| `... (other folders) ...` | Other bivariate and outlier analysis plots. |
| `requirements.txt` | Lists all necessary Python dependencies. |

---

## 🛠️ Requirements & Installation

To replicate this environment and run the notebook locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/telecomeChurn-EDA-Analysis.git](https://github.com/YourUsername/telecomeChurn-EDA-Analysis.git)
    cd telecomeChurn-EDA-Analysis
    ```
2.  **Install dependencies:**
    *(If you haven't uploaded `requirements.txt` yet, manually install the common libraries)*
    ```bash
    # Assuming you use these standard libraries for EDA:
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
3.  **Run the notebook:**
    ```bash
    jupyter notebook EDA_CHURN_ANALYSIS.ipynb
    ```

---

## 📈 Analysis Highlights

*(Optional: If you want to highlight a specific chart, replace the text below with the path to your chart image)*

The **correlation heatmap** was crucial for understanding feature relationships:

![Correlation Heatmap](heatmap/correlation_matrix.png)
