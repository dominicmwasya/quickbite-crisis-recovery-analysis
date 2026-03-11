# 🍕 QuickBite Express: Crisis Recovery Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)](https://powerbi.microsoft.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **A comprehensive data analysis project examining a food delivery platform's operational crisis, customer impact, and strategic recovery roadmap.**

[Live Dashboard](#) | [Case Study](reports/Executive_Summary.pdf) | [Presentation](presentation/QuickBite_Presentation.pdf)

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Business Context](#-business-context)
- [Key Findings](#-key-findings)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation & Setup](#-installation--setup)
- [Analysis Approach](#-analysis-approach)
- [Deliverables](#-deliverables)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [Results & Impact](#-results--impact)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)

---

## 🎯 Project Overview

QuickBite Express, a Bengaluru-based food delivery platform, experienced a severe operational and reputational crisis in June 2025. This project analyzes the crisis impact across multiple dimensions and develops a data-driven recovery strategy.

**Analysis Period:** January 2025 - September 2025 (9 months)  
**Dataset Size:** 149,166 orders | 107,776 customers | 19,995 restaurants  
**Tools Used:** Python, Jupyter Notebooks, Power BI, Excel

---

##  Business Context

### The Crisis

In June 2025, QuickBite faced a perfect storm:
- **Week 1:** Viral food safety incident (#QuickBiteDisaster - 2M+ views)
- **Week 2:** Monsoon-related delivery infrastructure failures
- **Week 3:** Aggressive competitor campaigns targeting dissatisfied customers
- **Week 4:** Mass customer exodus and restaurant partner churn

### Business Impact

- **59% order volume drop** (22,761 → 9,293 monthly orders)
- **73,000 customers lost** (69% of customer base)
- **On-time delivery collapse:** 92% → 41%
- **Rating crisis:** 4.5 → 2.5 stars
- **₹19.15M cumulative revenue loss**

---

## 🔍 Key Findings

### Customer Segmentation
- **69% Lost:** 73,000 customers who stopped ordering
- **10% Recovered:** 10,603 loyal customers who stayed
- **13% New:** 13,807 customers acquired post-crisis
- **3% At-Risk:** 3,453 customers showing churn signals

### Operational Breakdown
- **On-time delivery:** Dropped 51 percentage points
- **Cancellation rate:** Doubled from 6% to 12%
- **Delivery time:** Increased by 20.6 minutes
- **Restaurant churn:** 5,338 partners left (27%)

### Financial Impact
- **Monthly revenue:** ₹7.52M → ₹2.68M (-64%)
- **Average order value:** Relatively stable at ₹350
- **Customer lifetime value:** Severely impacted
- **Recovery cost estimate:** ₹31.08M investment needed

---

##  Tech Stack

### Data Analysis & Processing
- **Python** - Primary analysis language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **openpyxl** - Excel file handling

### Visualization
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical graphics
- **Power BI** - Interactive dashboard

### Development Environment
- **Jupyter Notebook** - Interactive analysis
- **VS Code** - Code editor
- **Git/GitHub** - Version control

### Documentation
- **Microsoft Word** - Executive summary
- **Markdown** - Documentation

---

## Project Structure

```
QuickBite-Crisis-Recovery-Analysis/
│
├── 📊 data/                      # Dataset files
│   └── processed/                # Cleaned & processed data
│       ├── customer_segments.csv
│       ├── daily_orders.csv
│       ├── phase_summary.csv
│       └── ...
│
├── 📓 notebooks/                 # Jupyter notebooks
│   └── quickbite_analysis.ipynb # Main analysis notebook
│
├── 📈 visualizations/            # Generated charts
│   ├── 1_daily_orders_trend.png
│   ├── 2_customer_segments.png
│   ├── 3_phase_comparison.png
│   └── 4_rating_trend.png
│
├── 📊 dashboard/                 # Power BI files
│   ├── QuickBite_Dashboard.pbix
│   └── QuickBite_Dashboard.pdf
│
├── 📑 presentation/              # Presentation materials
│   └── QuickBite_Presentation.pdf
│
├── 📄 reports/                   # Written reports
│   └── Executive_Summary.pdf
│
├── 🐍 scripts/                   # Python scripts
│   ├── create_powerbi_csvs.py
│   └── requirements.txt
│
└── README.md                     # This file
```

---

##  Installation & Setup

### Prerequisites

```bash
- Python 3.8 or higher
- Jupyter Notebook
- Power BI Desktop (for dashboard)
```

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/quickbite-crisis-analysis.git
cd quickbite-crisis-analysis
```

2. **Create virtual environment** (recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r scripts/requirements.txt
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook notebooks/quickbite_analysis.ipynb
```

---

## Analysis Approach

### 1. Data Collection & Preparation
- Loaded 7 Excel files containing orders, customers, restaurants, and ratings data
- Cleaned and validated data quality
- Created phase classifications (Pre-Crisis, Crisis, Recovery)

### 2. Exploratory Data Analysis
- Daily order trends and patterns
- Customer behavior analysis
- Delivery performance metrics
- Rating and sentiment analysis

### 3. Customer Segmentation
- Developed segmentation logic based on ordering behavior across phases
- Identified Lost, Recovered, New, and At-Risk customer cohorts
- Analyzed segment characteristics and value

### 4. Root Cause Analysis
- Delivery performance breakdown analysis
- Quality assurance gap identification
- Customer service failure points
- Competitive vulnerability assessment

### 5. Strategic Recommendations
- Customer reacquisition strategy
- Operational excellence roadmap
- Trust rebuilding initiatives
- Financial projections and ROI modeling

---

## Deliverables

### 1. Interactive Dashboard (Power BI)
- **4 KPI cards:** Orders, Customers, On-Time %, Rating
- **Daily trend visualization:** Crisis impact timeline
- **Customer segmentation:** Pie/donut chart breakdown
- **Phase comparison:** Pre-Crisis vs Crisis vs Recovery

**[View Dashboard PDF](https://app.powerbi.com/groups/me/reports/3c86f2b0-d422-4745-a9ef-049e24d6d39f/d51cabee787aa52e96df?experience=power-bi)**



### 2. Executive Summary Report
- 2-page strategic document
- Key findings and insights
- Detailed recommendations
- Implementation roadmap

**[View Executive Summary](reports/Executive_Summary.pdf)**

### 3. Jupyter Notebook Analysis
- Complete Python code
- Data cleaning and preparation
- Statistical analysis
- Visualization generation

**[View Notebook](notebooks/quickbite_analysis.ipynb)**

---

## 4 Key Insights

### Customer Behavior
1. **Lost customers weren't actively churning** - they simply stopped using the service, presenting a recovery opportunity
2. **Loyal customers are gold** - 10% stayed through the crisis and deserve premium treatment
3. **New acquisition is possible** - 13,807 new customers joined despite the crisis

### Operational Failures
1. **Delivery performance is non-negotiable** - The 51-point drop in on-time delivery was catastrophic
2. **Cascading failures** - Food safety → delivery issues → poor service → mass exodus
3. **Monsoon vulnerability** - No weather-adaptive capacity planning

### Market Dynamics
1. **Trust is fragile** - 2-star rating drop shows how quickly reputation can be destroyed
2. **Competitors are opportunistic** - "Safe & Fast" campaigns were highly effective
3. **Restaurant partners are stakeholders** - 27% churn shows importance of partner relationships

---

##  Recommendations

### Three-Pillar Recovery Strategy

#### Pillar 1: Customer Reacquisition (₹4.37M)
- **Win-back campaign** targeting 73,000 lost customers
- **25% recovery target:** 18,250 customers
- **Tactics:** CEO apology video, 50% off first 3 orders, free delivery
- **Expected ROI:** 150.6%

#### Pillar 2: Operational Excellence (₹5.0M)
- **Deploy 500 additional delivery partners**
- **AI route optimization** (-8 min delivery time)
- **Target:** 85%+ on-time delivery in 6 months
- **Impact:** Cancellation rate < 5%

#### Pillar 3: Trust Rebuilding (₹3.0M)
- **Live hygiene ratings** for all restaurants
- **Real-time order tracking** (2-min updates)
- **24/7 customer support** (<1 hour response)
- **CEO quarterly video updates**

### Total Investment: ₹31.08M
### Expected 6-Month Revenue: ₹337.05M
### ROI: 984% | Payback Period: 2.2 months

---

##  Results & Impact

### Projected Outcomes (6 months)

**Customer Metrics:**
- 53,500 active customers (17,500 recovered + 25,000 new + 10,950 retained)
- Customer retention rate: 60%+
- Net Promoter Score: 40+

**Operational Metrics:**
- 85%+ on-time delivery
- <5% cancellation rate
- 4.0+ average rating
- 18,000+ restaurant partners

**Financial Metrics:**
- ₹56.18M monthly revenue
- ₹337.05M 6-month revenue
- 984% ROI
- Positive monthly cash flow by Month 6

---

##  Screenshots

### Dashboard Overview
![Dashboard Preview](screenshots/dashboard_preview.png)

### Customer Segmentation Analysis
![Segmentation](visualizations/2_customer_segments.png)

### Crisis Impact Timeline
![Timeline](visualizations/1_daily_orders_trend.png)

### Performance Metrics
![Metrics](visualizations/3_phase_comparison.png)

---

## Future Enhancements

### Analytical Enhancements
- [ ] Predictive modeling for customer churn
- [ ] Restaurant performance clustering
- [ ] Geographic heat maps for recovery focus
- [ ] Time-series forecasting for demand planning

### Technical Improvements
- [ ] SQL implementation for database integration
- [ ] Real-time dashboard with live data
- [ ] Automated reporting pipeline
- [ ] Machine learning for customer segmentation

### Business Extensions
- [ ] Competitive analysis dashboard
- [ ] Restaurant partner health score
- [ ] Marketing campaign effectiveness tracking
- [ ] Customer journey mapping

---

##  Author

**[Your Name]**
- 💼 LinkedIn: [www.linkedin.com/in/dominic-mwasya-70651425b]
- 🌐 Portfolio: [datascienceportfol.io/dominicmwasya]
- 📧 Email: [dominicmwasya02@gmail.com]
- 🐙 GitHub: [@yourusername](https://github.com/dominicmwasya)

---

##  Acknowledgments

- Dataset inspired by real-world food delivery challenges
- Analysis framework based on industry best practices
- Visualization design influenced by data storytelling principles

---

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---




