# BANT Analysis Dashboard

## Description
This Power BI dashboard helps sales teams qualify leads based on **Budget**, **Authority**, **Need** and **Timeline**. It visualizes lead scores, segments high‑potential opportunities, and offers interactive slicers for real‑time filtering.

## Features
- Interactive slicers for Budget, Authority, Need, Timeline  
- KPI cards showing counts of Hot/Warm/Cold leads  
- Stacked bar chart of lead distribution by Authority level  
- Donut chart of conversion readiness  
- DAX‑powered lead‑scoring measures  


## 🗂️ Repository Structure

```text
├── BANT Analysis Dashboard.pbix    # Power BI file  
├── data/  
│   └── sample_leads.csv           # Sample dataset  
├── sql/  
│   └── data_prep.sql              # SQL scripts used for data prep  
└── README.md                      # This file  

```


## Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/) (version … or later)  
- Excel or any CSV‑capable tool to view `data/sample_leads.csv`

## Setup & Usage
1. Clone or download this repo.  
2. Open **BANT Analysis Dashboard.pbix** in Power BI Desktop.  
3. To swap in your own data, replace `data/sample_leads.csv` and update the data source connection.  
4. Use the slicers and visuals to explore lead‑qualification insights.

## DAX Measures
| Measure Name       | Purpose                                   |
|--------------------|-------------------------------------------|
| `Lead Score`       | Calculates weighted BANT score per lead   |
| `Hot Lead Count`   | Counts leads meeting “Hot” criteria       |
| `Conversion Rate`  | % of qualified leads vs total             |

## How It Works
We apply weighted scores in DAX to each BANT dimension, then classify leads into Hot/Warm/Cold based on thresholds. Visuals update dynamically when slicers are adjusted.

## Contributing
Feel free to open an issue or pull request for bug fixes, feature requests, or feedback.

## License
MIT License (see LICENSE file) or “All rights reserved.”

## Contact
Vikyath Bhat • vikyathvbhat@gmail.com.com • [github.com/Vikyath‑vbhat03](https://github.com/Vikyath‑vbhat03)

## Dataset download

Download the sample leads CSV from Kaggle:

https: //www.kaggle.com/datasets/amritachatterjee09/lead-scoring-dataset

Save it as `data/sample_leads.csv` in this repo.


