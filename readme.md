# 🛒 Market Basket Analysis

## Customer Purchase Pattern Analysis Using Apriori Algorithm

---

## 📌 Project Overview

This project performs **Market Basket Analysis** on retail transaction data to discover hidden purchasing patterns and identify which products are frequently bought together. The analysis uses the **Apriori algorithm** to generate association rules that can be used for cross-selling recommendations, store layout optimization, and product bundling.

### Key Question Answered:
> *"When a customer buys product X, what other products are they likely to buy?"*

### Real-World Example:
When you shop online and see "Customers who bought this also bought..." - that is Market Basket Analysis in action.

---

## 📊 Dataset

- **Source:** Retail transaction data (Excel/CSV format)
- **Size:** 7,500+ transactions
- **Products:** Approximately 300 unique items
- **Average basket size:** 5-7 items per transaction
- **Smallest basket:** 1 item
- **Largest basket:** 32 items

### Original Data Issue:
Each transaction was spread across 20 columns instead of one row per basket. The data required significant cleaning before analysis.

### Most Frequent Items:
1. Mineral water (23% of transactions)
2. Green tea (18% of transactions)
3. Chocolate (15% of transactions)
4. Eggs (12% of transactions)
5. French fries (11% of transactions)

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| Python 3.x | Core programming language |
| pandas | Data manipulation and cleaning |
| numpy | Numerical operations |
| matplotlib | Data visualization |
| seaborn | Statistical visualizations |
| mlxtend | Apriori algorithm implementation |

### Installations:
```bash
pip install pandas numpy matplotlib seaborn mlxtend