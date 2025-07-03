# 🗳️ Elections Ad Spending Analysis with Python

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-Data%20Analysis-%23150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Plots-%233B4D98?logo=plotly&logoColor=white)](https://plotly.com/)

> **Analyze, visualize, and understand political ad spending across Indian states using open data and Python!**

---

## 📊 Project Overview

This project explores the spending patterns of political advertisers during elections in India, merging Facebook ad data, geographic locations, and polling results to uncover insights about ad distribution, effectiveness, and regional trends.

- **Data Sources**:  
  - Advertisers’ spending and activity  
  - State-wise ad spend  
  - Election results by state and constituency

- **Key Features**:  
  - Data cleaning and merging for multi-source datasets  
  - State-level ad spend analysis  
  - Interactive data visualizations with Plotly  
  - Reproducible code in Jupyter Notebook

---

## 🏁 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/PGaraiya/Elections-Ad-Spending-Analysis-with-Python.git
   cd Elections-Ad-Spending-Analysis-with-Python
   ```

2. **Install required packages**
   ```bash
   pip install pandas plotly
   ```

3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook "Elections Ad Spending Analysis with Python.ipynb"
   ```

4. **Explore and modify the notebook**  
   - Update data sources (CSV files) as needed
   - Visualize ad spending by state
   - Experiment with your own analysis!

---

## 🧑‍💻 Core Workflow

1. **Import Datasets**  
   - Load advertisers, locations, and election results CSVs

2. **Clean & Merge Data**  
   - Standardize state names  
   - Merge results and location tables on state

3. **Analyze Spending**  
   - Aggregate and visualize total ad spend by state

4. **Visualize Insights**  
   - Generate interactive charts with Plotly  
   - Explore patterns between ad spend and election outcomes

---

## 📑 Example Outputs

| State                  | Total Ad Spend (INR) | Total Votes | Polled (%) |
|------------------------|---------------------:|------------:|-----------:|
| Andhra Pradesh         | 100,819,732          | 10,000,000  | 80.2       |
| Maharashtra            | 75,000,000           | 20,000,000  | 67.5       |
| ...                    | ...                  | ...         | ...        |

> _Bar charts and interactive visuals available in the notebook!_

---

## 📂 Data Files

- `advertisers.csv` – Details and spending by political advertisers
- `locations.csv` – State-wise ad spending
- `results.csv` – Election results per state and constituency

---

## 🚀 Built With

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [Jupyter Notebook](https://jupyter.org/)

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bugfixes, or new analyses.

---

## 📜 License

MIT License.  
Feel free to use, modify, and share!
