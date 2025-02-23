# Machine Learning Model for Diabetes Diagnosis

## Description

This project focuses on training a predictive machine learning model to diagnose diabetes in female patients. The dataset used for training was sourced from Kaggle, consisting of over 800 records. The workflow includes data cleaning, exploratory data analysis, model training, evaluation, and visualization of performance metrics.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) using Pandas
- Implementation of multiple machine learning techniques using Scikit-Learn
- Model evaluation and hyperparameter tuning
- Performance visualization using Seaborn and Matplotlib
- Achieved an accuracy score of up to 80%

## Technologies Used

- Python
- Pandas, NumPy for data manipulation
- Scikit-Learn for machine learning models
- Seaborn, Matplotlib for visualization

## Installation & Setup

### Prerequisites

- Python 3.x installed
- Jupyter Notebook or a Python IDE (VS Code, PyCharm, etc.)
- Virtual environment (optional but recommended)

### Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/TheVinh-Ha-1710/Diabetes-Predictive-Model.git
   cd Diabetes-Predictive-Model
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

## Usage

1. Load and preprocess the dataset.
2. Perform exploratory data analysis to understand data insights.
3. Train and evaluate various machine learning models.
4. Optimize the best-performing model through hyperparameter tuning.
5. Visualize model performance with accuracy, confusion matrix, and ROC curve.

## Folder Structure

```
📂 Diabetes-Predictive-Model
 ├── 📜 README.md               # Project documentation   
 ├── 📜 diabetes.csv            # Model training script notebook  
 ├── 📜 model_training.ipynb    # Dataset  
 ├── 📜 model_training.pdf      # PDF version of the notebook
 ├── 📜 requirements.txt        # Dependencies    
```
