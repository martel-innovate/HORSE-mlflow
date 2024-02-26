# HORSE-mlflow

Repository for HORSE project.

## Instructions
- Download 5GNIDD dataset (too big to put in this repository). Link: https://www.kaggle.com/datasets/humera11/5g-nidd-dataset
- Move file Combined.csv into data/5GNIDD folder
- Create a virtual environment using the requirements.txt:
  ```
  # using pip
  pip install -r requirements.txt

  # using Conda
  conda create --name <env_name> --file requirements.txt ```
- Run the notebook mlflow-5GNIDD.ipynb
- The notebook will train several machine learning models and evaluates them to find the best ones.
