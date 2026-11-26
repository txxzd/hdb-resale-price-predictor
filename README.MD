# HDB Resale Price Predictor

Predicting Singapore HDB resale flat prices from public transaction data.

🚧 Work in progress

## Data
HDB resale transactions (Jan 2017 onwards) from [data.gov.sg](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view).
Download the CSV into `data/` (not included in this repo).

## Plan
- [ ] Exploratory data analysis
- [ ] Location features (distance to MRT, schools, CBD via OneMap)
- [ ] Baseline + gradient boosting with time-based validation
- [ ] Error analysis
- [ ] Streamlit demo