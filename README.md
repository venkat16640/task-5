task-5


🛳 Titanic Dataset Exploratory Data Analysis (EDA)
This project explores the Titanic passenger dataset using Python to uncover patterns and trends related to survival. It focuses on understanding relationships among variables like sex, passenger class, fare, age, and port of embarkation.

📁 Dataset Files

train.csv: Main dataset used for training and EDA
test.csv: Unlabeled test set for future predictions
gender_submission.csv: Benchmark for sample submission

📊 EDA Steps Completed

✅ Step A: Data Loading
Loaded the dataset using pandas.read_csv()
Previewed the structure using .info(), .describe()
Analyzed categorical values with .value_counts()

✅ Step B: Visualizations
Plotted using seaborn and matplotlib:
Pairplot to explore bivariate relationships
Heatmap to visualize correlations

✅ Step C: Relationship & Trend Identification
Analyzed relationships between Survived and:
Sex
Pclass
Age
Fare
Embarked
Observed strong patterns favoring females, first-class passengers, and high-fare ticket holders.

✅ Step D: Visualizations (Deep Dive)
Histograms of Age & Fare
Boxplots of Age and Fare by survival
Scatterplot of Age vs Fare colored by survival


✅ Step E: Observations
Documented insights from each visualization
Noted survival bias by gender, class, and embarkation


✅ Step F: Summary of Findings
Identified key features driving survival:
Sex, Pclass, and Fare
Highlighted trends, outliers, and skews


🧪 Tools Used
Python 🐍
pandas
seaborn
matplotlib
numpy
