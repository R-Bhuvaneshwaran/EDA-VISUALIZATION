# EDA-VISUALIZATION
# MCX Trade Data Analysis – ETL + EDA with Pandas and Seaborn

This project explores historical trade data from the **Multi Commodity Exchange (MCX) of India**, where we go from raw `.xls` downloads to rich insights and visual storytelling.

---

##  Project Goals

- ✅ Parse and combine `.xls` files (HTML tables) from MCX website  
- ✅ Clean and standardize trade data using `pandas`  
- ✅ Perform time-series and categorical EDA  
- ✅ Use `matplotlib` and `seaborn` for data visualization  
- ✅ Identify outliers, trends, and instrument-level patterns

---

##  Files in This Repo

| File | Description |
|------|-------------|
| `MCX_TRADE.csv` | Final merged CSV containing all trade data |
| `MCX_Trade_EDA.ipynb` | Full Jupyter notebook with ETL + EDA |
| `README.md` | You're here 😉 |

---

##  Data Source

- 🔗 [MCX Historical Market Data](https://www.mcxindia.com/market-data/historical-data)
- The raw data was downloaded in `.xls` format (which are HTML tables under the hood)
- Multiple files were combined using `pandas.read_html()` and saved as a single dataset

---

##  Key Insights Visualized

- Daily & monthly trade volume trends
- 7-day and 30-day rolling averages
- Box plots by `Instrument Type`
- Heatmap of feature correlations
- Weekday trading behavior
- Anomaly detection (top 1% trade days)

---

##  Python Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `os`

---

##  Author

**Bhuvaneswaran R.**  
_Data Engineer → Data Science Enthusiast_  
[📘 Medium Blog](https://medium.com/@Bhuvaneshwaran_16/from-raw-trades-to-market-trends-a-complete-eda-on-mcx-data-3f30d0dfd550) | [🐙 GitHub](https://github.com/R-Bhuvaneshwaran)

---

##  Next Step

👉 Coming next: **“PySpark for Data Enthusiasts”** – learn how to scale this workflow using Spark DataFrames.

---

## 📝 License

Feel free to use or adapt this notebook for learning or teaching purposes. Attribution appreciated!

