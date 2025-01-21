# Task-4---Sales-Prediction

## Project Overview

This project focuses on predicting **sales** based on advertising budgets for **TV**, **Radio**, and **Newspaper** campaigns. Using a **Linear Regression model**, the project demonstrates end-to-end steps including data preprocessing, model training, evaluation, and predicting sales for new data.

---

## Project Description

The project workflow includes:
1. **Data Exploration and Preprocessing**:
   - Analyzing the dataset for missing values, duplicates, and basic statistics.
   - Visualizing relationships between features using heatmaps and line plots.
2. **Feature Scaling**:
   - Standardized features using `StandardScaler` from Scikit-learn.
3. **Model Training**:
   - Built a **Linear Regression model** to predict sales.
4. **Model Evaluation**:
   - Evaluated using metrics like **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
5. **Prediction**:
   - Predicted sales for new input data.

---

## Dataset

- **Columns**:
  - `TV`: Advertising budget for TV.
  - `Radio`: Advertising budget for Radio.
  - `Newspaper`: Advertising budget for Newspaper.
  - `Sales`: Target variable (sales in units).
- The dataset file should be named `advertising (1).csv` and placed in the root directory.

---

## Dependencies

Install the required libraries before running the code:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/advertising-sales-prediction.git
   cd advertising-sales-prediction
   ```

2. Place the `advertising (1).csv` file in the root directory.

3. Run the script:
   ```bash
   python sales_prediction.py
   ```

4. The script will output:
   - Evaluation metrics: **R² Score**, **MAE**, **RMSE**.
   - Predicted sales for the sample input.

---

## Output

### Model Evaluation:
- **R² Score**: Measure of how well the model fits the data.
- **MAE**: Average error between predicted and actual sales.
- **RMSE**: Root mean squared error for error magnitudes.

### Prediction:
The script provides sales predictions for new input values.
