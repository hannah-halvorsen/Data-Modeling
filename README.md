House Price Prediction Project
This project aims to predict house prices using various regression and machine learning models. The dataset used is KC_House_Sales.csv, which contains information about house sales in King County. The project involves data preparation, exploratory analysis, model building, evaluation, and documentation.

Project Steps
Team Formation

Joined a team of four students to collaboratively work on the project.
Data Loading and Review

Loaded the dataset KC_House_Sales.csv and performed an initial review to understand its structure and contents.
Data Splitting

Split the dataset into training (70%) and testing (30%) sets using a random seed of 1023 to ensure reproducibility.
Data Preparation

Investigated and cleaned the data by combining categorical variables, dropping irrelevant variables (such as id, Latitude, Longitude), and addressing any data quality issues.
Exploratory Data Analysis

Created scatter plots and a correlation matrix for the training dataset to visualize and interpret the relationships between variables and their potential impact on the response variable, price.
Model Building and Selection

Built multiple linear regression models using stepwise selection to identify the best models.
Compared the performance of the top two linear models based on various metrics.
Model Assumptions

Checked assumptions for the final model (e.g., linearity, normality of residuals) and applied remedial measures, such as transformations if necessary.
Variance and Multicollinearity

Investigated issues related to unequal variances and multicollinearity.
Applied remedial methods (e.g., Weighted Least Squares, Ridge, Elastic Net, Lasso) where needed to address these issues.
Alternative Modeling Approaches

Built and evaluated an alternative model using one of the following approaches: regression tree, neural network (NN), or support vector machine (SVM).
Checked the applicable model assumptions and explored logistic regression if relevant.
Model Evaluation

Assessed the performance of the models using the test dataset to ensure they generalize well to unseen data.
Model Selection

Based on performance metrics from both the training and test datasets, determined the primary (champion) model and identified a benchmark model for comparison.
Documentation

Created a comprehensive model development document that describes the model, methodology, and findings, following the provided template.
Project Team
[Student 1]
[Student 2]
[Student 3]
[Student 4]
How to Run the Project
Ensure you have the necessary libraries installed. You can install them using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
Load the dataset and follow the steps outlined in the project. The code is organized into Jupyter notebooks/scripts corresponding to each step of the project.

Refer to the documentation for detailed explanations of the methodologies used and the results obtained.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

