# Project: SpaceX Falcon 9 Predictive Analytics for Launch Cost Optimization
**IBM Data Science Professional Certificate | Capstone Project**

## Executive Summary
This project develops a complete machine learning pipeline to predict the landing success of the Falcon 9 first stage. By accurately predicting landing outcomes, we can determine the price of a launch. SpaceX can reuse the first stage, which results in a cost saving of over $100 million compared to other providers who cannot recover their rocket stages.

## Strategic Objectives
* **Data Acquisition:** Utilize REST APIs and Web Scraping (BeautifulSoup) to compile a comprehensive launch dataset.
* **Data Engineering:** Perform data cleaning, feature engineering, and SQL-based analysis to identify key variables.
* **Exploratory Data Analysis (EDA):** Leverage geospatial mapping (Folium) and interactive dashboards (Plotly Dash) to visualize success patterns.
* **Machine Learning:** Train and evaluate multiple classification models (SVM, KNN, Logistic Regression, Decision Trees) to optimize prediction accuracy.

## Technical Stack
* **Languages:** Python 3.9+
* **Data Processing:** Pandas, NumPy, SQL (IBM DB2)
* **Visualization:** Folium, Plotly Dash, Matplotlib, Seaborn
* **Modeling:** Scikit-Learn (GridSearchCV for hyperparameter tuning)

## Repository Structure
* **01_Data_Collection:** API Requests and BeautifulSoup Scraping
* **02_Data_Wrangling:** Null handling and Feature Engineering
* **03_EDA_SQL:** Database queries for landing statistics
* **04_EDA_Visualization:** Statistical plotting and trend analysis
* **05_Interactive_Map:** Folium Geospatial Launch Site Analysis
* **06_Dashboard:** Plotly Dash application
* **07_Predictive_Analysis:** Machine Learning model comparison

## Results and Findings
* **Site Analysis:** Launch site KSC LC-39A demonstrated the highest success rate among all tested sites.
* **Payload Correlation:** Launch success is statistically higher for payloads within the 2,000kg to 6,000kg range.
* **Model Performance:** The Support Vector Machine (SVM) achieved an accuracy of 83.3% on the test set.

## Installation and Usage
1. **Clone the repository:** `git clone https://github.com/youssefHosni/SpaceX-Landing-Prediction.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Execute Analysis:** Run the Jupyter notebooks in numerical order to replicate the full pipeline.

## Contact
