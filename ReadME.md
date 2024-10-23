
# E-commerce Analysis

This project analyzes an e-commerce dataset ("Superstore_USA.xlsx") to extract insights about sales, shipping, product categories, and customer behavior. The analysis is conducted using Python in a Jupyter Notebook, focusing on exploratory data analysis (EDA) and visualization techniques.

## Key Features
- **Data Cleaning:** Handling missing values and standardizing column values.
- **Exploratory Data Analysis (EDA):** Understanding trends in sales, shipping modes, and customer preferences.
- **Data Visualization:** Using `matplotlib` and `seaborn` to visualize key insights, such as the most demanded products, highest sales regions, and product margins.

## Analysis Steps
1. **Data Loading and Preparation:**
   - Loaded the dataset containing 9,426 rows and 24 columns.
   - Filled missing values in the "Product Base Margin" column.
   - Cleaned and standardized values in the "Order Priority" column.

2. **Exploratory Data Analysis (EDA):**
   - **Order Priority Analysis:** Counted the frequency of each order priority.
   - **Shipping Mode Analysis:** Analyzed the distribution of different shipping modes.
   - **Customer Segment Analysis:** Visualized the distribution of customer segments.
   - **Product Category Analysis:** Identified the most demanded product categories.
   - **Sub-Category Demand Analysis:** Assessed demand within "Office Supplies," "Technology," and "Furniture" categories.
   - **Yearly Order Trends:** Analyzed the number of orders received each year.
   - **Profit by Product Category:** Visualized profit contributions across different product categories.
   - **Sales by State/Province:** Identified states with the highest sales.
   - **Product Base Margin Analysis:** Compared product margins across categories.

3. **Visualizations:**
   - Count plots, bar graphs, and pie charts were used to visualize distributions and trends.
   - Annotated graphs to highlight key figures and trends for better understanding.

## Requirements
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/e-commerce-analysis.git
   ```
2. **Install dependencies:** Make sure all the required Python libraries are installed.
3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Open and run the notebook:** Execute each cell in `E-commerce Analysis.ipynb` to follow along with the analysis.

## Data
The dataset used in this analysis (`Superstore_USA.xlsx`) includes information on orders, customers, products, and sales performance. It contains the following details:
- Order and shipping information
- Product categories and sub-categories
- Customer segmentation
- Financial metrics such as sales, profit, and discount

## Results
The analysis provides insights into:
- The distribution of order priorities and shipping modes.
- The most and least demanded product categories and sub-categories.
- Yearly trends in order volume.
- Profit contributions from different product categories.
- Sales distribution across various states.




