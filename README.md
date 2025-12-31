# **Executive Summary ~ Vendor Performance Analysis**

## **Business Problem**
Retail profitability is heavily influenced by vendor pricing, freight costs, lead times, and inventory efficiency.

The objective of this analysis is to evaluate vendor performance and identify:
- Cost inefficiencies
- Vendor dependency risks
- Profitability variance across vendors

The insights aim to support better vendor negotiations, inventory optimization, and sourcing decisions.

## **Clear Objective**
- Identify top and underperforming vendors by cost and profitability
- Analyze unit cost variation across vendors
- Evaluate impact of freight percentage on vendor economics
- Assess lead time consistency and operational risk
- Highlight vendors contributing to high cost volatility

## **Tools & Skills Used**
- Python (Polars, Pandas, NumPy)
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Aggregation & Group-level Analysis
- Business Metrics

## **Key Findings**
- ### *Widespread Margin Erosion at Brand Level*
  - A significant proportion of brands operate below the acceptable 15% gross margin threshold, with many exhibiting negative gross margins
  - Several brands generate low sales while incurring large losses, indicating inefficient product assortment and pricing misalignments.
  - High sales volume does not guarantee profitability, highlighting cost and pricing inefficiencies.

- ### *Revenue Concentration Does Not Equal Profitability*
  - A small group of vendors contributes a large share of total revenue, yet many of these vendors generate substantial gross losses.
  - Vendor contribution analysis reveals a clear revenue–profit mismatch, where scale amplifies losses instead of offsetting them.
  - Only a limited subset of vendors consistently delivers both revenue and profit, making them true value creators.

- ### *Bulk Purchasing Delivers Massive Cost Savings but Is Underutilized*
  - Bulk purchasing reduces unit cost by over 90% compared to small orders.
  - Despite this, more than 95% of purchase orders are small-sized, indicating severe underutilization of bulk procurement.
  - Fragmented purchasing behavior is one of the largest drivers of avoidable cost leakage.

- ### *Inventory Turnover Issues Drive Holding Cost Risk* 
  - Inventory turnover is skewed toward low values, with many brands operating near or below turnover < 1.
  - Low turnover strongly correlates with dead stock accumulation, locking capital in unsellable inventory.
  - Dead stock risk is highly concentrated among a small set of brands, while overstock issues are widespread and systemic.

- ### *Vendor Profitability Varies in Stability, Not Just Cost*
  - Several vendors exhibit high unit cost volatility and freight impact, making profitability unpredictable.
  - Lead time averages are similar across vendors, but lead time reliability varies significantly, increasing safety stock requirements.
  - A small group of vendors accounts for disproportionate financial and operational risk, despite representing a minor share of the vendor base.
## **Overall Business Impact**
- Margin erosion driven by pricing, freight, and cost volatility
- Excess working capital locked in slow-moving and dead inventory
- Over-reliance on high-volume but low-profit vendors
- Reduced forecasting accuracy and procurement efficiency
## **Strategic Recommendations**
### *Optimize Brand Portfolio*
- Discontinue or rationalize consistently loss-making brands, especially those with low sales and negative margins
- Reprice or renegotiate high-volume, low-margin brands to convert scale into profitability.
- Promote brands with positive margins but moderate sales to scale profitably.

### *Shift Vendor Strategy from Revenue to Profit*
- Reduce dependency on vendors that consistently dilute margins.
- Introduce a vendor profitability scorecard combining:
   - Revenue Contribution
   - Gross Profit Contribution
   - Cost Volatility
   - Flight Impact
   - Lead Time Reliability 

### *Consolidate Purchases to Unlock Cost Savings*
- Aggressively consolidate small orders into bulk purchases where operationally feasible.
- Establish minimum order quantity (MOQ) guidelines to discourage inefficient procurement.
- Centralize procurement planning for high-frequency SKUs.

### *Strengthen Inventory Governance*
- Apply turnover-based replenishment controls for slow-moving brands.
- Actively liquidate dead stock through markdowns or delisting.
- Recalibrate safety stock and reorder points for overstock-heavy brands.

### *Manage Vendor Risk Proactively*
- Renegotiate contracts with high-volatility vendors to include:
  - Price stabilization clauses
  - Freight cost caps
  - Long-term rate agreements
- Diversify sourcing away from unstable vendors, even at slightly higher unit cost.
- Align safety stock policies with vendor delivery reliability.

## **DataSet** ([Link](https://drive.google.com/drive/folders/1QdN01yMBgj34owUZa-Gd-zyFqdzsrwgT?usp=sharing))
a) begin_inventory ([Link](https://drive.google.com/file/d/19FrxBvZwjka8wnvAyZhw8U5KH4ISA-ZK/view?usp=sharing))
b) end_inventory ([Link](https://drive.google.com/file/d/1ebcvARzBEBkrPZGjOaTCoj2CvegZfu5g/view?usp=sharing))
c) vendor_invoice ([Link](https://drive.google.com/file/d/1owK2YhFHYX05h-d_VpgyVHYLzwcNRSVy/view?usp=sharing))
d) purchase_prices ([Link](https://drive.google.com/file/d/163JZ0VVSBBVoXHLx2Hl1r5hqZkQwOVF9/view?usp=sharing))
e) sales ([Link](https://drive.google.com/file/d/1jyCvChbYi1kLyLpCniqnSenjWBC4S0-q/view?usp=sharing))
f) purchases ([Link](https://drive.google.com/file/d/1Rt9Aw8f3rIXLgqlrUmwBk8bwzt1zT-SU/view?usp=sharing))
