# Olist-Data-Analysis
This project aims to analyze Olist's 2017 sales data and provide insights for the business.

## 📌 Overview
- Dataset with 9 tables but i will use only 6 of them.
- Dataset Link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
- Preprocessing techniques including:
  - Merging table
  - Handling missing values
  - Feature Engineering

## 📊 Technologies and Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

## 🚀 How to Run

1. Install the dependencies:
```bash
pip install -r requirements.txt
```

2. Open the notebook:
```bash
jupyter notebook notebook/Olist-Data-Analysis.ipynb
```

## 🛠️ Analysis
- After some analysis and visualizations, we noticed a significant spike in Olist's revenue in November, specifically on November 24th. Upon further investigation, we found that this date coincides with Black Friday. Therefore, we decided to conduct a deeper analysis of this particular day.
- We found that the average review score of the customer is 3.7 which is lower than the average of 2017 (4.1).
- Based on our analysis, it appears that the most likely reason is the significant increase in the average total delivery time of orders on this day. Most customers who made purchases on this day were preparing for Christmas. However, the late delivery rate for these orders was quite high, meaning many of them arrived very close to Christmas—or even after the holiday.
- Finally, after conducting a deeper analysis, I concluded that the main cause of the delivery delays was the longer preparation time by the sellers. This could be due to delays in packaging, insufficient inventory, or not being able to prepare the products on time. Additionally, the delivery process itself also took longer. We also observed that the shipping time for bulky items was significantly higher than average.


## ✍️ Author
Vũ Hoàng Huy
