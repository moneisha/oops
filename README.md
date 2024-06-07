# Peak Hackathon 2024 - Data Analysis and Forecasting Project

Welcome to the Peak Hackathon 2024!

## Project Overview

### Dataset Description

The dataset given to us for the taskncontains detailed information about sales, profits, orders, and customer segments for a retail store. The dataset includes the following columns:

- `order_id`: Unique identifier for each order.
- `order_date`: Date when the order was placed.
- `ship_date`: Date when the order was shipped.
- `ship_mode`: Shipping mode used for the order.
- `customer_name`: Name of the customer.
- `segment`: Customer segment (Consumer, Corporate, Home Office).
- `state`: State where the customer is located.
- `country`: Country where the customer is located.
- `market`: Market region.
- `region`: Region within the market.
- `category`: Product category.
- `sub_category`: Product sub-category.
- `product_name`: Name of the product.
- `sales`: Sales amount.
- `quantity`: Quantity of products ordered.
- `discount`: Discount applied on the order.
- `profit`: Profit earned from the order.
- `shipping_cost`: Shipping cost for the order.
- `order_priority`: Priority of the order.
- `year`: Year of the order.

## Project Structure

The project is divided into two Notebooks:

1. **Data Analysis Notebook** (`data_analysis.ipynb`):
   - Contains all the analysis related to sales, profits, and purchasing patterns.
   
2. **Forecasting Notebook** (`forecasting.ipynb`):
   - Contains the hierarchical forecasting models and visualizations for future demand trends.
     
### Hierarchical Forecasting Model

For forecasting, we used a hierarchical forecasting model. Hierarchical forecasting involves structuring the forecast based on different levels of aggregation (e.g., product categories, sub-categories). This method provides more accurate and granular predictions, allowing better resource allocation and inventory management.

