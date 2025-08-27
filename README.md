# Climate Change and Armed Conflict Prediction

## Purpose
This project explores the relationship between temperature increases and the occurrence of armed conflict. While climate pressures such as water scarcity, food insecurity, and economic instability have long been associated with violence, this research investigates whether rising temperatures can *predict* conflict occurrence at both the global level and within the Middle East and North Africa (MENA) region.  

The study aims to answer two core questions:  
1. **Global:** Can rising global temperatures predict the total number of global conflicts?  
2. **Middle East:** Can regional temperature trends predict the number of conflicts in the Middle East?  

---

## Data Set Up
- **Conflict Data:** Uppsala Conflict Data Program (UCDP) armed conflict dataset.  
- **Climate Data:** Global and regional temperature trends from publicly available climate records.  
- **Scope:** Two levels of analysis were conducted—global and regional (Middle East).  
- **Models Used:** Time series forecasting models (SARIMA family) applied to capture relationships between temperature and conflict counts.

---

## Approach to Predicting Conflict with Temperature
1. **Global Analysis:**  
   - Implemented SARIMA(1,1,1)(2,0,0)[12] and SARIMA(2,1,1)(2,0,0)[12] models.  
   - Tested the predictive ability of global temperatures on the total number of global conflicts.  

2. **Middle East Analysis:**  
   - Applied SARIMA(1,1,2)(0,0,2)[12] to regional temperature and conflict data.  
   - Found evidence that regional temperatures are significantly associated with the number of conflicts in the Middle East.  

3. **Forecasting**  


---

## Main Takeaways
- **Global Conflict Prediction:** Rising global temperatures alone are not reliable predictors of worldwide conflict trends.  
- **Middle East Conflict Prediction:** Regional temperature fluctuations appear to have predictive power, indicating a stronger link between localized climate stress and conflict in the Middle East than with overall global temperatures and conflicts.  
 
- **Complex Interactions:** Conflict is shaped not only by climate but also by political, social, and economic structures (e.g., power distribution, resource competition, livelihood insecurity).  
- **Policy Implications:** Addressing environmental stress in combination with governance, inequality, and resilience strategies is critical for reducing conflict risks.  

