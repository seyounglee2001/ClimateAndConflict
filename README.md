# Can Temperature Variations Predict Armed Conflict?

## ⭐ Motivation
The motivation behind this project stems from a study by the Political Geography Journal that found that human-induced climate change can encourage more violent behavior. While climate pressures such as water scarcity, food insecurity, and economic instability have long been associated with violence, this project explores whether rising temperatures can actually *predict* conflict occurrence at both the global level and within the Middle East region.  

The project aims to answer two core questions:  
1. **Global:** Can rising global temperatures predict the total number of global conflicts?  
2. **Middle East:** Can regional temperature trends predict the number of conflicts in the Middle East?  

---

## 📊 Data Set Up
- **Conflict Data:** Uppsala Conflict Data Program (UCDP) armed conflict dataset (Middle East and Global).
- **Climate Data:** Global and Middle East temperature trends from publicly available climate records (Middle East and Global).  

---

## 🌡️ Approach to Predicting Conflict with Temperature
1. **Time Series Model:**
   - Motivation:
   - Global: Implemented SARIMA(1,1,1)(2,0,0)[12] and SARIMA(2,1,1)(2,0,0)[12] models.
   - Middle East: Applied SARIMA(1,1,2)(0,0,2)[12] to regional temperature and conflict data.  

3. **Time Series Regression Model:**  
   - Motivation:

4. **Forecast Model:**  
   - Motivation:

---

## ✅ Main Takeaways
- **Global Conflict Prediction:** Rising global temperatures alone are not reliable predictors of worldwide conflict trends.  
- **Middle East Conflict Prediction:** Regional temperature fluctuations appear to have predictive power, indicating a stronger link between localized climate stress and conflict in the Middle East than with overall global temperatures and conflicts.  
- **Complex Interactions:** Conflict is shaped not only by climate but also by political, social, and economic structures (e.g., power distribution, resource competition, livelihood insecurity).   

