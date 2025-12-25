# NBA Awards Analysis (1989–2024)

This project analyzes historical NBA award winners to understand how the statistical profiles of elite players have evolved over time.  
The focus is on three major individual awards:

- Most Valuable Player (MVP)
- Defensive Player of the Year (DPOY)
- Rookie of the Year (ROY)

The analysis explores how evaluation criteria have shifted from raw volume-based dominance toward efficiency, context, and per-minute impact.

---

## 🎯 Project Objectives

- Identify long-term statistical trends among NBA award winners
- Compare total impact versus per-minute efficiency
- Understand how modern award evaluation differs from earlier eras
- Provide a clear, descriptive, and data-driven perspective on player value

This project uses **descriptive analysis and correlation analysis**, not machine learning.

---

## 📊 Data & Metrics

All metrics are analyzed at the **player-season level**.

### Key Metrics
- **Production:** PTS, TRB, AST  
- **Defense:** STL, BLK  
- **Efficiency:** FG%  
- **Impact:** Win Shares (WS), Win Shares per 48 Minutes (WS/48)

Data is grouped by **year** and **decade** to highlight both short-term variability and long-term structural trends.

---

## 📂 Workbook Structure

The Excel workbook is organized as follows:

- **README** – Project overview and key findings
- **Data_MVP / Data_DPOY / Data_ROY** – Cleaned datasets
- **MVP_Decade_Summary / DPOY_Decade_Summary / ROY_Decade_Summary**  
  Decade-level pivot summaries and bar charts
- **MVP_Evolution / DPOY_Evolution / ROY_Evolution**  
  Year-by-year trend analysis
- **Correlation_MVP / Correlation_DPOY**  
  Correlation analysis between performance metrics and impact
- **Final_Insights_MVP / Final_Insights_DPOY / Final_Insights_ROY**  
  Key conclusions for each award
- **Final_Insights_Overall**  
  Cross-award synthesis and league-wide conclusions

---

## 🏆 Key Findings

### MVP
- Scoring (PTS) and shooting efficiency (FG%) increase consistently over time
- Total impact (WS) remains relatively stable
- WS/48 shows a clear upward trend, indicating higher per-minute value
- Modern MVPs deliver elite impact through efficiency rather than raw volume

### DPOY
- Raw defensive volume (TRB, BLK) declines across decades
- WS/48 remains stable or slightly increases
- Defensive excellence is increasingly efficiency-driven and role-specific

### ROY
- Both WS and WS/48 decline over time
- Modern rookies are integrated more gradually
- The award increasingly reflects long-term potential rather than immediate dominance

---

## 🔍 Correlation Insights

- MVP impact (WS) shows a moderate correlation with scoring volume (PTS)
- The strongest relationship appears between WS/48 and shooting efficiency (FG%)
- Defensive box-score stats show weaker correlations, especially for MVP selection
- Results reinforce the shift toward efficiency, context, and optimized usage

---

## 📌 Conclusion

Across MVP, DPOY, and ROY, the data highlights a league-wide evolution:

- From volume-based dominance
- Toward efficiency-driven, context-aware, and role-optimized performance

Modern NBA awards increasingly reward **how efficiently value is generated**, not just how much is accumulated.

---

## 🛠 Tools Used

- Microsoft Excel
- Pivot Tables
- Charts and Dashboards
- Correlation Analysis

---

## 📎 File

- `NBA_Awards_Analysis_1989_2024.xlsx`
