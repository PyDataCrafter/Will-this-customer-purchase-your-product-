# 🛍️ Will-this-customer-purchase-your-product

Welcome to this data science project where I analyzed the behavior of online customers during the busiest months of the year — **November and December** (the busiest months for shoppers) for the marketing team.

> 📈 Goal: Help the marketing team understand customer behavior, optimize campaigns, and improve purchase rates.

---

## 📌 Key Questions & Answers

### 1. 🛒 What are the purchase rates by customer type in November and December?

We calculated the purchase rates for **Returning** and **New Customers** during online shopping sessions:

```python
purchase_rates = {
    "Returning_Customer": 0.1955,
    "New_Customer": 0.2733
}
```

---

### 2. 🔗 What is the strongest correlation between time spent across page types by returning customers?

The strongest correlation between time spent on two page types by **Returning customers** is:

```python
top_correlation = {
    "pair": ("Administrative_Duration", "ProductRelated_Duration"),
    "correlation": 0.3898
}
```

---

### 3. 🎯 With a 15% campaign boost, what is the probability of 100+ sales in 500 returning customer sessions?

A new marketing campaign increases the returning customer purchase rate by 15%. We estimate the probability of achieving at least **100 sales** out of **500 sessions**:

```python
prob_at_least_100_sales = 1.0000
```

> 📊 Binomial probability distribution plot is included to visualize the chances.

![image](https://github.com/user-attachments/assets/74fae3b5-d6ba-4471-95b8-fd9ba7ef0f7a)

---

## 🧰 Tech Stack

- **Python 3.12**
- **NumPy** & **Pandas**
- **SciPy**
- **Matplotlib** / **Seaborn**

---

## 📁 Project Structure

```bash
.
├── data/                   # Raw data files
├── notebooks/              # Jupyter notebooks for EDA and modeling
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PyDataCrafter/Will-this-customer-purchase-your-product-.git
   ```

2. Run the notebook or script of interest:
   ```bash
   jupyter notebook notebooks/notebook.ipynb
   ```

---

## 👤 Author

**Nicolás De Paoli Bornia**  
📧 nicolasdepaolibornia@gmail.com
🔗 [LinkedIn](www.linkedin.com/in/nicolás-de-paoli-bornia-a8a0201a7) | [Portfolio](https://github.com/PyDataCrafter)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 💡 Inspiration

This project is inspired by real-world e-commerce analytics problems where understanding customer behavior can unlock powerful growth opportunities.
