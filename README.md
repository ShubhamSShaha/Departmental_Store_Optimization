# Retail Basket & Customer Segmentation

**Business question:** Which products are bought together, and which customer segments should promotions target?

**Approach**
- Market basket analysis (Apriori) on 7,500 transactions to find product associations by lift
- Hierarchical clustering on customer income and spending score to define segments

**Key findings**
- Top rule: [item A] → [item B] (lift [x]), a candidate for co-placement or bundling
- [N] customer segments; the high-income, high-spend group is [x]% of customers, the priority for loyalty offers

**Recommendations:** store layout, bundle promotions, targeted offers by segment

**Tools:** Python, pandas, apyori, scipy, matplotlib
