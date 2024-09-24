# app-pocalypse
**Studying Factors that Contribute to App-Churn on the Google Play store**

**Objective**: Developed a survival analysis model to predict the likelihood of app churn, defined as apps not being updated for over 6 months, using features like app category, price, content rating, and user reviews.

**Skills**: Data Preparation, Cox Proportional Hazard Model, Kaplan-Meier Estimator, Feature Engineering, Data Visualization, Survival Analysis

**Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn, Lifelines, StatsModels, Scikit-learn

**Approach**:

- Cleaned and preprocessed app data from the Google Play Store, handling variables such as size, installs, price, and categorical fields. Engineered features such as the time since last update to create the dependent variable for app churn.
- Conducted survival analysis using the Kaplan-Meier Estimator to compare the survival probability of free vs. paid apps, highlighting the likelihood of updates over time.
- Applied the Cox Proportional Hazard Regression Model to predict app churn, analyzing how factors like app category, price, and reviews influence the likelihood of updates.
- Evaluated model performance using the Concordance Index and assessed the model's proportional hazards assumptions to ensure its validity.

Results: Found that paid apps have a higher survival probability (likelihood of receiving updates), potentially due to developer investment. Additionally, content rating positively influenced app churn, highlighting important factors for app longevity.
