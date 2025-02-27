# Supply Chain Data Analysis

## Project Overview
This project analyzes supply chain data to optimize logistics and reduce late deliveries. It leverages data visualization techniques to gain insights into sales trends, delivery performance, and profitability.

## Dataset
The project uses the `DataCoSupplyChainDatasetRefined.csv` dataset, which contains order details, shipping data, customer information, and financial metrics.

## Key Analyses and Visualizations
1. **Product Category Delays in a Specific Country**
   - Identifies late delivery risks for different product categories within a selected country.
   - Uses a stacked bar chart to display on-time vs. late deliveries.

2. **Delayed Deliveries Per Country**
   - Shows the number of late deliveries per country using a horizontal bar chart.

3. **Impact of Discount Percentage on Late Delivery Risk**
   - Uses a violin plot and box plot to analyze whether discounts correlate with late deliveries.

4. **Sales Trend Over Time**
   - Uses a line chart to visualize revenue growth trends over months/years for a selected product.

5. **Correlation Between Order Quantity and Profit Percentage**
   - Uses a scatter plot with regression to examine how order quantity impacts profitability.

6. **Effect of Shipping Mode on Late Deliveries**
   - Compares the number of delayed deliveries across different shipping methods.

## Technologies Used
- **Python**
- **Pandas** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Scipy** (Statistical Analysis)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/SupplyChainDataAnalysis.git
   ```
2. Install dependencies:
   ```sh
   pip install pandas matplotlib seaborn scipy
   ```
3. Run the analysis scripts in a Jupyter Notebook or Python environment.

## Usage
- Modify the country name in the script to analyze late deliveries for different regions.
- Update the product name to see sales trends for specific products.
- Use different statistical models to explore further insights.

## Conclusion
The analysis provides valuable insights into supply chain inefficiencies, helping businesses optimize logistics, reduce late deliveries, and improve profitability.

## Author
[Your Name]

## License
This project is licensed under the MIT License.

