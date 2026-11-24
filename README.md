
# 🛒 Amazon Retail Intelligence & Sales Analytics

### An End-to-End Business Intelligence Project Using Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Amazon.in-orange)

## 📌 Project Overview

**Amazon Retail Intelligence & Sales Analytics** is an end-to-end Business Intelligence project developed using Microsoft Power BI. The project analyzes Amazon.in retail sales data to understand sales performance, product demand, order trends, fulfilment operations, cancellations, and returns.

The objective is to transform raw e-commerce transaction data into meaningful business insights through data cleaning, transformation, analysis, DAX calculations, and interactive dashboards.

The analysis covers the period from **31 March 2022 to 29 June 2022** and contains approximately **129K order-line records**.

## 🎯 Project Objectives

- Analyze overall Amazon sales and revenue performance.
- Identify top-performing product categories.
- Understand product size and quantity distribution.
- Evaluate monthly sales and revenue trends.
- Analyze order fulfilment performance.
- Examine order cancellations and product returns.
- Identify operational challenges and opportunities.
- Build interactive dashboards to support data-driven decisions.

## 📊 Dataset Description

The project uses the **Amazon Sale Report** dataset containing Amazon.in order-level sales information.

| Dataset Attribute | Description |
|---|---|
| Platform | Amazon India |
| Analysis Period | 31 March – 29 June 2022 |
| Order Lines | 128,975 |
| Unique Orders | 120,378 |
| Units Sold | 110,992 |
| Gross Revenue | ₹71.67 Million |
| Net Revenue | ₹70.29 Million |

### Important Dataset Fields

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Date | Date of order |
| Status | Order status |
| Fulfilment | Order fulfilment method |
| Sales Channel | Sales platform |
| Category | Product category |
| Size | Product size |
| Qty | Quantity ordered |
| Amount | Order amount |
| Ship City | Customer shipping city |
| Ship State | Customer shipping state |
| Courier Status | Shipment status |

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Measures and KPI calculations |
| CSV | Dataset storage and input |
| Microsoft Excel | Data inspection and validation |
| Git & GitHub | Version control and project documentation |

## 🔄 Project Workflow

### 1. Data Collection

- Collected the Amazon Sale Report dataset.
- Examined the structure and available fields.
- Identified missing values, inconsistent entries, and data-quality issues.

### 2. Data Cleaning & Transformation

Data preparation was performed using Power Query.

Key transformation activities included:

- Converted date fields into appropriate date formats.
- Standardized inconsistent state names.
- Consolidated 69 state-name variations into 38 standardized values.
- Grouped 13 raw order-status values into six meaningful status groups.
- Reviewed missing and inconsistent records.
- Prepared the data for analysis and visualization.

### 3. Data Analysis

The prepared dataset was analyzed across different business dimensions:

- Sales and revenue analysis
- Product category analysis
- Product size analysis
- Monthly sales trends
- Order status analysis
- Fulfilment performance
- Cancellation and return analysis

### 4. DAX Measures

DAX (Data Analysis Expressions) was used to create analytical measures and KPIs.

The analysis includes calculations for:

- Gross Revenue
- Net Revenue
- Total Orders
- Total Units Sold
- Cancellation Rate
- Return Rate
- Monthly Revenue
- Fulfilment Performance

### 5. Dashboard Development

Interactive Power BI report pages were developed to present the findings.

## 📈 Dashboard Pages

### Page 1: Sales Overview

Provides a high-level summary of Amazon sales performance.

Key areas:
- Gross and net revenue
- Total orders
- Units sold
- Monthly revenue trends
- Order performance indicators

### Page 2: Product Analysis

Focuses on product-level sales performance.

Key areas:
- Category-wise revenue distribution
- Top-performing product categories
- Product size distribution
- Quantity analysis
- Product demand patterns

### Page 3: Order & Fulfilment Analysis

Focuses on order processing and fulfilment performance.

Key areas:
- Amazon vs Merchant fulfilment
- Order status distribution
- Cancellation analysis
- Return analysis
- Courier status monitoring

## 🔍 Key Business Insights

### 1. Overall Sales Performance

- Gross revenue reached approximately **₹71.67 million**.
- Net revenue after recorded returns was approximately **₹70.29 million**.
- The dataset contains 120,378 unique orders.
- A total of 110,992 units were sold.

### 2. Product Category Performance

- Set contributed approximately **49.9%** of gross revenue.
- Kurta contributed approximately **27.1%**.
- Together, Set and Kurta generated approximately **77% of gross revenue**.
- The top four product categories contributed approximately 98% of gross revenue.

### 3. Monthly Revenue Trends

| Month | Gross Revenue |
|---|---:|
| April 2022 | ₹26.23 Million |
| May 2022 | ₹23.95 Million |
| June 2022 | ₹21.39 Million |

**Insight:** Revenue declined by approximately 18.5% from April to June 2022.

Note: March contains only 31 March data, while June ends on 29 June. Therefore, these months do not represent complete calendar months.

### 4. Product Size Analysis

- M, L, and XL were the leading product sizes.
- Together, these three sizes accounted for approximately 50.9% of units sold.

### 5. Fulfilment Analysis

| Fulfilment Method | Orders | Share |
|---|---:|---:|
| Amazon | 84,002 | 69.8% |
| Merchant | 36,376 | 30.2% |

**Insight:** Amazon fulfilment handled the majority of recorded orders.

### 6. Cancellation Analysis

- Overall cancellation rate was approximately **14.3%**.
- Merchant fulfilment cancellation rate was approximately **17.5%**.
- Amazon fulfilment cancellation rate was approximately **12.9%**.

**Insight:** Merchant-fulfilled orders showed a higher cancellation rate than Amazon-fulfilled orders.

### 7. Return Analysis

- Approximately 1,992 returned orders were recorded.
- Recorded returns were associated with Merchant fulfilment.
- The recorded return rate was approximately 1.7% overall.

**Important:** Return information in the dataset is incomplete across fulfilment methods. All recorded returns were associated with Merchant fulfilment, so the overall return rate may be understated.

## 💡 Business Recommendations

Based on the analysis, the following actions can help improve business performance:

1. **Focus on High-Performing Categories:** Maintain sufficient inventory for Set and Kurta products because they contribute a major share of revenue.

2. **Optimize Product Inventory:** Use size-demand patterns to plan inventory and reduce stock shortages.

3. **Reduce Order Cancellations:** Investigate the higher cancellation rate associated with Merchant fulfilment.

4. **Improve Fulfilment Operations:** Monitor order processing and courier performance to identify operational delays.

5. **Monitor Monthly Revenue:** Investigate the decline in revenue from April to June and identify possible causes.

6. **Improve Return Tracking:** Maintain consistent return records across fulfilment methods for more reliable return analysis.

## ⚠️ Project Limitations

- The dataset covers a limited period from 31 March to 29 June 2022.
- Cost information is unavailable; therefore, profit and profit margin cannot be calculated.
- Return tracking is incomplete across fulfilment methods.
- March and June are partial months.
- Average order amount calculations may be affected by cancelled order lines recorded with zero amounts.
- The analysis reflects the available dataset and should not be interpreted as a complete representation of Amazon's overall business performance.

## 📁 Repository Structure

```text
Amazon-Retail-Intelligence-/
│
├── Analysis/
│   └── Analysis-related project materials
│
├── Result/
│   └── Project results and outputs
│
├── clean-data/
│   └── Cleaned dataset
│
├── raw data/
│   └── Original dataset
│
└── README.md
```

## ▶️ How to Explore the Project

1. Clone or download this repository.
2. Explore the `raw data` folder to understand the original dataset.
3. Review the `clean-data` folder to examine the prepared data.
4. Explore the `Analysis` and `Result` folders to understand the analytical work and outcomes.
5. Open the Power BI report in Microsoft Power BI Desktop if the `.pbix` file is available separately.

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

- Data Analysis
- Data Cleaning
- Data Transformation
- Power Query
- DAX Calculations
- KPI Development
- Business Intelligence
- Data Visualization
- E-commerce Analytics
- Business Reporting
- GitHub Project Management

## 👩‍💻 Author

**Disha Singh**

GitHub: [@singh06disha-cmd](https://github.com/singh06disha-cmd)

Project Repository: [Amazon Retail Intelligence](https://github.com/singh06disha-cmd/Amazon-Retail-Intelligence-)

---

## ⭐ Conclusion

The Amazon Retail Intelligence & Sales Analytics project demonstrates how raw e-commerce transaction data can be transformed into meaningful business insights using Power BI.

By combining data preparation, analytical calculations, and interactive visualization, this project provides a structured understanding of product performance, revenue trends, fulfilment operations, cancellations, and returns.

It showcases the practical application of Business Intelligence concepts and data analytics techniques to a real-world retail use case.

**If you find this project useful, consider giving the repository a ⭐ star!**
