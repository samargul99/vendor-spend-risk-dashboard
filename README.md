# Vendor Spend & Risk Dashboard (Excel)

This dashboard analyzes vendor spend data to identify savings opportunities, cost overruns, and project risks.  
It was built in **Excel** using PivotTables, conditional formatting, and charts.

---

## Steps Taken
1. Collected vendor spend and cost variance data.
2. Built PivotTables to calculate:
   - Total Savings
   - Total Overruns
   - % Projects Below Average
   - Savings Rate
3. Applied conditional formatting for **risk categories** (High, Slight, On Track).
4. Created charts (Trend, Risk breakdown, Outlier distribution).

---

## Key Formulas Used
- Variance:  
  =Actual_Cost - Planned_Cost

- Savings Rate (%):

= (Old_Cost - New_Cost) / Old_Cost

Risk Categorization (using IF):

=IF(Variance > 0.2, "High Risk", IF(Variance > 0.05, "Slight Risk", "On Track"))

## Outputs

📊 Dashboard with KPIs (savings, overruns, project risk).

📈 Trend charts showing variance over time.

🟢 Enhanced visibility for leadership decision-making.

