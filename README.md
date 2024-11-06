# Kaggle Competition: Playground Series S4E10 - Data Science Portfolio

This repository serves as a portfolio to showcase my data science and machine learning skills. The focus is on solving the Kaggle Playground Series S4E10 competition, where I apply a range of data engineering, exploration, and machine learning techniques.

## Overview

This repository is designed to demonstrate my abilities in data engineering, data analysis, and machine learning model training with hyperparameter optimization. The notebook included here outlines my step-by-step approach, from data exploration to model evaluation.

## Viewing the Notebook with nbviewer

Since GitHub's Jupyter Notebook viewer can sometimes struggle with rendering complex notebooks, this repository includes a link to nbviewer, which offers more reliable and consistent rendering:

### View the Notebook You can view the notebook using nbviewer here.

- https://nbviewer.org/github/Alexej9671/kaggle_loan_approval_prediction/blob/master/train_models.ipynb?flush_cache=true

Using nbviewer ensures that all visualizations, code cells, and outputs are displayed correctly, offering a smoother viewing experience for anyone exploring the notebook online.

### Competition Link

https://www.kaggle.com/competitions/playground-series-s4e10

## Project Structure

- `train_models.ipynb`: Is the main Jupyter notebook where all processes are demonstrated.
- `README.md`: Overview and documentation of the project.
- `requirements.txt`: Lists the required libraries to run the notebook.

## Methodologies and Techniques

### Data Engineering and Exploration 

I employ a variety of data engineering and exploration techniques, primarily using Pandas, Matplotlib, and Seaborn. These techniques include:

- Data Preprocessing: Initial inspection and cleaning of the dataset.
- Plotting:
- Violin Plots: To visualize the distribution of variables.
- Box-and-Whisker Diagrams: For detecting and analyzing outliers.
- Outlier Removal: Identifying and handling outliers to improve model performance.
- One-Hot-Encoding and Manual Encoding: Encoding categorical variables as needed.
- Correlation Analysis: Examining relationships between features.
- Pivot Tables: Summarizing data to extract insights.
- Feature Engineering: Creating new features to enhance model performance.
- Normalization: Scaling features to standardize data for better model training.

### Model Training and Tuning 

After data processing, I move on to model training using various machine learning algorithms. Hyperparameter tuning is performed with Optuna, a powerful and flexible optimization tool.

## Results

The notebook concludes with model evaluation and insights drawn from the final tuned model. 
The Kaggle competition determined that the model would be evaluated using Receiver Operating Characteristic Area Under the Curve (roc-auc).

## Libraries Used

- Pandas: For data manipulation and engineering.
- Matplotlib and Seaborn: For data visualization.
- Scikit-Learn: For preprocessing and modeling.
- Optuna: For hyperparameter optimization.
- Math: For math.ceil()
- Numpy: For conditional calculations using np.where()
- LightGBM: For the LGBMClassifier, which works well for binary classification with non-linear relationships between variables

## How to Use

- Clone the repository: ``` git clone https://github.com/Alexej9671/kaggle_loan_approval_prediction.git ```
- Install dependencies: ``` pip install -r requirements.txt ```
- Run the notebook: Open `train_models.ipynb` in Jupyter Notebook or Jupyter Lab.
