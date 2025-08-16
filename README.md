# -SCT_DS_2-
Perform data cleaning and exploratory data analysis (EDA) on a dataset of choice. For this task, I have used the Titanic dataset (Kaggle).  The goal is to:  Clean and preprocess the dataset (handle missing values, duplicates, etc.)  
The main objective of this task was to perform Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset (sourced from Kaggle).
The dataset provides passenger details such as age, gender, class, and survival status.
The aim was to uncover meaningful patterns and relationships between variables to better understand factors influencing passenger survival.


---

🧠 My Approach

🔹 Step 1: Data Loading and Understanding

Loaded the Titanic dataset into a Pandas DataFrame.

Performed an initial inspection using .info(), .describe(), and .isnull().sum() to identify data types, missing values, and basic statistics.


🔹 Step 2: Data Cleaning

To prepare the dataset for analysis, I applied the following steps:

Dropped irrelevant columns that do not add value to survival prediction:

PassengerId, Name, Ticket, Cabin


Handled missing values:

Filled missing Age values with median age (since age distribution is skewed).

Filled missing Embarked values with mode (most frequent embarkation port).


Verified data quality after cleaning to ensure no further inconsistencies remained.


🔹 Step 3: Exploratory Data Analysis (EDA)

Used Python libraries like Pandas, Seaborn, and Matplotlib to explore patterns:

📌 Overall Survival Distribution

Visualized how many passengers survived vs. did not survive.


👩‍🦰 Survival by Gender

Analyzed survival differences between male and female passengers.

Confirmed that females had a significantly higher survival rate.


🛳 Survival by Passenger Class (Pclass)

Explored survival rates across 1st, 2nd, and 3rd class.

Found that higher-class passengers had better chances of survival.


⚓ Survival by Embarkation Point (Embarked)

Compared survival rates of passengers who boarded at Cherbourg (C), Queenstown (Q), and Southampton (S).

Identified subtle differences in survival outcomes based on embarkation location.


🎂 Age Distribution among Survivors

Studied survival rates across different age groups.

Found higher survival rates among children compared to adults.


🔥 Correlation Heatmap

Created a heatmap to understand correlations between numerical variables.

Identified that Fare and Pclass had significant influence on survival.


🔄 Pairwise Relationships (Pairplot)

Used Seaborn’s pairplot to study interactions between features.

Helped in identifying combinations of variables influencing survival.



📝 Outcome

Through this task, I was able to:

✅ Strengthen my ability to clean real-world datasets, handle missing values, and drop irrelevant features.

✅ Apply EDA techniques to uncover key insights, such as how gender, class, and age influenced survival rates.

✅ Use visual storytelling to communicate findings effectively through clear and purposeful visualizations.

✅ Gain practical experience in correlation analysis and pairwise exploration to understand inter-variable relationships.
