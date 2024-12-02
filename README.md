# Contaminated River Water Parameters Analysis

# Project Overview
This project analyzes the physico-chemical parameters of a polluted river in Buenos Aires to assess its water quality and identify potential sources of contamination. By leveraging a dataset from Kaggle, we perform data preprocessing, exploratory data analysis (EDA), hypothesis testing, and machine learning modeling to evaluate water quality trends and predict contamination levels.

Trello Board: https://trello.com/invite/b/674daf9e017562db7e6a6c57/ATTI97c8e45c33d0bff7c7ec741971cfc361B9AE654F/capstone-project

# Project Goals
1. Evaluate the current state of water quality by analyzing key physico-chemical parameters.
2. Investigate correlations between various parameters to identify potential pollution sources and their impact on water quality.
3. Test hypotheses related to the factors affecting water quality and determine their statistical significance.
4. Develop predictive models to forecast water quality under varying conditions, enabling better resource management.

# Dataset Information
Source: Ferran, N. (2023). River Water Parameters. Kaggle.

# Dataset Characteristics
Size: Contains multiple rows of measurements across different locations and time periods.
Features: Includes both numerical (e.g., pH, conductivity, dissolved oxygen) and categorical variables (e.g., water hardness classification).
Scope: Represents diverse physico-chemical characteristics essential for water quality assessment.

# Technologies Used
Programming Language: Python
Libraries:
Data Analysis: pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn
Statistical Testing: SciPy
Environment: Google Colab / Jupyter Notebook

# Key Components
1. Data Preprocessing
Handled missing values and outliers.
Converted date columns to a standardized format.
Encoded categorical features for compatibility with machine learning models.

2. Exploratory Data Analysis (EDA)
Visualized distributions and trends across months.
Generated correlation heatmaps to identify key relationships among variables.
Highlighted seasonal trends and patterns.

3. Water Quality Assessment
Conducted hypothesis testing to compare water quality indicators against reference standards.
Assessed contamination levels based on physico-chemical properties.

4. Predictive Modeling
Built machine learning models (e.g., Random Forest) to predict contamination levels.
Evaluated models using metrics like accuracy and feature importance analysis.

5. Insights and Recommendations
Highlighted parameters significantly impacting water quality.
Suggested actionable measures for environmental monitoring and remediation.

# How to Use
Clone the Repository:
bash
Copy code
git clone https://github.com/your-username/river-water-analysis.git
cd river-water-analysis
Install Required Libraries:

bash
Copy code
pip install -r requirements.txt
Run the Notebook: Open RiverWaterAnalysis.ipynb in Jupyter Notebook or Google Colab.

# Analyze Results:
View EDA visualizations and hypothesis test outputs.
Evaluate model predictions and feature importance.
Results
The analysis highlights critical water quality indicators like pH, conductivity, and dissolved oxygen.
Seasonal variations and industrial pollution were identified as major contributors to contamination.
The Random Forest model achieved high accuracy in predicting contamination levels, emphasizing the importance of physico-chemical features.
Contributions
This project was created and maintained by Carroll. Contributions and suggestions are welcome! Please feel free to submit issues or pull requests.

# References
See References and Sources section for detailed citations.


For further inquiries, contact [ctshabane@gmail.com].
