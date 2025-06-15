# Life Expectancy Data Preprocessing

This project focuses on preprocessing and cleaning life expectancy data, including various health and demographic indicators. The goal is to prepare the dataset for further analysis and machine learning applications by handling outliers, imputing missing values, and visualizing key features.


## Table of Contents

- [Overview](#overview)
- [Dataset Description](#description)
- [Steps of Preprocessing](#steps)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Next Step](#next_step)
- [Contributing](#contributing)
- [License](#license)


## Overview

The objective of this project is to preprocess a dataset related to life expectancy in different countries, accounting for features such as mortality rates, GDP, schooling, health expenditures, and other health-related factors. By cleaning and preparing the dataset, it will be suitable for further machine learning models that can predict life expectancy or explore relationships between various indicators.


## Description
The dataset consists of health and demographic data with the following key features:

  - Country: The name of the country
  - Year: The year of the data entry
  - Life Expectancy: Life expectancy in years
  - Adult Mortality: Adult mortality rate (per 1000 population)
  - GDP: Gross Domestic Product per capita
  - Schooling: Average number of years of schooling
  - HIV/AIDS: HIV/AIDS death rate
and other indicators such as Alcohol consumption, Hepatitis B prevalence, thinness (5-9 years), and Income composition of resources.


## Steps

- importing modules
- Read Dataset
- Sanity Check
    - Remove unnecessary columns
    - Remove duplicates
    - Formatting column names
- Exploratory Data Analysis
    - Histogram
    - Boxplot
    - Scatterplot
    - Heatmap
- Handling Missing Values
    - KNNImputer
- Handling Outliers
- Encoding Data
    - Label encoding


## Installation

1. **Install The Environment:**
   ```bash
   https://docs.anaconda.com/anaconda/install/
   ```

2. **Install Jupyter Notebook:**
   ```bash
   pip install notebook
   ```
   or
   ```bash
   conda install -c conda-forge notebook
   ```
3. **Clone the repository:**

    ```bash
    git clone https://github.com/tshihab/Life-Exepectancy-Data-Preprocessing.git
    ```

4. **Navigate to the project directory:**

    ```bash
    cd Life-Exepectancy-Data-Preprocessing
    ```


## Dependencies

The project uses the following Python libraries:

  - **pandas:** For data manipulation and analysis.
  - **numpy:** For numerical operations.
  - **seaborn** and **matplotlib:** For data visualization.
  - **scikit-learn:** For the KNNImputer.
  - **pathlib:** Ensure the xlsx file paths work correctly across different operating systems.
  - **Install Dependies:**
    ```bash
    pip install pandas numpy scikit-learn seaborn matplotlib pathlib
    ```


## Usage
To run the preprocessing steps, open the provided Jupyter Notebook or execute the code in Python. The key sections in the notebook include:

  - Loading the dataset
  - Visualizing outliers through box plots
  - Imputing missing values using KNN
  - Detecting and addressing outliers
  - Encode the dataset with label encoding


## Next Step
After preprocessing, the dataset will be ready for further analysis, including:

  - ***Feature selection:*** Identifying the most significant life expectancy features.
  - ***Modeling:*** Applying machine learning models (e.g., regression, decision trees) to predict life expectancy.
  - ***Statistical analysis:*** Understanding the correlation between various indicators and life expectancy.


## Contributing

Contributions are welcome! Please feel free to submit a pull request.


## License

This project is licensed under the [MIT License](LICENSE).
