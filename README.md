# bricole-association-mini

##  Objective
Use simulated shopping data and Apriori association rule mining to discover frequent itemsets and shopping patterns.

##  Simulated Transactions
- 10 transactions generated randomly from a pool of 8 items:
  - Bread, Milk, Eggs, Cheese, Butter, Apples, Bananas, Yogurt
- Each transaction has 2–5 items.

##  Analysis
- One-hot encoded the transaction data using pandas.
- Applied Apriori algorithm (min support = 0.3) using `mlxtend`.
- Generated association rules with:
  - Metric: confidence
  - Min threshold: 0.7

##  Example Rule & Interpretation
One generated rule:
> If a customer buys **Milk and Eggs**, they are likely to also buy **Bread** with 80% confidence.

###  Real-Life Meaning
Customers who purchase **Milk and Eggs** often also buy **Bread**. This can inform shelf placement, discounts, or bundles in a retail setting.

##  Files
- `bricole-association-mini.ipynb` - Contains the full Python script
- `README.md` - Summary and explanation


