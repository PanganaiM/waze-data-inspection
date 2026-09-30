# Waze User Data — Inspection and Preparation

## Project Overview
This project performs an initial inspection and preparation of a Waze user dataset. The objective is to understand the dataset's structure, assess data quality, examine important variables and prepare the data for later exploratory and statistical analysis.

## Objectives
- Load and inspect the Waze dataset.
- Understand its dimensions, columns and data types.
- Identify missing information.
- Review descriptive statistics.
- Examine churn and device distributions.
- Compare selected behavioural characteristics of retained and churned users.
- Identify issues that should be considered in later analysis.

## Tools and Technologies
- Python
- pandas
- NumPy
- Jupyter Notebook

## Dataset
The dataset contains **14,999 user records** and behavioural variables related to Waze usage and driving activity.

## Data Inspection Workflow
1. Import the required Python libraries.
2. Load the CSV dataset into a pandas DataFrame.
3. Inspect rows, columns, dimensions and data types.
4. Generate descriptive statistics.
5. Review missing values.
6. Examine churn and device categories.
7. Compare retained and churned users across relevant behavioural measures.
8. Document data-quality observations and preparation requirements.

## Selected Output

### Dataset Size
- **14,999 records**

### Missing Churn Labels
- **700 records** have missing churn information.

### Churn Distribution
Among records with a churn label:
- **Retained:** 11,763
- **Churned:** 2,536

### Device Distribution
The dataset contains users from both iPhone and Android devices, with iPhone users representing the larger group.

## Key Observations
- The dataset is large enough to support meaningful exploratory analysis.
- Missing churn labels must be considered before analyses that use churn as the target or grouping variable.
- Retained users substantially outnumber churned users.
- Behavioural variables show substantial variation across users.
- Initial retained-versus-churned comparisons provide direction for deeper exploratory and statistical analysis.

## Why This Stage Matters
Data inspection is performed before drawing conclusions or building models. It helps identify missing information, unusual values, variable types, class balance and other issues that can affect subsequent analysis.

## Repository Contents
- `waze_data_inspection.ipynb` — data inspection and preparation notebook
- `waze_dataset.csv` — project dataset
- `README.md` — project documentation

## How to Run
1. Clone or download the repository.
2. Install the required Python libraries.
3. Open `waze_data_inspection.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells from top to bottom.

## Skills Demonstrated
- Data inspection
- Data-quality assessment
- pandas DataFrame operations
- Descriptive statistics
- Missing-value analysis
- Categorical distribution analysis
- Preparation of data for downstream analytics
