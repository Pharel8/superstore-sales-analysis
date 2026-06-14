# Superstore Sales Analysis

Exploratory Data Analysis (EDA) of a fictional US retail superstore dataset spanning 2014–2017. The dataset contains 9,994 orders across 4 regions (West, East, Central, South) and 3 product categories (Technology, Furniture, Office Supplies).

## Dataset

**Source:** [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset (`Sample - Superstore.csv`) is not included in this repository due to Kaggle license terms. Download it and place it in the `Data/` folder.

## Questions Explored

| # | Question |
|---|----------|
| 1 | Which year had the highest revenue? |
| 2 | Which region performs best in sales and profit? |
| 3 | Which product category is the most profitable? |
| 4 | Which month generates the most sales? |

## Key Findings

| KPI | Value |
|-----|-------|
| **Total Revenue** | $2,297,201 |
| **Total Profit** | $286,397 |
| **Total Orders** | 5,009 |
| **Avg Profit Margin** | 12.0% |
| **Best Year** | 2017 ($733,215) |
| **Best Region** | West (highest sales & profit) |
| **Best Category** | Technology (highest margin) |
| **Best Month** | November |

### Visualizations

| Chart | Description |
|-------|-------------|
| `images/yearly_sales.png` | Bar chart of sales by year (2014–2017) |
| `images/region_sales.png` | Grouped bar chart of sales & profit by region |
| `images/category_margin.png` | Horizontal bar chart of profit margin by category |
| `images/monthly_sales.png` | Line chart of monthly sales across all years |

## Tech Stack

- **Python** – data processing & analysis
- **pandas** – data loading, cleaning, aggregation
- **matplotlib** – static charts and visualizations
- **seaborn** – enhanced styling and color palettes

## How to Run

### Local (Jupyter Notebook)
1. Clone this repository
2. Download `Sample - Superstore.csv` from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) and place it in `Data/`
3. Install dependencies: `pip install pandas matplotlib seaborn`
4. Open `Superstore-sales-Analysis.ipynb` and run all cells

