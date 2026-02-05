# 🛒 Retail & Supply Chain Data

Welcome to the **Retail Operations and Logistics Hub**. This repository features datasets that model the complex world of modern commerce, from warehouse floors to customer checkout.

## 📦 Fulfillment & Logistics Catalog

| File Name | Domain | Critical Metric | Optimized via... |
| :--- | :--- | :--- | :--- |
| `retail_customer_footfall_v2.csv` | Real Estate | Staff-to-Visitor ratio| Poisson Analysis |
| `retail_demand_forecasting_v2.csv` | Inventory | Forecast Bias | DeepAR / Transformer |
| `retail_inventory_levels_v2.csv` | Supply Chain | Shrinkage / Waste | Anomaly Detection |
| `retail_logistics_cost_v2.csv` | Finance | Cost per Mile (CPM) | Linear Programming |
| `retail_order_fulfillment_v2.csv` | Fulfillment | Last-mile Success % | Travel Salesman Alg. |
| `retail_pricing_discount_v2.csv` | Marketing | Price Elasticity | Demand Curves |
| `retail_returns_shrinkage_v2.csv` | Loss Preven | Theft / Damage Rate | Random Forest |
| `retail_store_sales_v2.csv` | Corporate | YoY Revenue Growth | XGBoost Regressor |
| `retail_supplier_performance.csv` | Sourcing | Lead Time Variance | Monte Carlo Sim. |
| `retail_warehouse_operations.csv` | Ops | Picking Speed / Accuracy| Process Mining |

## 🚀 Optimization Projects

1.  **Demand Forecasting 2.0:** Create a model that predicts product demand at a **Store-SKU-Day** level to eliminate overstock.
2.  **Dynamic Pricing Engine:** Use the pricing/discount dataset to find the "Sweet Spot" price that maximizes profit without killing volume.
3.  **Logistics Cost Reducer:** Identify which shipping routes in `retail_logistics_cost` have the highest variance and suggest new carrier partners.

## 🏗️ Supply Chain Standards

- **Units of Measure:** Be careful with units like EA (Each), CS (Case), and PL (Pallet).
- **Lead Time:** Account for external factors like weather or port congestion if available.
- **ABC Analysis:** Category 'A' items (high value/low volume) usually need more precise forecasting than 'C' items.

---
*Part of the [Dataset Hub](../README.md) project.*
