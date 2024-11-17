
Project Overview:
This project is divided into two tasks:
1. Predicting Bank Marketing Campaign Success (Binary Classification)
2. Predicting NBA Player Performance (Regression Analysis)

------------------------------------------------------------
Task Summaries:

Task 1: Bank Marketing Campaign Success
----------------------------------------
- **Objective**: Predict if a customer will subscribe to a term deposit.
- **Steps**:
  1. Preprocess the data: Handle missing values and encode categorical features.
  2. Select key features using correlation and mutual information.
  3. Train models: Logistic Regression, Decision Tree, and Random Forest.
  4. Evaluate models with accuracy, precision, recall, and F1-score.
- **Output**: Identify the best-performing model and key influencing features.

Task 2: NBA Player Performance
------------------------------
- **Objective**: Predict a player's game score or performance metric.
- **Steps**:
  1. Perform EDA: Visualize data distributions and feature correlations.
  2. Engineer new features: Points per game, assists per game, etc.
  3. Train models: Linear Regression and Ridge Regression.
  4. Evaluate models using R-squared and Mean Absolute Error (MAE).
- **Output**: Key insights about factors affecting player performance.

------------------------------------------------------------
How to Run the Code:

1. **Install Required Libraries**:
   - Install Python (version 3.8 or above).
   - Run the following commands to install dependencies:
     ```
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```

2. **Download Datasets**:
   - Place the datasets:
     - `bank-full.csv` for Task 1.
     - `nba_players.csv` for Task 2.
   - Save them in the same directory as the project files.

3. **Run Jupyter Notebooks**:
   - Open `task1_bank_marketing.ipynb` and `task2_nba_performance.ipynb` in Jupyter Notebook or your preferred IDE.
   - Execute all cells in sequence.

4. **Review Results**:
   - Visualizations and results are generated in the notebooks.
   - Summary reports are included in the `reports/` folder.

------------------------------------------------------------
Folder Structure:

- `task1_bank_marketing.ipynb`: Notebook for Task 1.
- `task2_nba_performance.ipynb`: Notebook for Task 2.
- `datasets/`: Folder containing the required datasets.
- `reports/`: Summarized markdown reports for each task.
- `README.txt`: This file with instructions and project details.


