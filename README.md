Objective:
The goal of this project was to predict whether the SpaceX Falcon 9 rocket’s first stage would successfully land, based on parameters such as payload mass, booster version, orbit type, and launch site. This project was completed as part of the IBM Data Science Professional Certificate Capstone.

Project Overview:
The project began with data collection from the official SpaceX API, supplemented by web scraping for missing information. The collected data was cleaned to remove inconsistencies, handle missing values, normalize payload data, and encode categorical variables. Exploratory Data Analysis (EDA) was conducted to uncover patterns in launch success, such as bar charts showing landing success by site and booster version, scatter plots linking payload with orbit type, SQL queries to count success/failure outcomes and identify the first successful landing date (2015-12-22), and heatmaps to analyze correlations.

Visualizations were extended with a Folium interactive map plotting launch and landing sites, as well as a Plotly Dash dashboard for dynamic filtering by site, payload, and booster version. For predictive modeling, multiple machine learning algorithms were trained, including Logistic Regression, SVM, Random Forest, and Gradient Boosting. Hyperparameters were tuned using GridSearchCV, and model performance was evaluated with accuracy, precision, recall, and F1-score.

Key Results:

Random Forest and Gradient Boosting achieved the strongest predictive performance.

Critical predictors of landing success were Payload Mass, Booster Version, and Orbit Type.

Insights provide value for mission planning, helping SpaceX reduce risk and optimize reusability strategies.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash, SQL
