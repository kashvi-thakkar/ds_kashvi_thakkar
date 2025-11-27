# Trader Behavior Insights – Data Science Assignment

This project analyzes the relationship between **trader behavior** on Hyperliquid and the overall **Bitcoin market sentiment** (Fear vs Greed). It forms part of the submission for the **Junior Data Scientist – Trader Behavior Insights** role.

---

## Project Structure

<pre>
  ds_kashvi_thakkar/
├── notebook_1.ipynb # Main Colab notebook with complete analysis
├── csv_files/
│ ├── historical_data.csv
│ └── fear_greed_index.csv
├── outputs/
│ ├── avg trader pnl.png
│ ├── buy-sell activity.png
│ ├── trading volume.png
│ └── daily_pnl_trend.png
├── ds_report.pdf # Final summarized insights
└── README.md # Project documentation
</pre>


---

## Objective

To investigate how **trader actions** (P&L, leverage, position size, side of trade) change depending on **market sentiment** (Fear vs Greed).  
The goal is to uncover hidden signals that may support:

- Smarter trading strategies  
- Better risk assessment  
- Pattern recognition during emotional market phases  

---

## Key Analysis Performed

### Data Cleaning & Processing
- Timestamp normalization  
- Merging datasets using nearest-date logic  
- Handling missing values  
- Normalizing leverage/size metrics  

### Exploratory Data Analysis (EDA)
- Distribution of P&L across sentiment phases  
- Volume and leverage variations  
- Directional bias (long vs short) during fear vs greed  
- Hourly activity heatmaps  
- Outlier detection  

### Visualizations
Stored in the `outputs/` directory:
- PnL vs Sentiment  
- Average Position Size vs Sentiment  
- Leverage Trends  
- Trader Activity Heatmap  
- Greed-phase vs Fear-phase risk behavior  

---

## Summary of Insights

- **Greed periods show significantly higher leverage and risk-taking.**
- **Fear periods correlate with reduced trade size and more conservative entries.**
- Profitable traders tend to **reduce leverage** during high-volatility fear days.
- Directional bias becomes more predictable during extreme sentiment zones.

(Complete analysis in `ds_report.pdf`.)

---

## Reproducibility – How to Run

1. Open the notebook using this Colab link:  
   **[[Google Colab Notebook Link](https://colab.research.google.com/drive/1XYMpesAqoJ3TL8uZ7Wvnz-vAP4I7Hic6?usp=sharing)** 

2. Upload the dataset or update paths if needed.

3. Run the notebook top to bottom — charts will be saved automatically inside `outputs/`.

---

## Additional Links

- **GitHub Repository:** [<[GitHub repo link](https://github.com/kashvi-thakkar/ds_kashvi_thakkar)>]  
- **Project Folder (Google Drive):** [<[Drive link](https://drive.google.com/drive/folders/18VUe1LxjYBr3ME7zaylgTWJFo7PwJCl8?usp=drive_link)>]

---

## Author

**Kashvi Thakkar**  
Aspiring Data Scientist  
Email: kashvithakkar16@gmail.com  
GitHub: [github.com/kashvi-thakkar](https://github.com/kashvi-thakkar)

---

If any issues occur while opening the notebook or data, feel free to reach out.
