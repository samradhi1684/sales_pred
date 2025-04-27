# Sales Prediction Project (Data Science Assignment)
I am creating this project to showcase my foremost interest and skills in the position of Data Science Intern at GrowthLink. 
I am very grateful to have been given this opportunity.
This project focuses on building a robust Sales Prediction Model to forecast future sales using historical data. 
The process involves multiple stages, starting from data preprocessing to ensure the data is clean and structured for analysis. 
Utilized a Linear regression model to predict sales, with a focus on evaluating model performance through cross-validation and various evaluation metrics.

## Key features :
- **Data Preprocessing** : Handling missing values, dropping unnecessary columns and scaling features to improve model accuracy. A correlation heatmap was created to analyze relationships
between different features before modeling. This helped identify which variables were most strongly correlated with sales, guiding feature selection for the model.  
- **Modeling** : Applied Linear regression to predict sales and evaluated model using MSE and R-squared scores, and performed thorough cross-validation to ensure model's generalizability.
- **Detecting outliers** : Identifying outliers using boxplots and handling them to ensure extremes don't distort model's predictions.
- **Feature Importance** : After model training, we evaluated feature importance to identify the most significant factors influencing sales, providing valuable business insights.
- **Error Predictions** : we visualized the distribution of errors using a histogram, revealing that the errors were centered around zero, indicating that the model's predictions
were accurate and well-distributed.
- **Visualization of Predictions** : To further validate the model, we compared actual versus predicted sales using a scatter plot. The points aligned closely along a straight diagonal
line, confirming that the predicted sales were very close to the actual values.
- **Business Optimization** : Based on the model's predictions and insights, we proposed strategies for business optimization, including adjustments to pricing and marketing efforts to drive better sales outcomes.

## Usage
To use this project, follow the steps below to set it up on your local system. 
**Prerequisites** : Python 3.x, Jupyter Notebook, Required Libraries
jupyter notebook : pip install notebook
libraries : pip install numpy pandas matplotlib seaborn scikit-learn

**Setting up the project** :
1. Clone the repository : `git clone (https://github.com/samradhi1684/sales_pred.git)`
2. Navigate to the project folder
3. Start Jupyter notebook : `jupyter notebook` or `python -m notebook`
4. Run the notebook : open the sales.ipynb file in notebook and execute each cell. The notebook is organized with comments, visualizations and insights.

## Contact
For questions or feedback, feel free to reach out to [samradhi.s4@gmail.com](mailto:samradhi.s4@gmail.com)
