# Customer Buying Patterns & Revenue Boost: Auto Parts & Grocery
## Course: Marketing & Retail Analytics

This project is divided into two parts:
1. **Part A** - Auto Sales Analysis for an automobile parts manufacturing company.
2. **Part B** - Grocery Store POS Analysis to identify popular item combinations.

The objective is to leverage data analysis and customer segmentation to uncover buying patterns and provide actionable marketing recommendations for revenue optimization.

---

## Part A: Auto Sales Analysis

### Objective
Analyze transaction data for an automobile parts manufacturing company to uncover customer purchasing patterns and segment customers for targeted marketing.

### Files
- **EDA**: `Sales_Data.ipynb` - Python notebook for data exploration.
- **RFM Analysis**: `MRA_Sales_Data.knwf` - KNIME workflow for RFM (Recency, Frequency, Monetary) Analysis.
- **Business Report**: 
  - `Sales_Data_Business_Report.pdf` - Full report with EDA and RFM insights.
  - `MRA_Sales_Data.pdf` - Tableau dashboard link.
- **Data**: `Sales_Data.xlsx` - Dataset containing transaction records.

### Key Findings
- **Product Line Demand**: High demand for classic and vintage cars.
- **Transaction Size**: Primarily small and medium deal sizes.
- **Sales Seasonality**: Peak in Q4 and higher sales on Sundays.
- **Customer Segmentation**: RFM analysis helped identify high-value customers and customers at risk of churning.

### Tools Used
- **Python**: For EDA.
- **KNIME**: For RFM Analysis.
- **Tableau**: Access Tableau dashboard link in `MRA_Sales_Data.pdf`.

---

## Part B: Grocery Store POS Analysis

### Objective
Analyze Point of Sale (POS) data from a grocery store to identify frequently bought item combinations and recommend combo offers to boost revenue.

### Files
- **EDA**: `Dataset_Group.ipynb` - Python notebook for EDA.
- **Market Basket Analysis**: `MRA_Dataset_Group.knwf` - KNIME workflow for Market Basket Analysis.
- **Business Report**: 
  - `dataset_group_Business_Report.pdf` - Report with detailed insights.
  - `MRA_Dataset_Group.pdf` - Tableau dashboard link.
- **Data**: `dataset_group.csv` - POS data for analysis.

### Key Findings
- **Top Products**: Poultry, Soda, Cereal, Ice-cream, Cheese, and Waffles were popular items.
- **Order Patterns**: Higher orders on weekends; peak months are January and February.
- **Combo Recommendations**:
  - **Combo Deals**: Discounts on yogurt + poultry + aluminium foil.
  - **Buy Two Get One Free**: Deals on dinner rolls, spaghetti sauce, and ice cream.
  - **Cross-Selling Offers**: Discounts on cheese, bagels, and sandwich bags for cereal buyers.

### Tools Used
- **Python**: For EDA.
- **KNIME**: For Market Basket Analysis.
- **Tableau**: Access Tableau dashboard link in `MRA_Dataset_Group.pdf`.

---

## Instructions for Running the Project

1. **EDA**: Open and run the `.ipynb` files in Jupyter Notebook to view and replicate the exploratory data analysis.
2. **RFM/Market Basket Analysis**: Open the `.knwf` files in KNIME for customer segmentation (Part A) and Market Basket Analysis (Part B).
3. **Tableau Dashboards**: Access the interactive Tableau dashboards using the links in the respective PDF reports (`MRA_Sales_Data.pdf` and `MRA_Dataset_Group.pdf`).

