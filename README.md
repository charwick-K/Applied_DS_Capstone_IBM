# 🚀 SpaceX Falcon 9 Landing Prediction – Capstone Project

## 📌 Project Overview
This is the final capstone project for the IBM Data Science Professional Certificate. It applies data science techniques to predict whether the SpaceX Falcon 9 first stage will land successfully, thereby estimating launch cost efficiency.

## 🎯 Objective
Analyze launch data to understand key factors affecting Falcon 9 first-stage recovery and build binary classification models to predict landing success.

---

## 📁 Project Structure
- `data_collection.ipynb` – Collects data via SpaceX REST API and Wikipedia scraping.
- `data_wrangling.ipynb` – Cleans and prepares the dataset with feature encoding.
- `EDA_visualization.ipynb` – Performs SQL-based and visual exploratory analysis.
- `interactive_visuals.ipynb` – Builds dashboards with Folium and Plotly Dash.
- `modeling.ipynb` – Implements and evaluates classification algorithms.

---

## ⚙️ Execution Methodology

### 1. 📡 Data Collection
- SpaceX REST API used to gather official launch data.
- Web scraping from Wikipedia for historical launch details.

### 2. 🧹 Data Wrangling
- Removed irrelevant entries and filled missing values.
- Applied One-Hot Encoding to convert categorical variables.

### 3. 📊 Exploratory Data Analysis (EDA)
- Used SQL queries and visual tools (Matplotlib, Seaborn) to examine relationships.
- Analyzed the impact of payload mass, orbits, and site on landing success.

### 4. 🌐 Interactive Visualization
- Created geographical maps with **Folium**.
- Built interactive dashboards with **Plotly Dash** to explore trends dynamically.

### 5. 🤖 Predictive Modeling
- Trained and tuned models such as Logistic Regression, Random Forest, and SVM.
- Evaluated performance using accuracy, precision, recall, and F1-score.

---

## 🧪 Development Environment

To run this project locally, follow these steps:

### 🔧 JupyterLab Setup
1. Ensure you have Python 3.7+ installed.
2. Install JupyterLab:
   ```bash
   pip install jupyterlab
   jupyter lab
   ```
3. Open notebooks in JupyterLab for execution.

### 📦 Required Libraries
Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn folium plotly scikit-learn requests beautifulsoup4 dash
```

Alternatively, create a virtual environment:
```bash
python -m venv spacex_env
source spacex_env/bin/activate  # For Linux/macOS
spacex_env\Scripts\activate     # For Windows
pip install -r requirements.txt
```

---

## 💡 Research Benefits
- Predicts cost-saving outcomes based on recoverability.
- Provides insights into operational patterns over time.
- Aids commercial space forecasting and strategic planning.

---

## 📌 Final Outcome
A robust machine learning pipeline capable of predicting the reusability of Falcon 9 rockets, supported by interactive dashboards and clean datasets.

---

## 👨‍💻 Author
**Kondru Charwick Hamesh** – IBM Data Science Professional Certificate Graduate
