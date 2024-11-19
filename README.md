# Project Title: Predictive Analysis of SpaceY Rocket Launch Success

> Description:
This project analyzes the success rates of SpaceX's rocket launches using data science techniques. With reusable rocket technology revolutionizing the space industry, the analysis aimed to uncover key factors influencing successful landings. The project leveraged Python for data collection, preprocessing, visualization, and machine learning to derive insights and predictions.

## Key Highlights:

* Data Collection:
Data was sourced from the SpaceX API and Wikipedia pages using Python libraries (requests and BeautifulSoup).
Cleaned and formatted data into structured Pandas DataFrames for analysis.

* Data Wrangling and Feature Engineering:
Used Pandas to handle missing values and generate new features, such as a binary "Class" column to represent landing success (0 = failure, 1 = success).

* Exploratory Data Analysis (EDA):
Employed SQL and Python libraries like matplotlib and seaborn to explore relationships between features such as launch site, payload mass, orbit type, and success rates.
  * Launch site and orbit type were significant predictors of success.
  * Payload mass played a critical role, with heavier payloads more likely to succeed under specific conditions.
  * The most successful launches were associated with the KSC LC-39A launch site.

* Machine Learning Models:
Built and evaluated predictive models using scikit-learn, including: Logistic Regression, Support Vector Machines, Decision Trees and K-Nearest Neighbors, while conducting hyperparameter tuning with Grid Search to optimize model performance.

* Visualization and Dashboards:
Developed an interactive dashboard using Plotly Dash to allow users to filter data by launch site, visualize success rates, and explore payload and orbit relationships.

## Results:
Logistic Regression, SVM, and Decision Trees showed similar performance with high accuracy in predicting successful landings.
Interactive tools and visualizations provided actionable insights into launch characteristics and trends.

## Technologies Used:
Python, Pandas, Matplotlib, Seaborn, SQL (sqlite3), Folium, Plotly Dash, scikit-learn
