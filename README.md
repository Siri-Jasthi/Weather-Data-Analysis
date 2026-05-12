# 🌦️ Seattle Weather Data Analysis - By Siri Jasthi

## 📌 Project Overview

This project analyzes historical weather data from Seattle to uncover patterns, trends, and insights related to precipitation, temperature, wind, and weather conditions. The analysis is performed using Python with data visualization techniques to better understand weather behavior.

---

## 📂 Dataset

* Source: Kaggle – *Seattle Weather Dataset*
* Features include:

  * `date` – Date of observation
  * `precipitation` – Rainfall amount
  * `temp_max` – Maximum temperature
  * `temp_min` – Minimum temperature
  * `wind` – Wind speed
  * `weather` – Weather condition (rain, sun, snow, etc.)

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas – Data manipulation
* NumPy – Numerical operations
* Matplotlib & Seaborn – Data visualization
* Plotly – Interactive visualizations

---

## 🔍 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Created DataFrame for structured analysis

### 2. Data Exploration

* Checked dataset structure using `.info()` and `.describe()`
* Identified missing values
* Explored numerical and categorical features separately

### 3. Data Cleaning

* Converted `date` column to datetime format
* Handled missing values using `.dropna()`

### 4. Data Analysis & Visualization

* Scatter plots to analyze relationships (e.g., precipitation vs weather)
* Pie charts to visualize distribution of weather conditions
* Heatmaps for feature relationships
* Histograms for wind distribution
* Interactive charts using Plotly

---

## 📊 Key Insights

* Weather conditions show clear variation based on precipitation levels
* Temperature ranges differ significantly across weather types
* Wind distribution provides insights into seasonal patterns
* Certain weather conditions dominate the dataset

---

## 📈 Visualizations Included

* Scatter plots
* Pie charts
* Heatmaps
* Histograms
* Interactive Plotly graphs

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

3. Run the notebook:

   * Open in Jupyter Notebook or VS Code
   * Execute all cells

---

## ⚠️ Notes

* Dataset is not included due to size limits
* Download from Kaggle and update the file path:

  ```python
  pd.read_csv('path_to_dataset.csv')
  ```

---

## 💡 Future Improvements

* Add predictive modeling (ML models)
* Perform time-series analysis
* Deploy dashboard using Streamlit or Power BI

---

## 👤 Author

**Shirisha Jasthi**

---

## ⭐ If you found this useful

Give this repo a star ⭐ and feel free to fork it!
