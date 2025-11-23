# Customer Segmentation with RFM Analysis (Python + Power BI)

This project performs **customer segmentation using RFM (Recency, Frequency, Monetary) analysis** on a retail / e-commerce style dataset.  
It combines **Python** for data preparation & RFM scoring and **Power BI** for interactive visualisation.

---

## Objectives

- Segment customers based on their purchase behaviour  
- Identify high-value and at-risk customer groups  
- Provide an interpretable framework for targeted marketing and retention  
- Demonstrate a hybrid workflow: Python for analytics + Power BI for BI dashboards  

---

## RFM Definition

- **Recency (R):** How recently a customer made a purchase  
- **Frequency (F):** How often a customer buys  
- **Monetary (M):** How much revenue the customer generates  

RFM scores are combined into segments (e.g. *Champions, Loyal, At Risk, Lost*).

---

## Technologies Used

- Python (Pandas, NumPy)  
- Jupyter Notebook  
- Power BI  
- (Optional) Matplotlib / Seaborn for plots  

---

## Project Structure

```text
customer-segmentation-rfm-analysis/
  data/         → input dataset (e.g. Sample - Superstore)
  notebooks/    → rfm_analysis.ipynb (Python RFM analysis)
  powerbi/      → rfm_dashboard.pbix (Power BI dashboard)
  screenshots/  → exported dashboard images / charts
  README.md
```
---

## RFM Customer Segmentation Dashboard (Power BI)

This project includes a complete RFM (Recency–Frequency–Monetary) customer segmentation dashboard built in Power BI.

The dashboard visualises:

* Customer Recency distribution (binned)
* Frequency distribution
* Monetary distribution (log-scaled & binned)
* RFM customer segments (Champions, Loyal, High Spenders, Frequent, Recent, Others)
* KPI summary
  * Total Customers
  * Average Recency
  * Average Frequency
  * Average Monetary
* Customer table with RFM scores and assigned segment

---

## Technologies

* Power BI
* DAX
* Python (for RFM preprocessing)
* Jupyter Notebook
* Pandas / NumPy

---

## Dashboard File
```
PBIX file:

/powerbi/rfm_dashboard.pbix
```
---


## Screenshot


<img src="screenshots/rfm_dashboard.png" width="850">

## Planned Workflow

### 1. Python (notebooks/rfm_analysis.ipynb)
* Load transactional sales data
* Aggregate to customer-level
* Compute R, F, M metrics
* Assign RFM scores & segments
* Export RFM table for Power BI

### 2. Power BI (powerbi/rfm_dashboard.pbix)

* Import RFM table
* Build RFM overview dashboard
* Visualise segment distributions & KPIs

---

## Business Value

RFM segmentation helps organisations:
* Focus on high-value customers
* Design retention campaigns for at-risk segments
* Reduce marketing waste on low-value / lost customers
* Support data-driven customer strategy with simple, explainable metrics

---

## Next Steps

* Add dataset to data/ (e.g. “Sample - Superstore.csv”)
* Create notebooks/rfm_analysis.ipynb for Python RFM analysis
* Export RFM results and build rfm_dashboard.pbix in powerbi/
* Add screenshots of the dashboard to screenshots/ and link them here
