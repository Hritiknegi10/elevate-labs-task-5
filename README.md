# elevate-labs-task-5
Titanic Exploratory Data Analysis (EDA)

Data Analyst Internship - Task 5

Objective

Extract insights from the Titanic passenger dataset using statistical summaries and visual exploration.

Tools

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Project Files

Titanic_EDA.ipynb - complete executed EDA notebook with observations

Titanic_EDA_Report.pdf - concise PDF report of findings

titanic.csv - dataset (891 rows, 12 columns)

images/ - exported visualizations

requirements.txt - Python dependencies

Analysis Performed

Dataset overview using head(), info(), describe() and value_counts()

Missing-value and duplicate checks

Overall survival analysis

Survival by sex and passenger class

Age and fare distributions

Histogram, boxplot, scatterplot, heatmaps, and pairplot

Correlation analysis

Fare outlier detection using the 1.5*IQR rule

Written observation for each major visual

Key Findings

Overall survival rate: 38.4%

Female survival: 74.2% vs male survival: 18.9%

Class 1 survival: 63.0% vs Class 3: 24.2%

Survivors paid higher fares on average (about 48.40) than non-survivors (about 22.12)

Missing values: Cabin 687, Age 177, Embarked 2

Pclass has a negative relationship with survival while Fare has a positive relationship

How to Run

Install the dependencies:

pip install -r requirements.txt

Open Titanic_EDA.ipynb in Jupyter Notebook/JupyterLab/VS Code.

Keep titanic.csv in the same folder as the notebook.

Run all cells from top to bottom.

Dataset Reference

The included file uses the standard 891-row Titanic training dataset structure commonly used for introductory EDA. A public reference copy is available in the DataScienceDojo datasets repository:
https://github.com/datasciencedojo/datasets/blob/master/titanic.csv
