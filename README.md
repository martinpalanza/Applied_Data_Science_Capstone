# Applied_Data_Science_Capstone
Colab Notebooks and scripts .py from the course IBM Applied Data Science Capstone
# SpaceX Falcon 9 Landing Prediction Project

## 🚀 Project Overview
This project aims to predict the success of the Falcon 9 first-stage landing. By predicting the likelihood of a successful landing, we can estimate the cost of a launch. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each. Much of the savings is because SpaceX can reuse the first stage.

## 📊 Repository Structure
The project is organized into sequential steps to ensure a professional data science workflow:

1.  **Data Collection (API):** Fetching real-time launch data from the SpaceX API.
2.  **Data Collection (Web Scraping):** Extracting Falcon 9 launch records from Wikipedia using BeautifulSoup.
3.  **Data Wrangling:** Data cleaning, handling missing values, and feature engineering.
4.  **EDA with SQL:** Performing relational analysis to identify trends and patterns.
5.  **EDA with Visualization:** Using Matplotlib and Seaborn for statistical insights.
6.  **Geospatial Analysis:** Interactive mapping of launch sites and landing outcomes using Folium.
7.  **Interactive Dashboard:** A Python script (`.py`) running a Dash application for real-time scenario simulation.
8.  **Machine Learning Prediction:** Training and tuning models (SVM, KNN, Logistic Regression, Decision Trees) using GridSearch.
9.  **Dataset:** The processed `.csv` file used for the final models.
10. **Final Presentation:** A comprehensive PDF report summarizing the methodologies and findings.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash.
* **Tools:** Jupyter Notebooks, BeautifulSoup (Web Scraping), SQL (SQLite/IBM DB2).

## 📈 Key Results
* **Model Accuracy:** Achieved a peak accuracy of **83.3%** across multiple models.
* **Optimization:** Hyperparameter tuning performed via **GridSearchCV** to ensure model robustness.
* **Business Impact:** Developed a tool capable of assessing financial risks based on payload mass and orbit types.

## 📧 Contact
Martín Uriel Palanza Toledo - linkedin.com/in/martín-uriel-palanza-toledo-882241247
