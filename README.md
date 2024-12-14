# DS.v3.2.1.5

# Mental Health in Tech Survey 2014

This project involves analyzing a dataset from a 2014 survey on mental health in the tech workplace. The goal is to practice performing **Exploratory Data Analysis (EDA)** and visualizing insights using **Pandas**, **Matplotlib**, and **Seaborn**. Additionally, it involves using **sqlite** to query the dataset and estimating population parameters from the sample data while communicating the uncertainty in the findings.

## Objectives

1. **EDA with Pandas**: Gain insights from data by performing exploratory data analysis using statistical summaries and visualizations.
2. **Data Visualization**: Practice visualizing data using Matplotlib and Seaborn.
3. **Statistical Estimation**: Estimate population parameters from sample data and communicate uncertainties through confidence intervals.
4. **SQL Integration**: Practice querying a dataset using sqlite.

## Requirements

- Download the dataset from [Kaggle](https://www.kaggle.com/datasets/anth7310/mental-health-in-the-tech-industry).
- Use sqlite to query the dataset, and load the final dataset into a Pandas DataFrame for further analysis.
- Provide an overview of the survey respondents, including sample size and sociodemographic features.
- Investigate and discuss any potential sampling bias.
- Perform exploratory data analysis:
  - Generate statistical summaries.
  - Explore relationships between variables.
  - Visualize data using plots.
- Report the prevalence rates of at least three mental health conditions, including the confidence intervals and their interpretation.
- Provide suggestions on how the analysis could be improved.

## Dataset

The dataset is available for download from Kaggle:

- [Mental Health in Tech Survey Dataset](https://www.kaggle.com/datasets/anth7310/mental-health-in-the-tech-industry)

### Dataset Overview

This data is from Open Source Mental Illness (OSMI) using survey data from years 2014, 2016, 2017, 2018 and 2019. Each survey measures and attitudes towards mental health and frequency of mental health disorders in the tech workplace.

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pandas
- sqlite3
- Matplotlib
- Seaborn
- Jupyter Notebook (optional but recommended)

### Steps to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/mental-health-in-tech.git
    cd mental-health-in-tech
    ```

2. **Install Dependencies**:
    You can use `pip` to install the required Python packages:
    ```bash
    pip install pandas sqlite3 matplotlib seaborn jupyter
    ```

3. **Download the Dataset**:
    Download the dataset from [Kaggle](https://www.kaggle.com/datasets/anth7310/mental-health-in-the-tech-industry) and save it in the `data/` directory.

4. **Run the Jupyter Notebook**:
    Launch Jupyter Notebook to view and execute the code:
    ```bash
    jupyter notebook
    ```
    Open the file `mental_health_analysis.ipynb` to start exploring the analysis.

5. **Perform SQL Queries**:
    The project uses sqlite to query the dataset before loading it into a Pandas DataFrame for analysis. You can modify the queries to explore different aspects of the dataset.

## Exploratory Data Analysis (EDA)

The project performs various steps in the EDA process:

1. **Overview of Respondents**:
    - Sample size
    - Sociodemographic features (age, gender, country, etc.)
    - Discussion on potential sampling bias

2. **Statistical Summaries**:
    - Basic statistics like mean, median, mode, etc.
    - Frequency distributions for key features.

3. **Data Visualization**:
    - Correlation analysis between mental health treatment and various demographic features.
    - Visualizations using bar charts, histograms, and correlation matrices.

4. **Prevalence of Mental Diseases**:
    - The analysis will include the prevalence rates of at least three mental health conditions.
    - Confidence intervals will be plotted along with the data to communicate uncertainty in the estimates.

## Results & Interpretation

- **Confidence Intervals**: Interpretation of confidence intervals will be provided for the reported prevalence rates.
- **Key Insights**: Major trends and patterns will be highlighted, such as potential relationships between demographics and mental health conditions.

## Suggestions for Improvement

At the end of the notebook, some potential improvements will be suggested:

1. Collecting more data to improve generalizability.
2. Handling missing values or outliers more rigorously.
3. Expanding the scope of analysis by adding more features or external data sources.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Open Sourcing Mental Illness organization for the dataset.
- This project was inspired by a desire to better understand mental health trends in the tech industry.
