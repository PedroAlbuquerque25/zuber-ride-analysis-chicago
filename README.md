# 🚕 Zuber Ride Analysis — Chicago

## 📌 Project Overview
This project performs a comprehensive data analysis for **Zuber**, a new ride-sharing company launching in **Chicago**. 

The primary goal is to identify **passenger behavior patterns**, analyze competitor data, and **evaluate the impact of external factors**, such as weather conditions, on trip frequency and duration.

The analysis was conducted using data extracted via SQL and processed using Python to drive strategic insights for Zuber's market entry.

---

## 🎯 Objectives
* Analyze trip volumes across competing taxi companies.
* Identify passenger preferences and top destinations (neighborhoods) within the city.
* Evaluate the influence of weather conditions on ride demand.
* Conduct statistical hypothesis testing to validate the impact of climate factors.

---

## 🧪 Hypothesis Testing
> **Null Hypothesis (H₀):** The average duration of rides from the Loop to O'Hare International Airport does not change on rainy Saturdays.  
> **Alternative Hypothesis (H₁):** The average duration of rides from the Loop to O'Hare International Airport differs on rainy Saturdays.

---

## 📂 Project Structure

```
zuber-ride-analysis-chicago/
├── datasets/
│   ├── trips.csv
│   └── neighbourhoods.csv
├── notebook/
│   └── notebook.ipynb
├── environment.yml
├── .gitignore
└── README.md
```

---

## 🛠️ Tech Stack
- **Python 3.10**
- **Pandas — Data manipulation and analysis.
- **Matplotlib & Seaborn** — Data visualization.
- **SciPy — Statistical hypothesis testing.
- **Jupyter Notebook** — Interactive environment.
- **Conda** — Environment management.
- **Git & GitHub** — Version control.

---

## 🚀 🚀 How to Run

### 1️⃣ Clone the repositoryo
```bash
git clone https://github.com/PedroAlbuquerque25/zuber-ride-analysis-chicago.git
cd zuber-ride-analysis-chicago

2️⃣ Set up the Environment (Conda)
conda env create -f environment.yml
conda activate zuber-env

3️⃣ Launch the Notebook
jupyter notebook
# Open notebook/notebook.ipynb
```

---

## 📊 Key Findings & Insights
* Market Dominance: Identified the leading taxi companies by trip volume, highlighting market concentration.
* Top Destinations: Mapped the most popular drop-off locations, with the "Loop" being the primary hub.
* Weather Impact: Statistical evidence (Mann-Whitney U test) confirmed that bad weather significantly affects trip durations.
* Strategic Support: Insights provided to support Zuber's marketing and operational planning for 2017.


---

👤 Autor
Pedro Albuquerque Data Analyst | Business Intelligence
---

## 🤝 Contato
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phaa/)

