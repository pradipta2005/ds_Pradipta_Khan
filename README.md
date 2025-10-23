
# 📊 Trader Behavior vs Market Sentiment Analysis

### Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed).

---

## 🧠 Project Overview

This project explores the intricate relationship between **trader behavior** and **market sentiment**, identifying patterns that can enhance smarter trading strategies.  
It combines **trading data from Hyperliquid** with **market sentiment indicators** to uncover trends in profitability, risk exposure, and leverage decisions under varying emotional market states (fear vs greed).

---

## 🧩 Key Objectives

- Understand how trader behavior correlates with market sentiment.  
- Identify behavioral signals that precede shifts in market trends.  
- Visualize and quantify trading patterns such as:
  - Profit/Loss trends
  - Leverage behavior
  - Volume dynamics
  - Sentiment divergence zones

---

## 🧰 Technologies Used

- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn** *(if feature correlations or models are applied)*
- **Datetime** and **Feature Engineering tools**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/trader-sentiment-analysis.git
cd trader-sentiment-analysis
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate    # for macOS/Linux
venv\Scripts\activate       # for Windows
```

### 3. Install Dependencies


```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

### 4. Open the Notebook
```bash
jupyter notebook notebook_1.ipynb
```

---

## 📈 Workflow

1. **Data Preprocessing** – Load and clean raw trading and sentiment datasets.  
2. **Merging Datasets** – Align trading data with sentiment scores based on timestamps.  
3. **Feature Engineering** – Derive metrics like:
   - Daily Profit/Loss
   - Trade Volume
   - Leverage Ratios
   - Sentiment Indicators  
4. **Exploratory Data Analysis (EDA)** – Generate plots showing:
   - Correlation between risk and sentiment  
   - Behavior shifts during extreme fear/greed periods  
   - Distribution of profitability across traders  
5. **Insights & Conclusions** – Summarize patterns that can guide better trading decisions.

---

## 🪄 Output Highlights

- Interactive visualizations showing trading trends under various sentiment conditions.  
- Statistical analysis linking behavior metrics to sentiment shifts.  
- Actionable insights summarized for traders and analysts.  

---

## 📝 Notes

- Ensure both datasets (trading and sentiment) are available and formatted properly before execution.  
- Large datasets may increase runtime — optimize using sampling if needed.  
- Sentiment indices should be timestamp-aligned with trading logs for accuracy.  
- This notebook is designed for **research and educational purposes**.

---

## 🧩 Folder Structure

```
📁 trader-sentiment-analysis/
│
├── 📓 notebook_1.ipynb           # Main analysis notebook
├── 📁 csv_files/                 # Raw and processed data files
├── 📁 outputs/                   # Plots and charts generated
└── 📄 ds_report.pdf              # Final summarized insights and explanations.     
└── 📄 README.md                  # Documentation (this file)
```

---

## 👤 Author

**Pradipta Khan**  
Data Science Enthusiast | AI Researcher | Analyst  

📬 Connect: [LinkedIn](https://www.linkedin.com/in/pradipta-khan) | [GitHub](https://github.com/pradipta2005)

---

## ⭐ Acknowledgment
 
Developed as part of the project:  
> _“Analyzing the relationship between trader behavior and market sentiment to identify hidden trends for smarter trading decisions.”_

---


