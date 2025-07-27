# Stock Price and Revenue Analysis: Tesla & GameStop 📊

This project analyzes historical stock price and revenue data for **Tesla (TSLA)** and **GameStop (GME)** using data from Yahoo Finance and static HTML files. It uses Python libraries such as `yfinance`, `pandas`, `BeautifulSoup`, and `matplotlib`.

---

## 📁 Contents

- `Tesla` stock price and revenue trends
- `GameStop` stock price and revenue trends
- Graphical visualization of stock vs revenue (till June 2021)

---

## 📦 Technologies Used

- Python
- `yfinance` – for fetching stock data
- `requests` – for downloading HTML pages
- `BeautifulSoup` – for parsing revenue tables
- `pandas` – for data processing
- `matplotlib` – for plotting graphs

---

## 🔍 Data Sources

- [Yahoo Finance](https://finance.yahoo.com)
- HTML pages:
  - Tesla Revenue: [revenue.htm](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)
  - GameStop Revenue: [stock.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

---

## 📊 Graphs Generated

### Tesla
Displays stock price vs revenue (up to June 2021).

```python
make_graph(filtered_tesla_data, filtered_tesla_revenue, "Tesla")
make_graph(filtered_gme_data, filtered_gme_revenue, "GameStop")


