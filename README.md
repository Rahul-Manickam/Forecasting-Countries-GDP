## Predicting GDP Per Capita using Country-Level Indicators

This project explores the factors influencing a country's GDP per capita and develops predictive models using machine learning. The dataset "Countries of the World" is analyzed to uncover insights and build models capable of estimating GDP based on various socio-economic indicators.

![](/1.png)

### Key Findings

* **Strongest Predictors:**  The number of phones per 1000 people, literacy rate, and infant mortality rate are identified as the most significant predictors of GDP per capita.
* **Regional Disparities:** Analysis reveals substantial differences in GDP per capita across regions, with North America and Western Europe leading and Sub-Saharan Africa trailing.
* **Model Performance:** Random Forest regression achieves the best predictive accuracy (R-squared score of 0.8839), followed closely by Gradient Boosting.

### Getting Started

1. **Dataset:** Download the "Countries of the World" dataset from Kaggle: [https://www.kaggle.com/fernandol/countries-of-the-world](https://www.kaggle.com/fernandol/countries-of-the-world)
2. **Dependencies:** Ensure you have the required libraries (NumPy, pandas, seaborn, matplotlib, scikit-learn) installed.
3. **Run the Notebook:** Execute the Jupyter Notebook to reproduce the analysis, data cleaning, and model training steps.

### Methodology

1. **Exploratory Data Analysis (EDA):**  Examines relationships between features and GDP, investigates regional patterns, and visualizes distributions.
2. **Data Cleaning:** Handles missing values and converts data types for consistency.
3. **Feature Engineering:** Encodes categorical variables and performs feature selection.
4. **Model Training and Evaluation:** Builds and compares multiple regression models (Linear Regression, SVM, Random Forest, Gradient Boosting) using various combinations of features and scaling techniques.
5. **Model Optimization:**  Fine-tunes hyperparameters of the best-performing models.

   ![](/2.png)


