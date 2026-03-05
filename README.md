# 📊 Sales Dashboard — Brazil E-commerce

## 📌 Project Overview

Interactive sales dashboard built with **Streamlit** and **Plotly**, consuming real-time data from a REST API.  
The dashboard analyzes Brazilian e-commerce sales data from 2020 to 2023, allowing dynamic filtering by region, year, and seller.

---

## 🎯 Objectives

- Visualize revenue and sales volume across Brazilian states
- Analyze monthly trends by year
- Compare performance across product categories
- Rank top sellers by revenue and number of sales
- Enable raw data exploration with customizable filters and CSV export

---

## 🛠 Technologies Used

- Python
- Streamlit
- Plotly Express
- Pandas
- Requests (REST API consumption)

---

## 📂 Project Structure

```
Dashboard_streamlit/
│
├── .streamlit/
├── pages/
│   └── Dados_brutos.py       # Raw data page with filters and CSV export
├── Dashboard.py              # Main dashboard page
├── requirements.txt
└── README.md
```

---

## 📊 Features

**Main Dashboard (`Dashboard.py`)** — 3 tabs:

- **Revenue** — Geographic map of revenue by state, monthly revenue trend, top 5 states and product categories
- **Sales Volume** — Same structure focused on number of transactions instead of revenue
- **Sellers** — Adjustable ranking of top sellers by revenue and sales count

**Raw Data Page (`Dados_brutos.py`)**:
- Full filtering across all dataset columns (product, category, price range, date, seller, location, rating, payment type, installments)
- Filtered data preview with row/column count
- CSV download with custom filename

**Sidebar Filters (Dashboard)**:
- Region selector (Brazil or specific region)
- Full period toggle or year slider (2020–2023)
- Multi-select seller filter

---

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Miich2000/Dashboard_streamlit.git
```

2. Navigate to the project folder:
```bash
cd Dashboard_streamlit
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
streamlit run Dashboard.py
```

---

## 🌐 Live Demo

> 🔗 (https://dashboardapp-strmltvendasmiich2000.streamlit.app/)

---

## 🚀 Skills Demonstrated

- REST API consumption with `requests`
- Real-time data filtering and aggregation with Pandas
- Interactive visualizations with Plotly Express (maps, line charts, bar charts)
- Multi-page Streamlit app architecture
- Sidebar filters with dynamic state management
- CSV export functionality with user feedback

---

## 📌 Author

Michel Angelo  
Aspiring Data Scientist | Python · SQL · Data Analysis · Machine Learning  
[github.com/miich2000](https://github.com/miich2000) · [LinkedIn](https://www.linkedin.com/in/michel-angelo-097614181/)
