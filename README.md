# Sales Prediction using Python

1. About the Project

Sales prediction is an important part of business planning. Companies use sales data to understand customer demand and make better marketing decisions.

In this project, I used Python and Machine Learning to analyze the relationship between advertising expenses and sales. The main goal is to predict sales based on the amount spent on TV, Radio, and Newspaper advertising.

This project helped me understand how data analysis and regression models can be used to solve real-world business problems.

2. Project Objectives

- Analyze advertising expenditure and sales data.
- Clean and prepare the dataset for analysis.
- Understand the relationship between advertising and sales.
- Visualize advertising trends using graphs.
- Build a Linear Regression model to predict sales.
- Evaluate model performance using different metrics.
- Generate sales predictions using new advertising data.

3. Dataset

The project uses `Advertising.csv`.

The dataset contains the following columns:

- TV: Advertising expenditure on television.
- Radio: Advertising expenditure on radio.
- Newspaper: Advertising expenditure on newspapers.
- Sales: Sales value used as the prediction target.

The `Unnamed: 0` column, if present, is removed because it represents the record index rather than an advertising feature.

4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

5. Project Workflow

1. Import the required Python libraries.
2. Load and explore the dataset.
3. Check missing values and duplicate records.
4. Clean and prepare the data.
5. Visualize advertising expenditure and sales.
6. Analyze correlations between the variables.
7. Split the dataset into training and testing sets.
8. Train a Linear Regression model.
9. Evaluate the model using MAE, RMSE, and R² score.
10. Predict sales using new advertising expenditure values.

6. Data Visualization

The project includes the following graphs:

- Advertising Expenditure Distribution
- TV Advertising vs Sales
- Radio Advertising vs Sales
- Newspaper Advertising vs Sales
- Correlation Heatmap
- Actual vs Predicted Sales

These visualizations help in understanding the relationships between advertising expenditure and sales.

7. Model Evaluation

The Linear Regression model is evaluated using the following metrics:

- MAE (Mean Absolute Error): Measures the average absolute difference between actual and predicted sales.
- RMSE (Root Mean Squared Error): Measures prediction error while giving more weight to larger errors.
- R² Score: Measures how well the model explains variations in sales on the test dataset.

The actual evaluation results are generated when the notebook is executed.

8. How to Run the Project

1. Download or clone this repository.
2. Open `Sales_Prediction.ipynb` in Google Colab.
3. Upload `Advertising.csv` when prompted.
4. Run all the code cells in order.
5. Review the generated graphs and model evaluation results.
6. Modify the advertising expenditure values to test new predictions.

9. What I Learned

While working on this project, I gained practical experience in data cleaning, exploratory data analysis, data visualization, correlation analysis, Linear Regression, and model evaluation.

I also learned how advertising expenditure can be analyzed to understand its relationship with sales.

10. Conclusion

This project demonstrates how Python and Linear Regression can be used to predict sales from advertising expenditure.

The model provides estimated sales values based on the patterns in the dataset. These predictions can support analysis and planning, but they should not be treated as guaranteed future sales.

11. Future Improvements

- Experiment with other regression algorithms.
- Compare the performance of different models.
- Use additional business and customer data.
- Improve predictions with more relevant                        features.
- Develop an interactive application for sales prediction.