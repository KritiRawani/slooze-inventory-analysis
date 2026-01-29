# Slooze – Inventory, Purchase & Sales Analysis

## Project Description
This project is a data science take-home challenge for **Slooze**, focused on analyzing
sales, purchase, and inventory data for a retail wine & spirits company.  
The objective is to optimize inventory management, reduce inefficiencies, and
extract meaningful business insights using data-driven techniques.

---

## Problem Statement
The company operates across multiple locations and handles millions of transactions.
Traditional spreadsheet-based analysis is insufficient at this scale.  
This project applies analytical and statistical methods to support better
inventory control, procurement planning, and sales performance evaluation.

---

## Analysis Covered

### 1. Demand Forecasting
- Historical sales data analysis
- Time-series based demand estimation
- Insights to support proactive inventory planning

### 2.ABC Inventory Analysis
- Product classification based on sales value
- Identification of high-priority (A), medium (B), and low-priority (C) items
- Inventory strategy recommendations by category

### 3. Economic Order Quantity (EOQ)
- EOQ calculation to minimize holding and ordering costs
- Identification of optimal order quantities

### 4. Reorder Point (ROP) Analysis
- Reorder point calculation using demand and lead time
- Identification of stockout-prone products

### 5. Supplier Lead Time Analysis
- Supplier performance evaluation using lead time metrics
- Identification of procurement risks

### 6. Inventory Risk & Inefficiency Insights
- Detection of slow-moving and overstocked products
- Identification of working capital tied up in inventory

---

## Key Insights
- A small percentage of products contribute the majority of revenue
- EOQ-based ordering can reduce inventory holding costs
- Supplier lead time variability increases stockout risk
- Several products show low sales velocity but high inventory levels

---

## Recommendations
- Apply strict inventory controls for Category A products
- Optimize order quantities using EOQ
- Closely monitor or renegotiate with high lead-time suppliers
- Reduce excess stock for slow-moving items
- Use demand forecasts for procurement planning

---

## Project Structure

SLOOZE-INVENTORY-ANALYSIS/
│
├── data/
│   ├── 2017PurchasePricesDec.csv
│   ├── BegInvFINAL12312016.csv
│   ├── EndInvFINAL12312016.csv
│   ├── InvoicePurchases12312016.csv
│   ├── PurchasesFINAL12312016.csv
│   └── SalesFINAL12312016.csv
│
├── notebooks/
│   ├── .ipynb_checkpoints/
│   └── inventory_analysis.ipynb
│
├── venv/
│
├── README.md
└── requirements.txt

## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/<your-username>/slooze-inventory-analysis.git
cd slooze-inventory-analysis


2. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Run the notebook
jupyter notebook inventory_analysis.ipynb