# Predicting Perishable Grocery Stockouts: An Early-Warning System for Proactive Inventory Replenishment
**Course:** DATA602

**Topic:** We develop a machine-learning system that, given data available at a particular time of day (e.g., noon), predicts which store-product combinations will stock out later that same day. We’ll also calculate how long each stockout will last and order products based on the level of risk so that the items that need restocking the most get the attention they need.

**Group Members:** 

Kalash Singh

Diksha Pal

Durga Sreelaasya Vemula

**Dataset and Source:**
*FreshRetailNet-50K*, an open benchmark dataset of hourly fresh-food sales with stockout annotations from an online fresh-grocery store.
- *Dataset:* https://huggingface.co/datasets/Dingdong-Inc/FreshRetailNet-50K
- *Citation:* Wang, Y., Gu, J., Long, L., Li, X., Shen, L., Fu, Z., Zhou, X., & Jiang, X. (2025). FreshRetailNet-50K: A Stockout-Annotated Censored Demand Dataset for Latent Demand Recovery and Forecasting in Fresh Retail. arXiv:2505.16319. https://arxiv.org/abs/2505.16319

*Size & Contents*: The dataset is made up of 50,000 store-product time series of hourly sales, with approximately 90 days of data. It is available at 898 locations in 18 cities and features over 860 perishable products. For each hour, we have stock status, promotional discounts, precipitation and time features. This is millions of store-product-day examples altogether.
