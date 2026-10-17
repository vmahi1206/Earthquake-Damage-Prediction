# Earthquake Damage Prediction

## Project Overview

This project uses machine learning to predict building damage grades based on earthquake-related building data. It explores the dataset, prepares features, trains classification models, and evaluates their performance.

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Random Forest hyperparameter tuning is performed using GridSearchCV.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow

1. Load the training datasets.
2. Explore and understand the data.
3. Clean and preprocess the features.
4. Train machine learning classification models.
5. Tune Random Forest hyperparameters.
6. Evaluate model performance using classification metrics and a confusion matrix.
7. Analyze feature importance.

## Project Files

- `Earthquake_Damage_Prediction.ipynb` — notebook containing the machine learning workflow.
- `train_values.csv` — training features, if this is the actual dataset filename.
- `train_labels.csv` — training labels, if this is the actual dataset filename.
- `requirements.txt` — Python dependencies.
- `.gitignore` — files excluded from Git tracking.

## How to Run

1. Clone this repository.
2. Install the dependencies using `pip install -r requirements.txt`.
3. Ensure the datasets are available at the paths expected by the notebook.
4. Open the notebook in Jupyter and run the cells in order.

## Future Improvements

- Save and reuse the trained model and preprocessing artifacts.
- Build a web application for interactive predictions.
- Deploy the application for online access.

## Author

V Mahesh

GitHub: https://github.com/vmahi1206
