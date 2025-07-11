📌 Executive Summary
This project helps HR managers and business leaders predict which employees are most likely to seek new job opportunities. By analyzing key employee attributes, we identify high-risk candidates and provide actionable insights to improve retention strategies.
![Uploading image.png…]()

🔑 Key Business Insights
✅ 25% of employees are actively looking for new jobs – a significant attrition risk.
✅ Employees in mid-career (2-6 years experience) are most likely to leave – suggesting a "career growth gap."
✅ City Development Index (CDI) impacts retention – employees in both very high and very low CDI areas are more likely to seek change.
✅ STEM professionals dominate attrition cases – critical for tech-driven companies.
✅ Employees who never changed jobs or changed recently are higher risks – indicating either stagnation or "job-hopping" tendencies.

📊 Why This Matters for HR Teams
1. Reduce Turnover Costs
Hiring and training replacements can cost 6-9 months of an employee's salary.

Predictive analytics helps prevent attrition before it happens.

2. Improve Employee Retention Strategies
Identify high-risk employees before they leave.

Tailor personalized retention plans (promotions, upskilling, flexibility).

3. Optimize Hiring & Workforce Planning
Understand which profiles are most likely to stay long-term.

Adjust recruitment strategies to target more stable candidates.

🔍 How We Analyzed the Data
We examined 14,000+ employee records, including:

Demographics (gender, education)

Work History (experience, last job change)

Company Factors (size, type, training hours)

Geographic Data (City Development Index)

📈 Key Findings in Simple Terms
Factor	Impact on Job Seeking
Low/High CDI	🚨 Higher risk
2-6 Years Experience	🚨 Most likely to leave
STEM Background	🚨 High turnover risk
Recent Job Changes	⚠️ Higher risk
Long Tenure (No Change)	⚠️ Potential stagnation risk
🤖 Predictive Model: How It Works
We built a machine learning model that predicts which employees are likely to leave with 74.8% accuracy.

🔮 Model Predictions Help HR Teams:
✔ Flag high-risk employees for proactive retention efforts.
✔ Understand key drivers of attrition (salary, role stagnation, location).
✔ Test "what-if" scenarios (e.g., impact of training programs on retention).

📉 Without This Model, Companies Risk:
❌ Unexpected resignations (losing top talent without warning).
❌ Higher recruitment costs (reactive hiring is expensive).
❌ Lower team morale (frequent turnover disrupts productivity).

🚀 Recommended HR Actions
Based on our findings, we recommend:

1. Targeted Retention Programs
Career path planning for employees with 2-6 years tenure.

Flexible work policies for employees in low-CDI cities.

2. Proactive Check-Ins
Quarterly stay interviews for high-risk employees.

Mentorship programs for STEM professionals.

3. Smarter Hiring Strategies
Prioritize candidates with stable job histories.

Adjust compensation benchmarks for high-attrition roles.

📂 Repository Structure
text
hr-analytics-employee-attrition-prediction/  
├── data/  
│   ├── aug_train.csv          # Training dataset  
│   └── aug_test.csv           # Test dataset  
├── notebooks/  
│   └── HR_Analytics.ipynb     # Full analysis & model code  
├── outputs/  
│   └── visualizations/        # Charts & insights  
└── README.md                  # This document  
📌 How HR Managers Can Use This
Run the model to identify at-risk employees.

Review insights to adjust retention policies.

Test interventions (training, promotions) and measure impact.

💡 Next Steps:

Deploy model for real-time attrition risk scoring.

Integrate with HRIS (Workday, BambooHR) for automated alerts.
