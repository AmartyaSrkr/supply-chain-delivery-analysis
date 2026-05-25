# Supply Chain Delivery Analysis & Predictive Delay Detection

## Business Problem
A global e-commerce company managing 172,765 orders across multiple 
regions faces chronic late deliveries with no system to identify 
at-risk shipments. This project identifies root causes, quantifies 
financial impact, and builds a predictive model to flag high-risk 
orders before dispatch.

## Key Findings
- Late delivery rate: 54.71% (94,523 orders affected)
- Profit at risk: $2.1M across delayed orders
- First Class shipping: 100% delay rate, the single biggest operational failure
- Peak delay months: August, September (55.4%) and December (55.2%)
- Predictive model precision on late orders: 77%

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, NumPy

## Project Structure
- `notebooks/` — full analysis notebook with commentary
- `report/` — 9-section business report with 8 prioritised recommendations
- `dashboard/` — key visualisations and bottleneck charts

## Results Summary
| Metric | Value |
|--------|-------|
| Total Orders Analysed | 172,765 |
| Late Delivery Rate | 54.71% |
| Profit at Risk | $2.1M |
| Model Accuracy | 72% |
| Model Precision (Late Orders) | 77% |
| Test Set Size | 34,553 records |

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/supply_chain_analysis.ipynb

## Strategic Recommendations
1. Immediate audit of First Class and Second Class shipping carriers
2. Deploy predictive alert system into order management workflow
3. Resolve payment processing bottlenecks (PAYMENT_REVIEW: 80% delay rate)
4. Build seasonal surge capacity for August, September, and December
