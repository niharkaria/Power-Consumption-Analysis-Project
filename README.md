# 🔌 Tetouan City Power Consumption Analysis

## 📊 Project Overview

This project involves an in-depth analysis of electrical power consumption in Tetouan City. By examining temporal usage trends and external influencing factors (such as temperature and humidity), we aim to uncover actionable insights for optimizing power distribution and consumption efficiency.

---

## 🎯 Objective

- Analyze hourly power consumption across three distribution zones.
- Study the impact of meteorological factors (temperature, humidity) on electricity usage.
- Visualize patterns and trends using Python data science tools.
- Generate business insights to inform urban planning and power management strategies.

---

## 🗃️ Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Tetouan+City+power+consumption)
- **Description**:
  - **Time**: Hourly records from January to December.
  - **Features**:
    - `DateTime`
    - `Zone1 Power Consumption`
    - `Zone2 Power Consumption`
    - `Zone3 Power Consumption`
    - `Temperature`
    - `Humidity`
  - **Size**: ~34992 rows, 6 columns

---

## 🧰 Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn`, `plotly` – Data visualization
  - `scikit-learn` – Data preprocessing and metrics
  - `tensorflow.keras` – Deep learning (LSTM, GRU models)
  - `datetime` – Time-based feature extraction

---

## 🔍 Exploratory Data Analysis (EDA)

Key steps:
- Checked for missing/null values and handled anomalies
- Parsed and extracted temporal features (hour, month, day)
- Compared power consumption patterns across different zones
- Investigated correlation between weather (temperature, humidity) and power usage

---

## 📈 Key Insights

- **Zone-wise Usage**: Zone 1 consistently showed higher consumption than Zones 2 and 3.
- **Daily Pattern**: Power usage peaks during working hours and drops late at night.
- **Seasonal Effect**: Increased usage during extreme temperatures indicates weather-driven consumption behavior.
- **Weather Correlation**:
  - Higher **temperature** → Increased **power consumption** (likely due to AC usage).
  - Higher **humidity** also showed a moderate positive correlation.

---

## 🤖 Modeling

Implemented deep learning models:
- **LSTM**: Captures long-term temporal dependencies in power consumption data.
- **GRU**: Lightweight alternative to LSTM, efficient and faster to train.

---

## 📌 Possible Extensions

- Further hyperparameter tuning of LSTM/GRU models
- Deploy dashboards with Power BI or Streamlit
- Perform zone clustering based on load patterns

---

## 📁 Folder Structure

```
.
├── Power_Consumption_Analysis_Project.ipynb
├── README.md
├── dataset/
│   └── Tetuan City power consumption.csv
├── outputs/
│   ├── graphs/
│   └── cleaned_data.csv
```

---

## 💡 Conclusion

This analysis helps stakeholders (e.g., city planners, power grid managers) understand consumption trends, enabling smarter energy management in urban environments.

---

## 🧑‍💻 Author

**Name**: Nihar Karia
[LinkedIn](https://www.linkedin.com/in/nihar-karia) | [GitHub](https://github.com/niharkaria)