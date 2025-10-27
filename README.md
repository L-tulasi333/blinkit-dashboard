# blinkit-dashboard
## 1. The dataset contains sales and operations data with the following key fields:
Item Identifier – Unique identifier for each item
Item Type – Category of the product (Fruits, Frozen, Household, etc.)
Item Fat Content – Nutrition information (Regular, Low Fat)
Item Visibility – Percentage visibility of the product in store/outlet
Item Weight – Weight of the item
Sales – Total sales amount for the item
Rating – Customer rating (out of 5)
Outlet Identifier – Unique identifier for outlet
Outlet Establishment Year – Year the outlet was established
Outlet Location Type – Tier 1, Tier 2, or Tier 3
Outlet Size – Small, Medium, or High
Outlet Type – Grocery Store, Supermarket Type 1/2/3

## 2. Clean and Transform the Data
Key tasks in Power Query:
Handle missing values (Sales, Item Weight, Item Fat Content).
Standardize categorical fields (e.g., LF, low Fat → Low Fat; reg → Regular).
Remove duplicates (same Item Identifier + Outlet).
Ensure correct data types (Sales, Rating = Decimal; Item Weight = Numeric).

## Create calculated columns:
Sales per Kg = Sales ÷ Item Weight
Years of Operation = Current Year – Outlet Establishment Year
Profit Margin (if cost available) = Sales – Cost




