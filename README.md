# House Price Prediction Project

This project aims to predict house prices using various regression and machine learning models. The dataset used is `KC_House_Sales.csv`, which contains information about house sales in King County. The project involves data preparation, exploratory analysis, model building, evaluation, and documentation.

## Project Steps

1. **Team Formation**
   - Joined a team of four students to collaboratively work on the project.

2. **Data Loading and Review**
   - Loaded the dataset `KC_House_Sales.csv` and performed an initial review to understand its structure and contents.

3. **Data Splitting**
   - Split the dataset into training (70%) and testing (30%) sets using a random seed of 1023 to ensure reproducibility.

4. **Data Preparation**
   - Investigated and cleaned the data by combining categorical variables, dropping irrelevant variables (such as `id`, `Latitude`, `Longitude`), and addressing any data quality issues.

5. **Exploratory Data Analysis**
   - Created scatter plots and a correlation matrix for the training dataset to visualize and interpret the relationships between variables and their potential impact on the response variable, `price`.

6. **Model Building and Selection**
   - Built multiple linear regression models using stepwise selection to identify the best models.
   - Compared the performance of the top two linear models based on various metrics.

7. **Model Assumptions**
   - Checked assumptions for the final model (e.g., linearity, normality of residuals) and applied remedial measures, such as transformations if necessary.

8. **Variance and Multicollinearity**
   - Investigated issues related to unequal variances and multicollinearity.
   - Applied remedial methods (e.g., Weighted Least Squares, Ridge, Elastic Net, Lasso) where needed to address these issues.

9. **Alternative Modeling Approaches**
   - Built and evaluated an alternative model using one of the following approaches: regression tree, neural network (NN), or support vector machine (SVM).
   - Checked the applicable model assumptions and explored logistic regression if relevant.

10. **Model Evaluation**
    - Assessed the performance of the models using the test dataset to ensure they generalize well to unseen data.

11. **Model Selection**
    - Based on performance metrics from both the training and test datasets, determined the primary (champion) model and identified a benchmark model for comparison.

12. **Documentation**
    - Created a comprehensive model development document that describes the model, methodology, and findings, following the provided template.

## Project Team

- [Hannah Halvorsen]
- [Daniel Yinanc]
- [Swapnil Diangade]
- [Sravan Katepalli]
- [Phu Thai]
- [Sheri Cunningham]

## How to Run the Project

1. Ensure you have the necessary libraries installed. You can install them using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels


