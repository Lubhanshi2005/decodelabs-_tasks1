# Student Performance Analysis 📊

## 📌 Project Overview

Student Performance Analysis is a data science project that explores student academic results using Python. The project analyzes a dataset of student records to understand patterns in final grades and examine how study time, school absences, and other numerical variables relate to academic performance.

Data analysis and visualization techniques are used to summarize the dataset and present the findings through graphs and a correlation heatmap.

## 🎯 Objectives

- Analyze student academic performance using Python.
- Inspect the dataset for missing values and duplicate records.
- Calculate descriptive statistics for student grades.
- Explore the relationship between study time and final grades.
- Analyze the relationship between school absences and final grades.
- Visualize grade distributions and correlations.
- Present the results in a clear and understandable format.

## 🛠️ Technologies Used

- **Python** — programming and analysis
- **Pandas** — data cleaning and manipulation
- **Matplotlib** — data visualization
- **Seaborn** — statistical charts and heatmaps
- **Google Colab / Jupyter Notebook** — development environment

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── student_data.csv
├── cleaned_student_data.csv
├── student_performance_correlations.csv
├── student_performance_summary.csv
├── student_performance_heatmap.png
├── study_time_vs_grade.png
├── absences_vs_grade.png
├── grade_distribution.png
├── grade_correlation.png
├── Student_Performance_Analysis_Report.pdf
└── README.md
```

*Note: The project report and graph files should be included in the repository if you have generated them.*

## 📊 Dataset Description

The dataset contains **395 student records and 33 features**.

Important columns include:

| Column | Description |
|---|---|
| `studytime` | Weekly study-time category |
| `absences` | Number of school absences |
| `G1` | Grade from the first period |
| `G2` | Grade from the second period |
| `G3` | Final grade |

The final grade (`G3`) is used as the main variable for analyzing student performance.

## 🔍 Project Workflow

1. Load the dataset using Pandas.
2. Inspect rows, columns, and data types.
3. Check missing values and duplicate records.
4. Calculate summary statistics.
5. Visualize study time against final grades.
6. Explore absences against final grades.
7. Plot the distribution of final grades.
8. Calculate correlations between numerical features.
9. Generate a correlation heatmap.
10. Summarize the results in a project report.

## 📈 Visualizations

The project includes the following visualizations:

- **Study Time vs Final Grade:** Compares average final grades across study-time categories.
- **Absences vs Final Grade:** Examines the relationship between absences and final grades.
- **Grade Distribution:** Shows the distribution of students' final grades.
- **Grade Correlation:** Displays correlations between numerical features and final grades.
- **Correlation Heatmap:** Visualizes correlations among numerical variables.

## 📋 Key Findings

- The dataset contains 395 student records.
- The average final grade (`G3`) is approximately **10.42 out of 20**.
- A total of 265 students scored 10 or above, while 130 scored below 10.
- Earlier-period grades (`G1` and `G2`) show strong positive correlations with final grades.
- Study time and absences can be explored for patterns in academic outcomes.

**Important:** Correlation does not imply causation. These results describe associations in the dataset and do not prove that a particular factor directly causes a change in grades.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open Google Colab or Jupyter Notebook.
3. Upload the dataset file `student_data.csv`.
4. Install the required libraries if necessary:

   ```bash
   pip install pandas matplotlib seaborn
   ```

5. Load the dataset:

   ```python
   import pandas as pd

   df = pd.read_csv("student_data.csv")

   print(df.head())
   print(df.shape)
   print(df.describe())
   ```

6. Run the project's analysis and visualization cells.

## 💡 Future Improvements

- Build a machine learning model to predict final grades.
- Compare the performance of different prediction algorithms.
- Explore additional categorical variables.
- Create an interactive dashboard using Streamlit or Power BI.
- Evaluate model performance using appropriate metrics.

## 📄 License

This project is intended for educational and learning purposes. Before redistributing the dataset, verify its original source and applicable license.
