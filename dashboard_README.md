# AI Impact on Jobs 2030 — Interactive Dashboard

An interactive data dashboard analyzing how AI is reshaping the global job market through 2030. Built with vanilla HTML, CSS, and JavaScript using Chart.js for visualizations.

**Live demo:** [sebastian435-sys.github.io/careerfit/dashboard.html](https://sebastian435-sys.github.io/careerfit/dashboard.html)

---

## Overview

This project conducts an exploratory data analysis (EDA) of 3,000 global job profiles to surface insights around AI replacement risk, salary trends, hiring outlook, and automation levels across industries, countries, and career stages.

---

## Key Findings

- **DevOps Engineers** face the highest AI replacement risk at 57% — infrastructure automation is accelerating faster than expected
- **UX Designers** are the most AI-resilient role at 46% risk — human empathy and creativity remain difficult to replicate
- **70% of roles** show high projected growth by 2030, suggesting AI creates more jobs than it eliminates in the near term
- **Finance** leads all industries in average salary at $132,017; Government is lowest at $120,626
- **AI tool usage does not correlate with higher pay** — workers with low AI tool usage earn slightly more than high users
- **Pakistan** has the highest average AI replacement risk (53%) among all countries analyzed

---

## Dashboard Sections

| Section | Description |
|---|---|
| KPI Cards | Total records, avg salary, avg AI risk, % high-growth roles |
| Hiring Trend 2026 | Growing / Stable / Declining breakdown |
| Job Growth by 2030 | High growth, moderate, flat, declining |
| Automation Level | Low / Medium / High distribution |
| Salary by Industry | Mean annual salary across 10 industries |
| AI Replacement Risk | Top 10 highest and lowest risk job titles |
| Salary by Education | High School vs. Bachelor vs. Master vs. PhD |
| Salary by AI Tool Usage | Low vs. Moderate vs. High AI adoption |
| Remote Work Distribution | On-site vs. Remote vs. Hybrid |
| Salary by Experience | Compensation across 5 career stages |
| Key Insights | 6 data-driven findings from the analysis |

---

## Dataset

**Source:** [AI Impact on Jobs 2030 — Kaggle](https://www.kaggle.com/)

| Field | Description |
|---|---|
| Job_Title | Role name |
| Industry | One of 10 industries |
| Country | One of 10 countries |
| Education_Level | High School / Bachelor / Master / PhD |
| Years_Experience | 0–30+ years |
| AI_Replacement_Risk | 0.0 – 1.0 score |
| Future_Demand_Score | Projected demand score |
| Remote_Work_Possibility | Yes / No / Hybrid |
| Average_Salary_USD | Annual salary |
| Automation_Level | Low / Medium / High |
| Job_Growth_2030 | % projected growth |
| Hiring_Trend_2026 | Growing / Stable / Declining |
| AI_Tool_Usage | Low / Moderate / High |
| Upskilling_Needed | Yes / No |

---

## Tech Stack

- **Python + Pandas** — data cleaning, aggregation, EDA
- **Vanilla HTML/CSS/JavaScript** — dashboard front end
- **Chart.js** — bar charts, line charts, doughnut charts
- **Google Fonts** — Inter + Space Grotesk
- **GitHub Pages** — deployment

---

## Project Structure

```
careerfit/
├── dashboard.html          # Full interactive dashboard (single file)
├── index.html              # CareerFit resume scorer app
└── README.md
```

---

## How to Run Locally

1. Clone the repo
```bash
git clone https://github.com/Sebastian435-sys/careerfit.git
cd careerfit
```

2. Open `dashboard.html` in any browser — no server or dependencies needed

---

## Built By

**Sebastian Gonzalez**
- LinkedIn: [linkedin.com/in/sebastian-g-ucla](https://linkedin.com/in/sebastian-g-ucla)
- GitHub: [github.com/Sebastian435-sys](https://github.com/Sebastian435-sys)
