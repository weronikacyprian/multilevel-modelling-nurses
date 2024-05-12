# Multilevel Analysis of Nurse Stress Intervention

This Github repository contains the code and analysis for a research project titled "Does the experimental 'Intervention' have a significant impact on nurse stress (post-stress)" conducted by Weronika Cyprian. The project aims to assess the effectiveness of an experimental intervention program in reducing stress levels among nurses working in Accident and Emergency (A&E) departments in hospitals.

## Project Overview

The project utilizes a longitudinal multisite trial dataset, consisting of stress scores of nurses at various time intervals after participating in the intervention program. The analysis employs multilevel modeling techniques to account for the hierarchical structure of the data, where nurses are nested within hospitals.

## Key Components

### 1. Data Exploration and Preprocessing

- Exploratory data analysis (EDA) to understand the structure and characteristics of the dataset.
- Handling missing values and summarizing key variables.
- Visualisations such as boxplots and scatterplots to explore relationships between variables.

### 2. Model Building and Analysis

- Construction of multilevel models to assess the impact of the intervention on nurse stress levels.
- Iterative model building process, starting from null models and gradually incorporating lower-level and upper-level predictors.
- Assessment of model fit and significance using likelihood ratio tests (LRT) and hypothesis testing.
- Interpretation of model coefficients and effect sizes.

### 3. Results and Discussion

- Presentation of findings regarding the effectiveness of the intervention program.
- Discussion of additional factors influencing nurse stress levels, such as experience, gender, and department size.
- Limitations of the study and recommendations for future research.

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine using `git clone https://github.com/username/repository.git`.

2. **Navigate to Code**: Explore the R scripts and Markdown files containing the analysis and visualizations.

3. **Run the Analysis**: Execute the R scripts in your preferred R environment to reproduce the analysis and generate results.

4. **Review Results**: Read through the Markdown files to understand the findings and interpretations of the analysis.

## Requirements

- R and RStudio
- Required R packages: lme4, lmerTest, ggplot2, sjPlot, dplyr, tidyr, performance, car

## Contributing

Contributions to this project are welcome! If you have suggestions for improvements or would like to report issues, please feel free to open an issue or submit a pull request.
