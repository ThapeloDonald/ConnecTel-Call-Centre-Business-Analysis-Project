# ConnecTel-Call-Centre-Business-Analysis-Project

### Project Overview
ConnectTel, a top telecom provider in South Africa, is facing high operational costs 
in its customer service call centre. They suspect inefficiencies in how calls are 
handled and how teams are managed. The goal is to run a diagnostic to uncover opportunities to reduce costs without hurting the customer experience.

### Data Source
ConnectTel CallCentre Data: The data set used for this analysis is sourced from Vuuma collaborations.

### Business Problem
ConnectTel is facing high operational costs in its customer service call centre.

#### The company needs to understand:
 - Is cost driven by volume or efficiency?
 - Are certain teams underperforming?
 - Are specific shifts inefficient?
 - Does experience impact cost?
 - What factors correlate most with cost per call?

 Without these insights, ConnecTel will keep on facing high operational costs and underperform operationally.

### Objectives
 - Identify what is driving cost.
 - Evaluate agents and team performance.
 - Identify which shifts are underperforming.
 - Provide actionable business recommendations.

### Dataset
 - 450 records.
 - Key Attributes:
   - Team (Team A, Team B, Team C).
   - Day (Monday, Tuesday, Wednesday, Thursday, Friday).
   - Agent (1-10).
   - Shift (Morning, Afternoon, Evening).
   - Experience (0-3 months, 3-6 months, 6+ months).
   - Calls Handled.
   - Average Call Duration.
   - Escalation Rate.
   - First Call Resolution Rate.
   - Customer Satisfaction Score (1-5).
   - Overtime Hours.
   - Cost Per Call.

### Methodology
 - Data cleaning and validation in Excel.
 - Correlation analysis for relationships.
 - Exploratory Data Analysis using Pivot Tables.
 - KPIs on Performance analysis (Total Calls, Total Calls Cost, Average Overtime Hours, Average Call Duration, Average Cost Per Call).
 - KPIs on Customer analysis (Average Escalation Rate, Average First Call Resolution Rate, Average Customer Satisfaction Score).
 - Dashboards creation for business insights.

### Tools and Skills Used
 - Microsoft Excel.
 - Advanced statistical analysis.
 - Pivot Tables & Charts.
 - Data Cleaning & EDA techniques.
 - Data Visualisation.

### Key Findings and Insights
#### 1. What drives costs?
<img width="384" height="270" alt="image" src="https://github.com/user-attachments/assets/d6a137f0-bb07-4cd0-b7c4-bb1a1d420c26" />   <img width="368" height="268" alt="image" src="https://github.com/user-attachments/assets/7c2211ed-e0f0-45da-a5a0-07da680b007c" />

Strong correlation with Cost Per Call:
 - Average Call Duration → 0.74
 - Overtime Hours → 0.71
 - Calls handled → 0

Key Insight: Cost is driven by inefficiency, not workload.

#### 2. Team Performance
<img width="940" height="187" alt="image" src="https://github.com/user-attachments/assets/7418e2e1-abcc-4e8b-9da7-56da6d488aec" />

Key findings:
 - Team B’s calls are ~24% longer.
 - Their cost per call is ~8–9% higher.
 - No customer satisfaction score advantage.

This indicates process inefficiency, not quality improvement.

#### 3. Shift Analysis
<img width="940" height="185" alt="image" src="https://github.com/user-attachments/assets/d082e49d-ffc9-47e4-b2f3-2e752115b27e" />

Evening Shift has:
 - Lowest first call resolution rate.
 - Similar cost to other shifts.

This likely drives hidden repeat-call costs.

#### 4. Experiance Impact
<img width="940" height="188" alt="image" src="https://github.com/user-attachments/assets/18c669d5-c938-4edd-b791-92a5ecedd7b1" />

New agents:
 - Escalate 2X more.
 - Use more overtime.
   
Training gap is likely increasing costs.

### Bussiness Recommendations
#### 1. Reduce Call Duration (Team B focus).
 - Audit scripts.
 - Standardise call flows.
 - Performance coaching.

Impact: ~7– 8% cost reduction potential.

#### 2. Improve Overtime Management
 - Better forecasting.
 - Smarter staffing allocation.
 - Approval thresholds.

Impact: ~3–5% savings.

#### 3. Improve Early-Tenure Training
 - 30 – 60 days coaching program.
 - Escalation reviews.
 - Mentorship pairing.

Impact: Reduce repeat workload + stabilise FCR rate.

### Risks and Assuptions
 - Shorter calls must not reduce customer satisfaction score.
 - Overtime reduction must not hurt service levels.
 - Repeat calls not fully captured in data.

### Recommended Next Steps
 - Run 4-week Team B pilot.
 - Conduct shift-level supervision review.

### Outcome
This analysis provides actionable insights that potentially reduces 7-10% overall cost ConnecTel Call Centre.










