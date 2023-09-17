# Indian Judicial Dataset

- JudegesAnalysis.ipynb : Data Analysis of the judges_clean.csv.
- CaseAnalysis.ipynb : Data Analysis of the case_[year].csv files. Also uses the judges_clean.csv to get combined insights.
- Classification.ipynb : Data sampling, preprocessing, and comparison of 4 different classification models for the classification problem considered.

In order to run the files, ensure all files and the dataset are in the same directory tree as below (or change the file path in the code to run). Run all the cells in the ipynb notebook to get the output.


```bash
├── JudgesAnalysis.ipynb
├── CaseAnalysis.ipynb
├──Classification.ipynb
├──judges_clean.csv
├──acts_sections.csv
├──cases
│   ├── cases_2010.csv
│   ├── cases_2011.csv
│   ├── cases_2012.csv
│   ├── cases_2013.csv
│   ├── cases_2014.csv
│   ├── cases_2015.csv
│   ├── cases_2016.csv
│   ├── cases_2017.csv
│   └── cases_2018.csv
└──keys
│   ├── act_key.csv
│   ├── cases_court_key.csv
│   ├── cases_district_key.csv
│   ├── cases_state_key.csv
│   ├── disp_name_key.csv
│   ├── judge_case_merge_key.csv
│   ├── purpose_name_key.csv
│   ├── section_key.csv
│   └── type_name_key.csv
```


Lanugage: Python
Libraries Used:
- pandas == 3.11
- matplotlib
- scikit-learn == 1.2.2
- datetime
