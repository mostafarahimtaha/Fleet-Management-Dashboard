# Transjakarta BRT Operations Analysis

This project analyzes Transjakarta Bus Rapid Transit (BRT) operations using two main tools:
- **Power BI Dashboards** for visual storytelling and executive insights
- **Python Data Science Notebook** for data cleaning, exploration, and deeper analytical understanding

---

## 🔧 Tools Used
- **Power BI Desktop** – for dashboard creation
- **Python (Jupyter Notebook)** – for data wrangling and analysis
- **Pandas, Matplotlib, Seaborn** – for data science and visualizations

---

## 📊 Power BI Dashboard Summary

Power BI dashboards provide a high-level overview of Transjakarta performance metrics.

### Key Metrics:
- **36.47K** Transactions in April
- **98M IDR** Revenue
- **221 Corridors**, **2492 Tap-in Stops**, **2200 Tap-out Stops**
- **2.69K IDR** Avg. Pay Amount

### Key Insights:
- **Gender Distribution**: Female passengers outnumber males by **6.6%**
- **Age Classification**: Adults form the majority of riders (**19.7K**)
- **Revenue by Date**: Lowest on weekends (Saturday & Sunday)
- **Revenue by Payment Type**: **DKI cards** are the most used (44M IDR)
- **Peak Days**: Friday generates the highest revenue (18M IDR)
- **Rush Hours**: 5–9 AM and 5–6 PM on weekdays are the busiest

### 📸 Screenshots

| Dashboard Page | Preview |
|----------------|---------|
| Operations Summary | ![](assets/BRT_page-0001.jpg) |
| Demographics & Revenue | ![](assets/BRT_page-0002.jpg) |
| Peak Hours & Tap-in Analysis | ![](assets/BRT_page-0003.jpg) |

---

## 📈 Data Science Analysis – `BRTanalysis.ipynb`

This notebook supports the dashboard with deeper data insights and preprocessing.

### Sections:
- **Background**: Outlines the purpose and issues faced by Transjakarta
- **Data Loading**: Reads raw CSV data on passenger transactions
- **Cleaning**: Fixes nulls, formats dates, extracts hours and weekdays
- **EDA**:
  - Gender and Age distribution
  - Tap-in hour patterns (weekday vs. weekend)
  - Revenue analysis by age and payment method
  - Daily revenue fluctuations

### Sample Insight from Notebook:
- “Friday is the day with the highest total payment (18.0M IDR)”
- “Adult age group generates the highest revenue (56.2M IDR)”

---

## 🚀 How to Use

1. Open the Power BI `.pbix` file to explore interactive dashboards.
2. Run `BRTanalysis.ipynb` in Jupyter or Colab to reproduce the data science insights.
3. Screenshots are available under the `assets/` folder for static references.

---

## 🤝 Contributing

Feel free to fork this project, suggest enhancements, or submit pull requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*Made with ❤️ by mostafarahimtaha*
