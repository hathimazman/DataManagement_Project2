# ✈️ Flight Delay and Cancellation Analysis, Analysis of Year 2006 Dataset

![plane](images/plane.jpg)

## 📌 Project Overview

This project presents a comprehensive data-driven analysis of flight delays and cancellations within the U.S. aviation industry. By leveraging historical flight performance data, it explores the impact of time, delay causes, airline operators, airports, and specific flight routes on overall punctuality and reliability. The analysis aims to uncover patterns, highlight operational bottlenecks, and provide actionable insights for airline companies, airport operators, policymakers, and travelers.

> This project utilizes the hadoop ecosystem with HIVE Database as a location for storing the dataset, and using HiveSQL to for ETL Process.

---

## 🎯 Objectives

- Identify temporal patterns in flight delays and cancellations (hourly, daily, monthly).
- Examine the frequency and severity of different delay causes (e.g., weather, carrier, NAS).
- Compare airline and airport performance based on cancellation and delay rates.
- Highlight problematic routes and assess contributing factors.
- Provide evidence-based recommendations to reduce disruptions and improve scheduling efficiency.

---

## 🧰 Tools & Technologies
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![HiveSQL](https://img.shields.io/badge/HiveSQL-yellow?logo=apache-hive&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-purple?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-teal?logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-lightgrey?logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Data-Kaggle-blue?logo=kaggle&logoColor=white)

- **Programming Language**: Python (Insights and Analysis), HiveSQL (ETL Process)
- **Data Analysis & Visualization**: pandas, numpy, matplotlib, seaborn
- **Statistical Testing**: scipy (e.g., t-tests)
- **Jupyter Notebook**: For interactive data exploration
- **Data Source**: [Data Expo 2009: Airline On Time Data](https://www.kaggle.com/datasets/wenxingdi/data-expo-2009-airline-on-time-data/data?select=1993.csv)

---

## 📊 Key Findings

- **Time Patterns**: Delays increase progressively throughout the day and peak in late afternoons/evenings. Tuesdays and spring months have the least delays, while Fridays and summer/holiday months have the most.
- **Delay Causes**: NAS-related delays are most frequent; weather delays are rare but longest; carrier issues are the primary reason for cancellations.
- **Airline & Airport Performance**: Major differences exist among airlines and airports. Telluride Regional and Hickory Municipal airports have consistently high cancellation rates.
- **Route Reliability**: Routes such as CVG–EWR and MSN–ORD exhibit high cancellation and delay rates, often due to systemic (NAS) or operational challenges.
- **Operational Insights**: Morning flights are more reliable; nighttime cancellations are minimal. Proactive schedule and resource management is critical.

---

## 📌 Recommendations

- **Airlines**: Optimize morning departure schedules and improve recovery planning to prevent cascading delays.
- **Airports**: Invest in infrastructure and optimize airspace use, particularly at high-delay locations.
- **Policy Makers**: Target NAS and weather resilience improvements in system-wide planning.
- **Travelers**: Prefer morning flights and avoid peak travel days (Fridays, holidays) for greater reliability.


