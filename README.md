# Market-Analysis-Summary
# Customer Segmentation and Product Analysis

## Project Overview
Analysis of customer transaction data to identify most profitable products and loyal customer characteristics for iGnosis Tech's marketing department. The project includes data processing, analysis, and visualization of customer purchasing patterns and product performance.

## Dataset
The analysis uses two main datasets:
- `transaction_data.csv`: Contains transaction details including product info and sales data
- `purchase_behaviour.csv`: Contains customer demographic and segment information

## Requirements
```
pandas
numpy
matplotlib
seaborn
```

## Project Structure
```
├──  transaction_data.csv
│    purchase_behaviour.csv
├── customer_analysis.ipynb
├── output/
│   ├── product_sales.png
│   └── customer_segments.png
└── README.md
```

## Key Findings
- Identified top 3 profitable products based on sales data
- Analyzed customer segments across different lifestages and premium status
- Generated insights about loyal customer characteristics
- Provided recommendations for marketing strategy

## How to Run
1. Clone the repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook notebooks/customer_analysis.ipynb`

## Results
The analysis reveals:
- Most profitable products are large format packages (380g)
- Strongest customer segments are Older Families (Budget) and Young Singles/Couples (Mainstream)
- Clear patterns in purchasing behavior across different customer segments

## Top 3 Most Profitable Products:

1. Dorito Corn Chip Supreme 380g
2. Smiths Crinkle Chip Original Big Bag 380g
3. Smiths Crinkle Chips Salt & Vinegar 330g

## Key Characteristics of Most Loyal Customers:

1. Demographic Profile
2. Shopping Patterns
3. Secondary Loyal Segments

Why These Customers Are Loyal:

Older Families (Budget) likely prioritize value for money and buy in bulk for larger households
Young Singles/Couples (Mainstream) have disposable income and regular social consumption needs
Retirees (Mainstream) show brand loyalty and prefer traditional, trusted products
