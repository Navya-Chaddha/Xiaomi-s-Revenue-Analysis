# Xiaomi Revenue Analysis 
Comparing revenue growth, mean growth rate, and volatility across Xiaomi's 
Smartphone and IoT & Lifestyle segments from FY2019 to FY2025 using Python.

## Key Findings
Xiaomi's IoT & Lifestyle segment demonstrates a higher mean growth rate and 
lower volatility compared to its Smartphone segment, suggesting it is becoming 
a more stable and resilient revenue driver for the company.

## Methodology
1. Revenue vs FY — plotted absolute revenue for both segments over 7 years
2. YoY Growth Rate — calculated year-over-year % change per segment
3. Mean Growth Rate — average YoY growth across FY2019–FY2025
4. Volatility — measured as standard deviation of annual growth rates

## Data Source
- Xiaomi Corporation Annual Reports (FY2019–FY2025)
- Data manually compiled into `data/xiaomi_revenue.csv`
- All figures in CNY (Chinese Yuan, millions)

## Project Structure
Xiaomi-s-Revenue-Analysis/
├── data/
│   └── xiaomi_revenue.csv
├── xiaomi.ipynb
├── output/
│   └── revenue_plot.png
└── README.md

## Tools Used
- Python 3
- pandas
- matplotlib
- Jupyter Notebook

## How to Run
1. Clone the repo
   git clone https://github.com/Navya-Chaddha/Xiaomi-s-Revenue-Analysis.git
2. Install dependencies
   pip install pandas matplotlib
3. Open the notebook
   jupyter notebook xiaomi.ipynb

## Author
Navya Chaddha
B.Tech — Maths and Computing
Linkedin : https://www.linkedin.com/in/navya-chaddha-97434521b/?skipRedirect=true
