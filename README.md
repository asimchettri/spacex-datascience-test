Objective:
To predict whether the SpaceX Falcon 9 rocket’s first stage will successfully land, based on launch parameters such as payload mass, booster version, orbit type, and launch site.

Key Steps:

Data Collection: Retrieved launch records from the SpaceX API
 and performed supplementary web scraping.

Data Wrangling: Cleaned inconsistencies, handled missing values, normalized payload data, and applied one-hot encoding to categorical features.

Exploratory Data Analysis (EDA):

Bar charts: landing success by site and booster version.

Scatter plots: payload vs. orbit type.

SQL queries: success/failure counts, first successful landing date (2015-12-22).

Heatmaps: feature correlation analysis.

Visualization:

Folium interactive map of launch & landing sites.

Plotly Dash dashboard for interactive exploration (filters for site, payload, booster).

Modeling:

Trained Logistic Regression, SVM, Random Forest, and Gradient Boosting models.

Optimized using GridSearchCV.

Evaluated with accuracy, precision, recall, and F1-score.

Results:

Random Forest and Gradient Boosting performed best.

Critical predictors: Payload Mass, Booster Version, Orbit Type.

Insights help optimize SpaceX mission planning and reduce risk.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash, SQL.
