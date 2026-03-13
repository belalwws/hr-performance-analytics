# HR Performance & Rewards Analytics Dashboard

A portfolio project simulating a real-world HR analytics deliverable — built to demonstrate data analysis, Excel modeling, and insight generation skills relevant to a **Performance & Rewards Specialist** role.

---

## Overview

This Excel workbook analyzes performance ratings, compensation, and attrition patterns for a simulated workforce of 50 employees. It is structured the way an HR analyst would present findings to senior management: raw data, summary dashboard, and a written insights report with actionable recommendations.

---

## File Structure

```
hr-performance-analytics/
│
├── HR_Performance_Analytics.xlsx   # Main workbook (3 sheets)
└── README.md
```

### Sheets

| Sheet | Description |
|---|---|
| **Employee Data** | 50 employees with department, job grade, performance rating, base salary, bonus, tenure, and employment status |
| **Performance Summary** | Dynamic dashboard with 4 analysis sections — all values via live Excel formulas |
| **Insights & Recommendations** | 5 structured findings with data evidence, risk level, and recommended actions |

---

## Dashboard Sections

**A. Performance Rating Distribution**
Breakdown of all 5 rating levels with count, % of workforce, and average salary per rating.

**B. Department Headcount & Compensation Summary**
Per-department view of headcount, active vs. resigned employees, turnover rate, average compensation, and average tenure.

**C. Salary Band Analysis by Job Grade**
Min, max, and average salary for each grade (G1–G5), plus salary spread to assess band width.

**D. Key Performance Indicators**
Summary cards covering total headcount, turnover rate, average compensation, total payroll, % high performers, and average tenure.

---

## Key Findings

- Departments with **below-average compensation had 2x higher turnover rate** than the company average
- **25% of employees** rated Below or Unsatisfactory — flagged for performance-linked pay policy review
- Engineering shows the **highest concentration of Outstanding ratings** — potential calibration inconsistency across departments
- Finance department has **bonus budget underutilization** — leftover budget not being tracked or reallocated

---

## Tools Used

| Tool | Purpose |
|---|---|
| Excel | Data modeling, formulas, dashboard layout |
| COUNTIF / AVERAGEIF / MINIFS / MAXIFS | Aggregation across filtered criteria |
| Conditional Formatting | Visual risk indicators |
| Python (openpyxl) | Workbook generation and formula injection |

---

## How to Use

1. Download `HR_Performance_Analytics.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. All dashboard values update automatically if you modify data in the **Employee Data** sheet
4. No macros or VBA — pure Excel formulas only

---

## Skills Demonstrated

- HR metrics: headcount analysis, turnover rate, salary bands, performance distribution
- Excel: Pivot-style formulas, dynamic cross-sheet references, structured reporting
- Data storytelling: translating numbers into management-ready recommendations
- Analytical thinking: identifying patterns, anomalies, and root cause hypotheses

---

## Author

**Belal Ahmed Mohamed**
[linkedin.com/in/belal-ahmid](https://linkedin.com/in/belal-ahmid) · [github.com/belalwws](https://github.com/belalwws)
