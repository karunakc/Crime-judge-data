# Indian Judicial Dataset

- JudegesAnalysis.ipynb : Data Analysis of the judges_clean.csv.
- CaseAnalysis.ipynb : Data Analysis of the case_[year].csv files. Also uses the judges_clean.csv to get combined insights.
- Classification.ipynb : Data sampling, preprocessing, and comparison of 4 different classification models for the classification problem considered.


Dataset Hierarchy:
- judges_clean.csv
- acts_sections.csv
- key
-       csv files to link with other csv files or to get further insights of the column which have only id and no other details
- cases
-       cases_[year].csv


Lanugage: Python
Libraries Used:
- pandas == 3.11
- matplotlib
- scikit-learn == 1.2.2
- datetime
