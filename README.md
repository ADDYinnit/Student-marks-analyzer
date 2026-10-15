# Student Marks Dataset - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on the `Student_Marks.csv` dataset to understand how student performance (Marks) is influenced by the number of courses they take and their study time.

## Dataset Description

The dataset contains 100 observations and 3 main columns:
1. **`number_courses`**: The number of courses the student has opted for.
2. **`time_study`**: The daily study time dedicated by the student (in hours).
3. **`Marks`**: The marks obtained by the student.

## Key Findings
- **No Missing Values**: The dataset is clean and complete with no null entries.
- **Strong Correlation**: There is an exceptionally strong positive correlation (~0.94) between **study time** and **marks obtained**, showing that study hours are the primary driver of higher marks.
- **Moderate Correlation**: The **number of courses** has a moderate positive correlation (~0.42) with student marks.

## How to Run the Analysis
Ensure you have the following Python libraries installed:
```bash
pip install pandas matplotlib seaborn
```

Run the analysis code in a Jupyter Notebook environment:
- Load the dataset with `pandas.read_csv`.
- Review distributions and descriptive statistics with `df.describe()`.
- Generate pairwise scatter plots and a correlation matrix heatmap using `seaborn`.
