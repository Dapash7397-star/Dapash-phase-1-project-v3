# Aviation Risk Analysis Project

## Overview
This project analyzes aviation accident data to provide insights into aircraft safety and risk levels.  
The analysis was conducted using Python, Pandas, and Tableau to clean, analyze, and visualize aviation accident data.  
The ultimate goal is to identify patterns that can help business stakeholders make informed decisions about entering the aviation industry.

---

## Business Understanding
The primary objective of this analysis is to determine the **lowest-risk aircraft** for a company planning to enter the aviation industry.  

### Stakeholders
- **Business executives**: Need to understand risk levels before investing in aircraft.  
- **Safety officers/regulators**: Want evidence-based insights on aircraft risks.  
- **Investors**: Require data-driven justifications for strategic decisions.  

### Key Business Questions
1. Which types of aircraft are most associated with fatal accidents?  
2. How have aviation accidents trended over time?  
3. Which regions or countries report the highest number of accidents?  

---

## Data Understanding and Analysis

### Source of Data
- **Dataset**: National Transportation Safety Board (NTSB) aviation accident data (1962–2023).  
- **Link**: [NTSB Accident Data](https://www.ntsb.gov/)  

### Description of Data
- **Columns**: Year, Country, Aircraft Damage, Fatalities, Injuries, Aircraft Type, etc.  
- **Size**: Civil aviation accidents and selected incidents across the United States and international waters.  
- **Cleaning & Preparation**: Missing values handled by imputation/removal, categorical variables standardized.  

### Visualizations

#### 1. Yearly Accident Trends
<img width="647" height="333" alt="image" src="https://github.com/user-attachments/assets/06d95af1-5c1c-4a87-a546-b6c918cf5d3b" />

*A line chart showing the number of accidents per year, categorized by injury severity.*  

#### 2. Aircraft Damage vs. Fatal Incidents
<img width="402" height="278" alt="image" src="https://github.com/user-attachments/assets/13143e9d-8468-4418-9c44-d303613c6d0e" />
  
*A stacked bar chart comparing aircraft damage categories against fatal incidents.*  

#### 3. Geographic Distribution of Accidents
<img width="730" height="333" alt="image" src="https://github.com/user-attachments/assets/cf25b8ba-a6d1-401c-bc02-d1f1afc6164b" />



*A map visualization showing accident counts by country.*  

---

## Conclusion

### Summary of Findings
1. **Accident trends have decreased over time**, especially in the past two decades, reflecting improved aviation safety standards.  
2. **Certain aircraft types are more prone to fatal accidents**, highlighting the importance of careful fleet selection.  
3. **Accidents are concentrated in specific regions**, suggesting that geographic factors influence aviation risk.  

### Next Steps
- Recommend fleet investment in aircraft types with historically lower fatality rates.  
- Continue monitoring global accident data for updated trends.  
- Combine accident data with maintenance and operational cost data for a full risk-benefit analysis.  

---

