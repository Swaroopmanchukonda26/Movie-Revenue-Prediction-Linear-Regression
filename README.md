# Movie Box Office Revenue Prediction & Linear Regression

An end-to-end data analytics and predictive machine learning project investigating the relationship between film production budgets and global box office gross returns using Seaborn and scikit-learn.

## 🚀 Key Architectural Discoveries
* **The Return Profile:** Modern-era blockbuster films yield an estimated **$3.12** in worldwide box office revenue for every additional $1 spent on production.
* **The High-Risk Boundary:** Exploratory data filtering reveals that a massive **37.2%** of movies fail to recoup their production budgets at the box office.
* **Model Goodness of Fit:** A univariate linear regression model explains **55.8%** of the variance in modern film revenue based purely on a single feature (Production Budget).

## 🛠️ Data Science Toolkit Used
* **Languages & Platforms:** Python, Google Colab
* **Exploration & Cleaning:** Pandas (`.query()`, `pd.to_datetime()`, `.describe()`)
* **Feature Engineering:** Floor Division (`//`) to segment movie timelines into neat generation decades.
* **Visualizations:** Seaborn (`sns.scatterplot`, `sns.regplot`) to map multi-dimensional 3D bubble charts and linear trends.
* **Machine Learning:** Scikit-Learn `LinearRegression` engine to calculate parameters ($\theta_0$, $\theta_1$) and handle predictive inference strings.
