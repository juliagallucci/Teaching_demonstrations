
This folder contains the annotated code used in the teaching demonstrations for the Assistant Professor (Teaching Stream) interview at the University of Toronto Faculty of Information.
Each script is designed to accompany the corresponding slide deck and dataset, illustrating key data science concepts through clear, step-by-step examples that emphasize both the how and the why behind each analysis.
More detailed explanations of each step are available in these notebooks.


1. Clustering Demonstration

- File: clustering_demo.ipynb
- Language: Python
- Course Context: INF2190 – Introduction to Data Analytics
- Overview:
This notebook introduces students to unsupervised learning using the K-Means algorithm on the Palmer Penguins dataset.
It walks through the process of data scaling, model fitting, and evaluating clustering performance using the total within-cluster sum of squared distances (WSSD) and the elbow method.

- Key Steps:
  - Scaling features with StandardScaler
  - Applying KMeans with multiple k values
  - Interpreting cluster quality using WSSD
  - Plotting the elbow curve to choose the optimal cluster number

2. Simple Linear Regression and Correlation Demonstration

- File: linear_regression_demo.Rmd
- Language: R
- Course Context: INF1344 – Introduction to Statistics for Data Science
- Overview:
This R Markdown file demonstrates supervised learning through simple linear regression, using the Sacramento Real Estate dataset.
It shows how to fit a regression model, interpret coefficients, visualize the line of best fit, and evaluate model performance using R-squared and RMSE.

- Key Steps:
  - Importing and exploring the dataset
  - Fitting a linear regression model with lm()
  - Visualizing the relationship with ggplot
  - Calculating and interpreting R-squared and RMSE
