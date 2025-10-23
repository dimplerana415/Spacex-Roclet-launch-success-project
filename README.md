---

# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 🌟 Project Overview

SpaceX has revolutionized space travel with the Falcon 9 rocket, which can reuse its first stage, drastically reducing launch costs. This project aims to predict whether the Falcon 9 first stage will land successfully using historical launch data. Accurate predictions can help SpaceX and stakeholders estimate mission costs, optimize planning, and enhance operational efficiency.

---

## 🎯 Problem Statement

SpaceX offers launches at approximately $62 million, while competitors charge over $165 million. This cost advantage comes from reusing the first stage. Predicting landing success is critical for reducing operational risks and ensuring cost-effective launches.

**Key Question:**

> Can we predict the success of a Falcon 9 first stage landing based on historical launch parameters?

---

## 🗂 Repository Structure

├── API-Data-Collection.ipynb          # Collects SpaceX launch data via API

├── Web-Scraping-DataCollection.ipynb  # Scrapes additional launch data from Wikipedia

├── Data-Wrangling.ipynb               # Cleans and preprocesses the data

├── EDA-SQL.ipynb                      # SQL-based Exploratory Data Analysis

├── EDA-with-Visualization.ipynb       # Visual EDA using Matplotlib, Seaborn, Plotly

├── Machine-learning-models.ipynb      # Builds and evaluates predictive models

├── Plotly_Dashboard.py                 # Interactive dashboard for insights

└── README.md                           # Project documentation

---

## 🧰 Tools & Technologies

Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn

Data Sources: SpaceX API, Wikipedia

Data Storage: SQLite

Visualization: Plotly Dash, Folium

Environment: Jupyter Notebook

---

## 🛠 Methodology

1. *Data Collection*

Fetched historical launch data from the SpaceX API.

Gathered additional data via web scraping from Wikipedia.

2. *Data Wrangling*

Cleaned and transformed raw data.

Handled missing values, outliers, and categorical encoding.

3. *Exploratory Data Analysis (EDA)*

Explored key patterns using SQL and Python visualizations.

Analyzed relationships between variables and landing outcomes.

4. *Model Building*

Developed machine learning models to predict landing success.

Evaluated models using metrics: accuracy, precision, recall, and F1-score.

5. *Dashboard Creation*

Built an interactive Plotly Dash dashboard to visualize launch data and predictions.


---

## 📈 Key Findings

Predictive Accuracy: 83.34%

Key Features Influencing Success: Launch site, booster version, payload mass, orbit type

Best Model: Logistic Regression, KNN, SVM


> These insights highlight the major factors affecting Falcon 9 landing outcomes and can guide future mission planning.

---

## 💻 How to Run the Project

1. Clone the repository:

git clone https://github.com/dimplerana415/Spacex-Roclet-launch-success-project.git
cd Spacex-Roclet-launch-success-project


2. Install dependencies:

pip install -r requirements.txt


3. Run the notebooks in order:

  1. API-Data-Collection.ipynb
  2. Web-Scraping-DataCollection.ipynb
  3. Data-Wrangling.ipynb
  4. EDA-SQL.ipynb
  5. EDA-with-Visualization.ipynb
  6. Machine-learning-models.ipynb


4. Launch the interactive dashboard:

python Plotly_Dashboard.py

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🔗 References

SpaceX API

Wikipedia - Falcon 9

IBM Data Science Capstone Guidelines

## Author

Dimple Rana |
Aspiring Data Scientist


---
