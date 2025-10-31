# Customer Sales Analysis

## Objective
This project provides a concise view of revenue and quantity analytics to understand **who buys** (by customer) and **what sells** (by item). It supports sales, marketing, and inventory teams in identifying top customers, best-selling items, and emerging trends, enabling data-driven decision-making.

## Data and Scope
- **Data sources**: Sales/orders, customers, items, and a time dimension.
- **Core tables**:
  - **Customers**: Customer Name, Region, Segment
  - **Orders**: Order ID, Date, Customer ID, Item ID, Quantity, Revenue
  - **Items**: Item ID, Description, Category
  - **Time**: Date, Month, Quarter, Year

## Metrics and Definitions
- **Revenue by customers**: Total revenue per customer over the analyzed period
- **Quantity by customers**: Total units sold per customer
- **Quantity by items**: Total quantity sold per item
- **Derived insights**: Top customers, best-selling items, growth indicators, market share per customer/item

## Data Highlights & Outcomes
- **Top Performing Retailers**: PetSmart leads with $341,991.43 revenue and 7,432 items sold.
- **Top Selling Items**:
  - Item 4: 11,223 units, $392,798.50 revenue.
  - Item 1: 3,932 units, $204,473.61 revenue.
- **Retailer & Item Performance**:
  - PetSmart and Home Depot show balanced performance.
  - Kohl’s heavily relies on Item 3 for revenue.
  - Target and Home Depot present balanced revenue distribution.
  - Lowes has relatively lower total revenue.
- **Strategy Insights**:
  - Diversify product range.
  - Focus on high-revenue items.
  - Understand customer and item contributions to grow revenue.

## Methodology
- Data cleaning, merging, and validation.
- Descriptive analysis to identify top performers.
- Visualizations to depict sales trends and distributions.
- Insights derived through aggregation and comparison.

## Results & Visualizations
- Key charts highlighting top customers, best-selling items, and revenue trends.
- Tables summarizing revenue and quantity metrics.
- Visual insights support strategic recommendations.

## Conclusions
- Focus on diversifying product offerings based on high performers.
- Target top customers for retention and upselling.
- Monitor trends for emerging products and regions.

## Future Work
- Incorporate seasonality and time-series trends.
- Add predictive models for sales forecasting.
- Explore customer segmentation for targeted marketing.

## Acknowledgments
Data sourced from internal sales and customer databases.

