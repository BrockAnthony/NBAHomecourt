
# DS4200 Final Project

## Introduction
This repository contains the final project for DS4200. The project focuses on analyzing mental health in the workplace, particularly within the tech industry. Using a comprehensive dataset, we aim to uncover trends and insights that could inform mental health policies and support systems in tech companies.

## Dataset
The dataset used in this project was sourced from Kaggle and includes various metrics related to mental health in the tech workplace. Key data points include age, gender, country, state, employment status, remote work status, mental health condition, treatment sought, and more.

## Preprocessing Steps
Preprocessing of the dataset involved several key steps to ensure the data was clean and suitable for analysis:
1. **Handling Missing Values**: Missing values in specific columns were addressed either by filling them with a default value or excluding the rows/columns as needed.
2. **Data Type Conversion**: Columns were converted to appropriate data types, such as converting 'Timestamp' to datetime format.
3. **Cleaning Text and Categorical Data**: Text data was standardized for consistency, and categorical data with numerous unique values was cleaned.
4. **Age Data Cleaning**: Outlier age values were replaced with the median age, and ages were categorized into specific age groups.
5. **Gender Data Standardization**: Gender categories were standardized to 'Male', 'Female', and 'Other'.
6. **Numerical Encoding**: Columns with three or fewer unique elements were converted to numerical format for ease of analysis.

## Visualizations
The project includes various visualizations to illustrate the findings from the dataset, such as:
- Gender distribution
- Age group distribution
- Geographic distribution of respondents
- Proportions of respondents with family history of mental illness
- Impact of mental health on work

## Tools and Technologies
- **Python**: For data analysis and visualization.
- **Libraries**: Pandas, Matplotlib, Seaborn.

## Contributing
This project is part of the DS4200 course, and contributions are limited to course participants.

## Authors
- Jordan Walsh
- Brock Ada
- Li Zou

## Acknowledgments
- Thanks to DS4200 course staff and fellow students for guidance and support.
- Kaggle for providing the dataset.
