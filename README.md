# Project Title: The relationship between socioeconomic status and educational opportunity
This project will use publicly available data to determine if socioeconomic variables influence educational opportunity. Specifically, ACT/SAT scores.

## Project Overview


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
[data file 1](data/EdGap_data.xlsx) [data file 2](data/ccd_sch_029_1617_w_1a_11212017.csv)
## Description: 
## License: (if applicable)
## Analysis:
Data was cleaned by changing column names and merging the school information and education gap data frames into a single, tidy data frame. A small percentage of missing values were removed and socioeconomic variables were imputed with predicted values from an iterative imputer. The notebook that performed the data preparation is [Education.ipynb](code/Education.ipynb). The clean data file can be found [here]data/education_clean.csv

## Results

## Authors
Kyle DeRosia
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Tools/libraries used
Tutorials or papers referenced
Inspiration or collaborators
