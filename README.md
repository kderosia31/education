# Project Title: The relationship between socioeconomic status and educational opportunity


## Project Overview
This project uses publicly available data to determine if socioeconomic variables influence educational opportunity. Specifically, this project assesses which specific combination of socioeconomic variables predict ACT/SAT scores the best.

## Objective:
To determine if specific socioeconomic status variables predict ACT scores
## Domain: 
Education
## Key Techniques: 
Regression
## Project Structure
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
## Data Source: 
[raw data file 1](data/EdGap_data.xlsx) [raw data file 2](data/ccd_sch_029_1617_w_1a_11212017.csv)

## Description: 
## License: (if applicable)
## Analysis:
Data was cleaned by changing column names and merging the school information and education gap data frames into a single, tidy data frame. A small percentage of missing values were removed and socioeconomic variables were imputed with predicted values from an iterative imputer. The notebook that performed the data preparation is [Education.ipynb](code/Education.ipynb). The clean data file can be found [here](data/education_clean.csv). After data cleaning and imputing, multiple linear regression analysis was performed to determine which socioeconomic variables predicted ACT scores. Multiple models were fit and assessed to determine which model is best suited to answer the question.

## Results
It was found that the percentage of students eligible for free or discounted lunches was the single best predictor of ACT scores. However, the addition of unemployment rate and the percentage of adults with a college degree improved the model fit. The final model that was used for analysis included only the percentage of students eligible for free/discounted lunches and the percentage of adults with a college degree. This was chosen because this model had one less variable but explained essentially the same amount of variance in the ACT scores. 

## Authors
Kyle DeRosia
## License
NA

## Acknowledgements
Tools/libraries used: pandas, numpy, seaborn, sklearn, statsmodels

