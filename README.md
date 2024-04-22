README.md

# Big Mart Sales Prediction

## Overview
This project focuses on predicting the sales of various products in Big Mart outlets. It involves analyzing historical sales data, exploring key features influencing sales, and building machine learning models for accurate sales prediction. The objective is to assist Big Mart in optimizing inventory management and maximizing sales revenue.

## Dataset
The dataset consists of two files: `Train.csv` containing the training data and `Test.csv` for testing. It includes various features such as Item ID, Item Weight, Item Fat Content, Item Type, Outlet ID, Outlet Establishment Year, Outlet Size, Outlet Location Type, and Item Outlet Sales (target variable).

## File Description
- `Train.csv`: Contains the training dataset.
- `Test.csv`: Contains the testing dataset.
- `Big_Mart_Sales_Prediction.ipynb`: Jupyter Notebook containing data preprocessing, exploratory data analysis, model building, and evaluation.
- `models/`: Directory containing saved trained models.
- `random_forest_grid.sav`: Saved Random Forest model after hyperparameter tuning.
- `sc.sav`: Saved Standard Scaler object for preprocessing.
- `requirements.txt`: File listing the Python packages required to run the notebook.

## Data Preprocessing
- Handled missing values in Item Weight and Outlet Size using mean and mode imputation respectively.
- Performed label encoding for categorical variables.
- Split the data into training and testing sets.

## Exploratory Data Analysis (EDA)
- Analyzed correlations between features using heatmap visualization.
- Utilized Pandas Profiling and Klib libraries for in-depth data exploration.
- Visualized distributions and missing values to gain insights into the data.

## Model Building
- Trained machine learning models including Linear Regression, Random Forest Regressor, and XGBoost Regressor.
- Conducted hyperparameter tuning using GridSearchCV to optimize model performance.
- Evaluated models using metrics like R-squared, Mean Absolute Error, and Root Mean Squared Error.

## Usage
1. Install the required dependencies listed in `requirements.txt` using `pip install -r requirements.txt`.
2. Run the Jupyter Notebook `Big_Mart_Sales_Prediction.ipynb` to execute the code.
3. Ensure the dataset files `Train.csv` and `Test.csv` are in the appropriate directory.

## Results
- Achieved significant improvement in model performance after hyperparameter tuning.
- Random Forest Regressor yielded the best performance with an R-squared score of over 0.60.

## Future Work
- Explore additional feature engineering techniques to enhance model performance.
- Experiment with advanced machine learning algorithms such as Gradient Boosting Machines and Neural Networks.
- Deploy the best-performing model into production for real-time sales predictions.

## Contributors
- Mayur Kyatham
- Utsav Kuntalwad
- Prerna Shakwar
- Srushti Sawant

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
