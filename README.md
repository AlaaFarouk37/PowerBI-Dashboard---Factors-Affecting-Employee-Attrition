# PowerBI-Dashboard---Factors-Affecting-Employee-Attrition
HR Attrition Dashboard Analyzing Factors Behind Employee Attrition.

Tools I used: Power BI, Power Query, DAX Measures

# Why Do Employees Leave? An HR Attrition Dashboard in Power BI

I wanted to answer one question: **what makes employees leave a company?**

I built a Power BI dashboard on a synthetic HR dataset of 70k+ employees to find out. Tools: Power BI, Power Query, DAX.

## How the project started

My first plan was to focus on high and average performers and ask why they leave. Then I looked at the data. It is synthetic and balanced, and attrition was about the same across every performance rating. Performance did not separate leavers from stayers.

So I widened the question to all employees, at every performance level.

## The data

- 70k+ synthetic employee records, 24 fields
- Demographics, job details (role, level, income), work conditions (remote work, overtime) and self-reported ratings (job satisfaction, work-life balance)
- Target column: Attrition (Left / Stayed)

## Data Prepartion

- Turned Attrition into 1/0, so an average gives the attrition rate
- Converted employee ratings from text (Poor, Fair, Good, Excellent) to scores (1 to 4) in Power Query

## What the dashboard shows

Two KPI cards: overall attrition rate and employee count. Then four visuals, one for each factor I looked at:

- Remote work
- Work-life balance
- Job level
- Number of promotions

A Company Size slicer lets you narrow it down.

## What I found

**Remote work made the biggest difference.** 24.7% of employees with remote work left, compared with 52.84% of those without it.

**Better work-life balance, fewer exits.** Attrition was highest where work-life balance was rated poor and fell as ratings improved.

**Entry level leaves the most.** Attrition was 63% at entry level and 45% at mid level, even though both groups are about the same size. So the gap is not just a matter of headcount.

**Promotions matter.** Employees with 0 to 2 promotions left at 48%, against 25% for those with 3 or more.
