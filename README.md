# E-Commerce Customer Segmentation Using RFM Analysis

## Business Problem
Segment customers based on purchasing behavior to identify VIP, Loyal, Lost, and Occasional customers for targeted marketing.

## Dataset Source
Dataset provided by Masai School Assessment.

## Dataset Description
- 4,395 transactions
- 681 unique customers
- Features include InvoiceNo, CustomerID, Quantity, InvoiceDate, UnitPrice, Category, and Product Description.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

## Steps Performed
1. Loaded dataset
2. Cleaned missing values and duplicates
3. Created RFM metrics
4. Standardized data
5. Applied K-Means clustering
6. Visualized customer segments
7. Generated business insights

## Data Cleaning Summary
- Removed missing values
- Converted date columns to datetime format
- Created Total Amount feature
- Checked duplicate records

## Key EDA Insights
- Majority of customers belong to Occasional and Lost segments.
- VIP customers represent the smallest customer group.
- High-spending customers generate significantly higher revenue.
- Customer purchase frequency varies across segments.

## Model / Analysis Summary
K-Means Clustering was applied on RFM metrics (Recency, Frequency, Monetary). Elbow Method identified 4 optimal clusters which were mapped into business-friendly customer segments.

## Final Business Recommendations
- Retain VIP customers through exclusive rewards.
- Increase engagement with Loyal customers through personalized offers.
- Reactivate Lost customers using discount campaigns.
- Convert Occasional customers into repeat buyers through loyalty programs.

## How to Run the Project
1. Clone the repository
2. Install requirements:
   pip install -r requirements.txt
3. Open the notebook in Jupyter or Google Colab
4. Run all cells sequentially
