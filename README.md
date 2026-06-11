# Xiaomi Revenue Analysis
Comparing revenue growth, CAGR, volatility and revenue share across Xiaomi's 
Smartphone and IoT & Lifestyle segments from FY2019 to FY2025 using Python.

## Key Findings
1. IoT & Lifestyle CAGR (12.10%) is higher than Smartphones (7.31%)
2. Smartphones are  more volatile than IoT (std dev 21.92% vs 14.35%)
3. IoT revenue share grew from 33.7% → 39.8% in just 6 years
4. Smartphone share fell from 66.3% → 60.2% over the same period
5. At this trajectory, IoT could approach 50% of revenue by ~FY2030
6. Xiaomi is quietly transitioning from a smartphone company into adiversified hardware ecosystem — and the data shows IoT is leading that shift.

## Methodology
1. Revenue vs FY — plotted absolute revenue for both segments over 7 years
2. YoY Growth Rate— calculated year-over-year % change per segment
3. Mean Growth Rate — average YoY growth across FY2019–FY2025
4. Volatility — measured as standard deviation of annual growth rates
5. CAGR — compound annual growth rate from FY2019 to FY2025
6. Revenue Share — each segment's % contribution to combined revenue per year

Limitation: 7 data points is a small sample. Findings are directional,not statistically definitive.

## Data Source
- Xiaomi Corporation Annual Reports (FY2019–FY2025)
- Data manually compiled into `xiaomi_revenue.csv`
- All figures in CNY (Chinese Yuan, millions)

## Project Structure
Xiaomi-s-Revenue-Analysis/
├── xiaomi_revenue.csv
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
