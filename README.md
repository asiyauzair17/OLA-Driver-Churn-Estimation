🚕 Ola Driver Churn Estimation Using Ensemble Machine Learning

Ola is one of India’s leading ride-hailing platforms, connecting millions of riders with drivers through its mobile application and website. Driver retention is a critical business challenge for Ola, as high attrition directly impacts service availability, customer satisfaction, and operational costs. This project addresses the problem of predicting driver churn by leveraging historical driver-level data and advanced machine learning techniques.

The objective of this project is to build a robust predictive system that determines whether a driver is likely to leave the platform based on demographic, performance, income, and engagement-related features. The dataset contains monthly driver information for the years 2019 and 2020, capturing both static and time-dependent attributes.

🔍 Exploratory Data Analysis (EDA)

The project begins with an extensive exploratory data analysis, where the structure, size, and data types of the dataset are examined. Statistical summaries are generated to understand central tendencies and variability. Univariate and bivariate analyses are performed to uncover relationships between driver attributes such as age, income, ratings, business value, and churn behavior.

🧹 Data Preprocessing & Feature Engineering

Data preprocessing includes:

Converting date-related columns into appropriate datetime formats

Handling missing values using KNN Imputation

Aggregating monthly records to the driver level to remove redundancy

Feature engineering plays a crucial role and includes:

Identifying increases in quarterly ratings

Detecting monthly income growth

Creating the target variable to indicate driver churn based on the last working date

Categorical variables are encoded, correlations among features are analyzed, class imbalance is treated, and numerical features are scaled to prepare the dataset for modeling.

🤖 Model Building Using Ensemble Learning

To improve predictive accuracy and generalization, multiple ensemble learning techniques are implemented:

Bagging

Boosting (Gradient Boosting and XGBoost with hyperparameter tuning)

Stacking

These models are well-suited for handling complex patterns and imbalanced datasets.

📊 Model Evaluation & Insights

Model performance is evaluated using classification reports and AU-ROC curves. Comparative analysis helps identify the best-performing model and key factors influencing driver attrition. The insights derived from this project can support strategic decisions aimed at improving driver retention.

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn
