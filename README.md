# E-Commerce-Sales-Analytics-Business-Intelligence-Dashboard
A comprehensive business intelligence project demonstrating data visualization, KPI analysis, and business problem-solving using Power BI

```markdown
# ShopNest Store - E-Commerce Sales Analytics & Power BI Dashboard
```
## 📋 Project Overview

**Business Context:**
ShopNest Store is an e-commerce platform operating across multiple states, product categories, and customer segments. Leadership needed visibility into sales performance, operational efficiency (delivery delays), customer payment preferences, and seasonal trends to make data-driven strategic decisions.

**Solution:**
I built a comprehensive Power BI dashboard analyzing 103K+ transactions across 7 key business dimensions: product categories, delivery performance, payment methods, geographic regions, seasonal trends, and revenue analysis.

## 🎯 Key Findings & Business Impact

### 1. Top Product Categories by Revenue
**Finding**: Beauty and Health dominates with ₹14.4M in total sales
- **Top Category**: Beauty & Health - ₹14.4M (14.6% of total)
- **Total Sales Across All Categories**: ₹98.7M
- **Business Impact**: Category concentration insight enables targeted marketing and inventory optimization

### 2. Delivery Performance Analysis
**Finding**: Delayed orders represent a significant service gap

| Metric | Count | % of Total |
|--------|-------|-----------|
| Total Orders | 7,827 | 100% |
| Delayed Orders | 811+ | 10%+ |
| Highest Delay Category | Bed, Table & Bath | 811 delays |
| **Impact** | Service quality risk | Affects customer satisfaction & retention |

**Key Insight**: Bed, Table & Bath category shows highest delay frequency, suggesting supply chain bottleneck in this segment.

### 3. On-Time vs. Delayed Orders Trend
**Finding**: Strong operational performance with seasonal variations
- On-time orders consistently exceed delayed orders every month
- Delayed orders show gradual increase but remain manageable (under 15% of volume)
- **Opportunity**: Peak season (Q1 2018) shows highest delayed orders - suggests need for temporary capacity increase

### 4. Payment Method Preferences
**Finding**: Credit card dominance with diversified fallback options

| Payment Method | Transactions | % Share |
|---|---|---|
| Credit Card | 76.8K | 73.92% |
| Boleto | 19.78K | 19.04% |
| Voucher | 5.78K | 5.56% |
| Debit Card | ~500 | <0.50% |
| Not Defined | Negligible | <0.01% |

**Business Value**: 
- 73.92% credit card penetration validates current payment infrastructure investment
- Boleto (19%) represents significant Brazilian market segment
- Opportunity to increase debit card adoption through incentives

### 5. Geographic Sales Distribution
**Finding**: Extreme geographic concentration in São Paulo

| State | Orders | % Share | Market Potential |
|---|---|---|---|
| São Paulo (SP) | 40,000+ | ~51% | Mature/Saturated |
| Rio de Janeiro (RJ) | Significant | ~15-20% | Growth opportunity |
| Minas Gerais (MG) | Moderate | ~10-15% | Growth opportunity |
| Far North (AM, AC, AP, RR) | Minimal | <2% | Expansion opportunity |

**Strategic Insight**: 51% concentration in SP creates business risk. North/Northeast regions represent untapped growth opportunities.

### 6. Seasonal Sales Patterns
**Finding**: Strong growth trajectory with peak in Q1 2018

| Period | Order Volume | Trend |
|--------|---|---|
| 2016 | Minimal | Data collection started |
| Q1 2017 - Q4 2017 | Steady Increase | +25-30% quarter-over-quarter |
| Q1 2018 | 20,000+ orders | **Peak performance** |
| Q2-Q3 2018 | Decline | -15-20% from peak |

**Pattern**: Clear seasonality with Q4 (holiday season) not shown but historically strong in retail.

### 7. Revenue Trend Analysis (Yearly)
**Finding**: Impressive year-over-year growth

| Year | Total Revenue | Growth |
|---|---|---|
| 2016 | Negligible | Baseline |
| 2017 | ₹7M+ | ~N/A (early stage) |
| 2018 | ₹9M+ | +28% YoY |

**Business Outcome**: Demonstrates healthy business scaling and operational maturity.

## 🔧 Technical Implementation & Methodology

### Data Architecture
- **Dataset Size**: 103K+ transactions across multiple dimension tables
- **Time Period**: 2016-2018 (36 months of data)
- **Granularity**: Transaction-level data with customer and product dimensions
- **Refresh Cadence**: Daily/Weekly updates for operational relevance

### Power BI Implementation

**Visualizations Created**:
1. **Bar Charts**: Top 10 categories by revenue, state-wise orders
2. **Stacked Area Charts**: Monthly on-time vs. delayed orders trend
3. **Pie Charts**: Payment method distribution
4. **Time Series Charts**: Quarterly order trends, yearly revenue growth
5. **Interactive Filters**: Drill-through capabilities by category, state, date range

**Key Features**:
- Cross-report drill-through functionality for detailed analysis
- Dynamic filters for date-based filtering (month, quarter, year)
- Calculated measures for KPIs (on-time %, revenue per category, delay rate)
- Conditional formatting to highlight performance outliers

### Data Transformations Applied

Raw Transaction Data
↓
[Data Cleaning & Validation]
↓
[Feature Engineering]
- Order delay flag (Actual Delivery > Estimated Delivery)
- Revenue per transaction
- Customer segment classification
↓
[Dimension Tables Created]
- Product Category Dimension
- Geographic State Dimension
- Payment Method Dimension
- Date Dimension (for time-series analysis)
↓
[Dashboard Modeling]
- Star schema with fact table (transactions) and dimension tables
↓
[Power BI Dashboard]
- Interactive, drill-through enabled reporting


## 📊 Dashboard Pages & Components

### Page 1: Executive Overview
- Total revenue, order count, delay rate
- Top-performing categories
- Geographic heatmap

### Page 2: Operational Performance
- On-time vs. delayed orders timeline
- Delay rate by category
- Performance trend (rolling 30-day)

### Page 3: Payment & Customer Insights
- Payment method distribution
- Customer segments by payment type
- Transaction value distribution

### Page 4: Geographic Analysis
- State-wise order volume heatmap
- Regional revenue contribution
- Market saturation vs. opportunity matrix

### Page 5: Trend Analysis
- Quarterly order volume trends
- Yearly revenue growth
- Seasonality patterns

## 💻 Tools & Technologies

- Power BI
  

