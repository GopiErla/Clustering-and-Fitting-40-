# Project Title: Analysis of Student Performance

## Project Overview
This project applies data science techniques to analyze student performance data. The aim is to uncover patterns in student scores across various demographics using k-means clustering and predict reading scores from math scores using linear regression. Insights from this analysis could help tailor educational strategies and interventions.

## Repository Structure
```
/Clustering-and-Fitting-40-
|-- notebooks/
|   |-- Clustering_Fitting.ipynb     # Jupyter notebook containing the analysis
|-- data/
|   |-- StudentsPerformance.csv      # Dataset used for the analysis
|-- README.md                        # This file
|-- requirements.txt                 # Python package dependencies
```

## Installation and Setup
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GopiErla/Clustering-and-Fitting-40-.git
   cd Clustering-and-Fitting-40-
   ```

2. **Install dependencies**:
   Make sure Python is installed on your system. Then install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**:
   Open the Jupyter notebook to view the analysis:
   ```bash
   jupyter notebook notebooks/Clustering_Fitting.ipynb
   ```

## Analysis Workflow
- **Data Preprocessing**: The data is first cleaned and normalized to ensure consistency in the analysis.
- **Clustering Analysis**: K-means clustering is performed to identify distinct groups based on student performance.
- **Regression Analysis**: Linear regression is used to predict reading scores from math scores.
- **Visualization**: Various plots including scatter plots, histograms, and heatmaps are used to visualize the results.

## Results
- The clustering identified three main groups of students based on their performance levels.
- The regression model showed a strong positive relationship between math and reading scores.
- Visualizations provided deeper insights into the distribution and relationships within the data.

## Technologies Used
- **Python**: Major programming language used for the analysis.
- **Pandas/NumPy**: For data manipulation.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Statsmodels**: For more detailed statistical analysis.

## Author
- GopiErla
