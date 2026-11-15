# HR Employee Attrition Analysis | Excel Dashboard

An interactive Excel dashboard that analyses **1,470 employee records** to find out **who is leaving the company, and why**. Built with Pivot Tables, Pivot Charts, Slicers and KPI cards.

<img width="1356" height="627" alt="image" src="https://github.com/user-attachments/assets/1be5142f-5b8a-4712-9ae3-f99693752fda" />

<!-- Add a screenshot of your Dashboard sheet at images/dashboard.png -->

---

## Business Problem

Employee attrition is expensive: hiring, onboarding and lost productivity all add up. HR leadership wanted answers to:

- What is the overall attrition rate?
- Which departments, job roles and age groups lose the most people?
- Do factors like overtime, income, marital status or work-life balance influence who leaves?

## Key KPIs

| Metric | Value |
|---|---|
| Total Employees | **1,470** |
| Employees Who Left (Attrition) | **237** |
| Active Employees | **1,233** |
| Attrition Rate | **16.1%** |
| Average Age | **36.9 years** |
| Average Job Satisfaction | **2.63 / 4** |

## Key Insights

**1. Early-career and junior staff leave the most**
- Employees **under 25** have a **39.2%** attrition rate, versus about **10%** for ages 35 to 54.
- **Job Level 1** employees leave at **26.3%**, compared with under 5% at Levels 4 and 5.

**2. Sales Representatives are the highest-risk role**
- Sales Representatives: **39.8%**, Laboratory Technicians: **23.9%**, HR: **23.1%**.
- Research Directors (**2.5%**) and Managers (**4.9%**) are the most stable.

**3. Overtime is the biggest warning sign**
- Employees working overtime leave at **30.5%**, against **10.4%** for those who don't.

**4. Single employees are far more likely to leave**
- Single: **25.5%**, Married: **12.5%**, Divorced: **10.1%**.

**5. Pay, tenure and travel matter**
- Leavers earned about **$4,787/month** on average, versus **$6,833** for those who stayed.
- Leavers had about **5.1 years** at the company, versus **7.4** for stayers.
- Frequent travellers leave at **24.9%**, against **8.0%** for non-travellers.

**6. Poor work-life balance and no stock options**
- Work-life balance rated 1 (lowest): **31.2%** attrition.
- No stock options: **24.4%**, versus **7.6 to 9.4%** for stock option levels 1 and 2.

**7. By department**
- R&D accounts for the most leavers in absolute numbers (**133 of 237, 56%**), but Sales has the highest rate (**20.6%**).

## Recommendations

1. **Limit overtime**, especially for junior roles. It is the strongest single driver of attrition.
2. **Build a retention plan for Sales Representatives** (better pay structure, clearer career path).
3. **Improve onboarding and mentoring** for employees under 25 and at Job Level 1.
4. **Expand stock options / equity** to employees currently at level 0.
5. **Review travel load** for frequent travellers and flag low work-life-balance scores for manager check-ins.

## Dashboard Features

- KPI cards: total employees, attrition count, active employees, attrition rate, average age
- Doughnut charts: job satisfaction rating and gender split (60% male / 40% female)
- Attrition by **Department, Job Role, Age Group, Education and Marital Status**
- **Slicers** for Gender, Department, Education, Education Field and Marital Status, so the whole dashboard filters interactively

## Tools and Techniques

- **Microsoft Excel**: Pivot Tables, Pivot Charts, Slicers, calculated KPI fields
- **Data preparation**: helper columns for age bands, attrition labels, attrition count and rate (`CF_` columns)
- **Dashboard design**: custom backgrounds and layout for a clean one-page view

## Dataset

- **Rows:** 1,470 employees
- **Columns:** 44, covering demographics (age, gender, marital status), job details (department, role, level, income), satisfaction scores, work-life balance, overtime, travel, and tenure
- Based on the popular IBM HR Analytics Employee Attrition dataset

## Repository Structure

```
HR-Employee-Attrition-Analysis/
│
├── HR-Employee-Analysis.xlsx   # Full workbook (data, pivots, dashboard)
├── README.md                   # Project documentation
└── images/
    └── dashboard.png           # Dashboard screenshot
```

## How to Use

1. Download `HR-Employee-Analysis.xlsx`.
2. Open it in Microsoft Excel (desktop version recommended, since slicers need it).
3. Go to the **Dashboard** sheet and click the slicers to filter the data.

## What I Learned

- Turning raw HR data into a decision-ready dashboard
- Building interactive reports with slicers connected to multiple pivot tables
- Translating numbers into business recommendations

## Author

**Your Name**
[LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username) | your.email@example.com
