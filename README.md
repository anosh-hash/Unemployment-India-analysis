# 📊 India Unemployment Analysis: Impact of COVID-19 on Employment Trends (2019–2020)

> Exploratory data analysis of India's unemployment rates (2019–2020),
> with a focus on the COVID-19 impact, regional disparities, and rural-urban divide.

---

## 📁 Repository Structure

```
├── Unemployment_in_India.csv         # Raw dataset (CMIE via Kaggle)
├── unemployment_analysis.ipynb       # Full EDA + visualization notebook
├── fig1_overview.png                 # National trend, COVID comparison, state rankings
├── fig2_rural_urban.png              # Rural vs Urban deep-dive
├── fig3_heatmap.png                  # State × Month unemployment heatmap
├── fig4_insights.png                 # Key findings & policy summary card
└── README.md
```

---

## 📌 Dataset

| Field | Details |
|---|---|
| **Source** | Centre for Monitoring Indian Economy (CMIE) |
| **Records** | 740 (28 states × Rural/Urban × Monthly) |
| **Period** | May 2019 – June 2020 |
| **Columns** | Region, Date, Frequency, Unemployment Rate (%), Employed, Labour Participation Rate (%), Area |

---

## 📈 Exploratory Questions

- How did unemployment change after the COVID lockdown?
- Which states were most affected?
- Did urban areas suffer more than rural areas?
- How did labour participation rates change?
- What policy lessons can be learned?

---

## 🔍 Key Findings

### 1. COVID-19 Shock
| Period | Mean Unemployment | Median Unemployment | Labour Participation Rate |
|---|---|---|---|
| **Pre-COVID** | 9.51% | 7.12% | 43.89% |
| **COVID-19** | 17.77% | 14.52% | 39.33% |

> 📌 COVID caused an **+8.3 percentage point surge** in average unemployment — nearly double the pre-pandemic baseline.

### 2. Peak Unemployment
- **76.74%** recorded during the COVID lockdown period (April–May 2020)
- Labour Participation Rate dropped sharply as discouraged workers exited the workforce

### 3. Rural vs Urban
- Urban unemployment is **consistently higher** than rural (driven by formal sector job losses)
- The urban-rural gap **widens sharply during COVID** as manufacturing/services collapsed
- Rural India was cushioned partly by MGNREGS (rural job guarantee scheme)

### 4. Regional Disparities
- States like **Tripura, Haryana, Jharkhand, Bihar** show chronically high unemployment
- Southern states (Kerala, Karnataka, Tamil Nadu) show relatively more stable rates
- The COVID shock was **unevenly distributed** — some states saw 5× normal rates

### 5. Seasonal / Cyclical Patterns
- Pre-COVID data shows **mild seasonal fluctuation** in rural areas (linked to agricultural cycles)
- COVID disrupted seasonal patterns, causing an unprecedented uniform spike in April–May 2020

---

## 💡 Policy Implications

1. **Urban informal sector** workers are the most vulnerable — targeted direct benefit transfers needed during economic shocks.
2. **MGNREGS expansion** to urban areas could act as a buffer during crises.
3. **State-level response variation** suggests a need for Centre-State coordination frameworks.
4. The drop in Labour Participation Rate indicates **hidden unemployment** (discouraged workers) — headline unemployment numbers understate the real distress.
5. Post-COVID recovery investments should prioritize **labour-intensive sectors**: construction, MSMEs, agro-processing.

---

## 🛠️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/unemployment-india-analysis.git
cd unemployment-india-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Run the analysis
Open unemployment_analysis.ipynb in Jupyter Notebook or Google Colab and run all cells.
```

---

## 📊 Visualizations

### Figure 1 – National Overview
- Monthly unemployment trend with COVID lockdown marker
- Pre-COVID vs COVID box plot comparison
- Top & bottom 10 states by average unemployment
- Labour Participation Rate over time

<img width="2367" height="1517" alt="fig1_overview" src="https://github.com/user-attachments/assets/81b41602-1b03-4214-a1c6-43cf37b7298f" />


### Figure 2 – Rural vs Urban
- Side-by-side time series comparison
- Violin plot showing distribution shifts

<img width="2372" height="885" alt="fig2_rural_urban" src="https://github.com/user-attachments/assets/d32697f4-b812-4ca8-ac17-c3aa5bb7dafc" />


### Figure 3 – State × Month Heatmap
- 28 states across all months — reveals geographic concentration of the COVID shock

<img width="2422" height="1067" alt="fig3_heatmap" src="https://github.com/user-attachments/assets/7bb6bdb1-479a-4b44-853a-61e8c94475c2" />


### Figure 4 – Key Insights Card
- Summary of all major findings and policy recommendations

<img width="1425" height="881" alt="fig4_insights" src="https://github.com/user-attachments/assets/15135a0c-86a0-4086-9fb2-2a07faa7312a" />


---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-lightblue)

---

## 📜 License
MIT — free to use and modify.
