README.md

## US Nurse Attrition Prediction Project

Nurse attrition in the US healthcare system is currently at an unprecedented high. This issue is a major area of focus, particularly for hospitals.

### Dataset Overview
This dataset contains employee and company data that can be useful for supervised machine learning, unsupervised machine learning, and analytics. The dataset includes whether an employee left the company (attrition) as a target variable that can be used.

The data is synthetic and based on the IBM Watson dataset for employee attrition. The employee roles and departments have been altered to reflect the healthcare industry. Additionally, the known outcomes for some employees have been changed in order to help improve the performance of machine learning models.

### Methodology
The project involved comprehensive exploration, model training, and evaluation. Here's an overview of the methodology used:

1. **Exploratory Data Analysis (EDA)**:
   - Univariate Analysis: Utilized histograms, subplots, pie charts, and bar charts to visualize the distribution of numerical and categorical variables.
   - Bivariate Analysis: Explored relationships between individual features and the target variable.
   - Multivariate Analysis: Employed pair plots and heatmaps to visualize relationships between all numerical columns and the correlation matrix.

2. **Model Training and Testing**:
   - Model Selection: Employed K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Logistic Regression, and Decision Tree algorithms.
   - Evaluation Metrics: Used recall, F1-score, and precision to assess model effectiveness.
   - Training-Testing Split: Divided the data into a training set (70%) and a testing set (30%) for unbiased evaluation.
   - SVM Emergence: Support Vector Machine (SVM) was identified as the best performing model based on evaluation metrics.

3. **Feature Engineering**:
   - Incorporated feature selection techniques using the "k-best" method to identify the most relevant features.
   - Retrained the SVM model with selected features to improve efficiency and accuracy.

4. **Deployment with Streamlit**:
   - Utilized Streamlit to deploy the predictive model, allowing users to input employee data and receive attrition risk predictions.

### Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit

### Recommendations
- Proactive Retention Strategies: Utilize predictive models to identify at-risk employees and implement targeted retention initiatives.
- Continuous Monitoring: Regularly assess nurse attrition patterns and adjust strategies accordingly.
- Employee Engagement: Focus on improving job satisfaction and work-life balance to reduce attrition rates.


### How to Clone the Repository
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/segunumoru1/US-Nurse-Attrition-Analytics-and-Prediction.git
   ```
2. Navigate to the project directory:
   ```
   cd nurse-attrition-prediction
   ```
3. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

### Libraries Used
- pandas
- numpy
- requests
- pickle
- json
- matplotlib
- seaborn
- scikit-learn
- streamlit

### Streamlit App
[Click to Predict US Nurse Attrition Rate](https://segunumoru1-us-healthcare-employee-attrition-analyti-app-tsc7ex.streamlit.app/)


## License
This project is licensed under the [MIT License](LICENSE).

