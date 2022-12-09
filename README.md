# Predicting Illegal Substance Use
This study aims to produce a classification model that can predict the number of illegal substances used within a year from demographics, personality traits, as well as the frequency of legal substance use.

## packages and versions
Python: 3.10.5\
numpy: 1.22.4\
matplotlib: 3.5.2\
sklearn: 1.1.1\
pandas: 1.4.2\
xgboost: 1.5.1\
shap: 0.40.0

## files and how to use
├── data: unprocessed dataset downloaded from Kaggle\
├── figures: all generated figures\
├── results: models and corresponding test data and prediction saved using pickle\
├── report \
├──── final_report.pdf\
├──── final_report.tex\
├──── models_and_hyperparameters.png: a table containing all models and hyperparameters\
├──── references.bib\
├── src: \
├──── dataset_download.ipynb: download dataset from Kaggle\
├──── EDA.ipynb: exploratory data analysis\
├──── models.ipynb: training all five classification models\
