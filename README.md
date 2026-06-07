# Task---1--Olaoluwa-Ajakaiye
My first Internship Project at DecodeLabs

Data Cleaning & Preparation
Objective
Clean a raw e-commerce dataset by identifying and handling missing values, removing duplicates, and correcting data formats to ensure data integrity before any analysis.
Tool Used
Microsoft Excel
Dataset
Records: 1,200 rows
Columns: 14 (OrderID, Date, CustomerID, Product, Quantity, UnitPrice, ShippingAddress, PaymentMethod, OrderStatus, TrackingNumber, ItemsInCart, CouponCode, ReferralSource, TotalPrice)
What Was Done
Phase 1 - Missing Values
Identified 309 missing values in the CouponCode column
Filled empty cells with "NONE" instead of deleting rows to preserve all 1,200 records
Phase 2 - Duplicates Check
Scanned all rows for duplicate records using Excel Remove Duplicates
Verified all OrderIDs are unique
Result: 0 duplicate rows found
Phase 3 - Data Formatting
Reformatted all 1,200 dates from MM/DD/YYYY to ISO 8601 standard (YYYY-MM-DD)
Verified TotalPrice values — all correctly formatted to 2 decimal places
Checked all text columns for inconsistent casing and whitespace — all clean
Key Results
0% error rate on unique identifiers
0% error rate on date formats
All 1,200 records preserved with no data loss
Files in This Repository
`Dataset for Data Analytics.xlsx` - Contains 3 sheets: Raw Data, Cleaned Data and Change Log

R001Filled 309 missing CouponCode values with "NONE"309ResolvedCR002Reformatted all dates to ISO 8601 (YYYY-MM-DD)1,200ResolvedCR003Verified zero duplicate records and OrderIDs0VerifiedCR004Checked all text columns for casing and whitespace0Verified
