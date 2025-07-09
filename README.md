📁 E-commerce Dashboard – Data Documentation
This folder contains the datasets and supporting information for the Power BI E-commerce Dashboard Project. The data has been compiled and enriched from multiple CSV sources to support insightful business intelligence reporting.

📑 Included Data Files
🔹 Raw CSV Files
Original data sources used to build the final dataset:

Customers_Large.csv: Customer details including ID, name, and segment.

Orders_Large.csv: Order-level data with transaction ID, product references, date, and customer ID.

Products_Large.csv: Product catalog including product ID, name, category, and price.

Sales_Large.csv: Sales information such as order ID, tax, discount, and revenue.

🔹 Final Processed File
Ecommerce_Sales_Data.xlsx: Merged and enhanced dataset containing derived metrics for streamlined analysis.

➕ Derived Columns
Profit
Purpose: Calculates net profit per transaction.

Formula: Revenue - (Cost + Tax)

Profit Margin
Purpose: Evaluates profitability relative to revenue.

Formula: Profit / Revenue

Discount Impact
Purpose: Quantifies how much discounts influence total revenue.

Formula: Discount / Revenue

Popularity
Purpose: Custom metric indicating product demand levels (Low, Medium, High) based on sales volume.

🛠️ Usage Instructions
The Ecommerce_Sales_Data.xlsx file is Power BI–ready and can be imported for dashboard/report creation.

Raw CSVs are preserved in the Original Data folder to support transparency, versioning, and custom transformation.

📁 Directory Overview
bash
Copy
Edit
├── Ecommerce_Sales_Data.xlsx        # Final dataset with enriched fields
└── Original Data/
    ├── Customers_Large.csv          # Raw customer data
    ├── Orders_Large.csv             # Raw order data
    ├── Products_Large.csv           # Raw product catalog
    ├── Sales_Large.csv              # Raw sales transactions
