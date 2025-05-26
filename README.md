# Data-science
#Titanic datset EDA
data set link= 
"https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
Titanic Dataset – Exploratory Data Analysis (EDA)
This project performs an in-depth exploratory data analysis (EDA) on the Titanic dataset using Python, Pandas, and visualization libraries like Matplotlib and Seaborn. The goal is to clean the data, explore key patterns, and extract actionable insights.

📁 Dataset
The dataset used is the classic Titanic Dataset, available publicly for machine learning and data science practice.

It includes features like:

Passenger Age, Gender, Class, Fare

Survival status (0 = No, 1 = Yes)

🧪 EDA Process
1. Data Loading
Loaded dataset directly from a GitHub CSV link using Pandas.

2. Data Cleaning
Filled missing Age values using the median.

Filled missing Embarked values using the mode.

Dropped the Cabin column due to high missing values.

Removed duplicate rows.

Detected and removed outliers from the Age column using the IQR method.

3. Visualizations
Bar Charts: Passenger count by Gender, Class, and Survival.

Histograms: Distribution of Age and Fare.

Correlation Heatmap: Displayed correlations among numeric variables to understand relationships.

4. Insights
Most passengers were male and in 3rd class.

Females and 1st class passengers had higher survival rates.

Fare is positively correlated with survival and class.

Sex, Pclass, and Fare are strong indicators for survival.

Sample Visualizations
Countplots for categorical features

Histograms for age and fare

Correlation heatmap

 Technologies Used:
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

