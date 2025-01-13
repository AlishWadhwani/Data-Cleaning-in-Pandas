# Data-Cleaning-in-Pandas

## Overview

This project demonstrates data cleaning and analysis techniques using Python and the Pandas library. It focuses on processing a customer call list dataset, addressing various data quality issues, and preparing the data for further analysis.

## Features

### Data Cleaning
- Removing duplicates
- Standardizing data formats (e.g., phone numbers, names)
- Handling missing values
- Correcting inconsistent data entries

### Data Analysis
- Exploratory Data Analysis (EDA)
- Customer segmentation based on various attributes
- Identifying patterns in customer data

## Installation

To run this project, you need to have Python installed along with the following libraries:

pip install pandas numpy matplotlib seaborn
text

## Usage

The main script can be run using:

python data_cleaning_analysis.py
text

Key operations include:
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
Load the data
df = pd.read_excel('Customer-Call-List.xlsx', sheet_name='Call List')
Data cleaning steps
(Include key data cleaning operations here)
Analysis
(Include key analysis operations here)
text
```
## Key Insights

- Distribution of paying vs non-paying customers
- Geographical distribution of customers
- Patterns in contact preferences

## Contributing

Contributions to improve the analysis or extend the project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-source and available under the MIT License.