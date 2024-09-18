Side Effect Data Analysis and Preprocessing

Author
Muhammed Sefa Akyüz
akyuzsefa8@gmail.com



Project Overview

This project focuses on analyzing and preprocessing a dataset related to drug side effects. The dataset contains information such as patient demographics, medications used, and reported side effects. The main objectives of the project are:

Perform Exploratory Data Analysis (EDA) to understand the structure of the data, identify missing values, and explore relationships between variables.
Conduct Data Preprocessing by handling missing values, encoding categorical variables, detecting and removing outliers, scaling numerical features, and performing feature engineering.



How to Run the Code

To run the project, follow these steps:

Clone the repository:
git clone https://github.com/Sefasola/Pusula_MuhammedSefa_Akyuz.git


Navigate to the project directory:
cd Pusula_MuhammedSefa_Akyuz

Install the required Python packages:
pandas==1.3.3
matplotlib==3.4.3
seaborn==0.11.2
scikit-learn==0.24.2
missingno==0.5.0


Run the pipeline:
python CaseStudy.py



Project Steps

1. Exploratory Data Analysis (EDA)
We begin by inspecting the structure and distribution of the dataset using descriptive statistics. Various visualizations, such as histograms and scatter plots, are used to understand data patterns. Missing values are identified and handled appropriately.

2. Data Preprocessing
Missing values are filled using appropriate strategies (mean for numerical values, most frequent for categorical values).
Categorical variables are encoded using One-Hot Encoding.
Outliers are detected and removed using the IQR method.
Numerical variables are scaled using MinMaxScaler.
New features such as age (calculated from the birthdate) and drug usage duration are engineered.
3. Output
The cleaned and preprocessed dataset is ready for further machine learning tasks.




Results

After completing the data preprocessing steps, the dataset is free from missing values, outliers are handled, and useful features have been engineered. The dataset is now suitable for building machine learning models.

