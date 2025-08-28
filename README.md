# How Does Human Behavior Change Under Heat? Temperature-Induced Conflict Predictions.

## ⭐ Motivation
The motivation behind this project stems from a study by the Political Geography Journal that found that <a href="https://www.clisec.uni-hamburg.de/en/pdf/data/nordas-gleditsch-2007-climate-change-and-conflict.pdf" target="_blank">human-induced climate change can encourage more violent behavior</a>. Climate pressures have long been associated with violence, hence why this project explores whether rising temperatures can actually *predict* conflict occurrence at both the global level and within the Middle East region.  

The project aims to answer two core questions:  
1. **Global:** Can rising global temperatures predict the total number of global conflicts?  
2. **Middle East:** Can regional temperature trends predict the number of conflicts in the Middle East?  

---

## 📊 Data Set Up
- **<a href="https://ucdp.uu.se/downloads/" target="_blank">Conflict Data</a>:** Uppsala Conflict Data Program (UCDP) armed conflict dataset (Middle East and Global).
- **<a href="https://www.ncei.noaa.gov/cdo-web/datasets" target="_blank">Climate Data</a>:** National Oceanic and Atmospheric Administration’s (NOAA) Global and Middle East temperature dataset.  

---

## 🌡️ Approach to Predicting Conflict with Temperature
1. **Time Series Model:**
   - Purpose: Captures patterns, seasonality, and autocorrelation over time. This shows you whether the temporal dynamics are statistically significant. The paper runs diagnostics on the models to test their reliability.

2. **Time Series Regression Model:**  
   - Purpose: To quantify the relationship between temperature and conflict over time, while controlling for other covariates. This gives you a measure of how strong the relationship is. Diagnostics on the model were applied as well as significance testing.
  
3. **Forecast Model:**  
   - Purpose: To predict future conflict levels based on the fitted model. This determines whether the predictions are reliable visually as well as providing insights for uncertainty through confidence bands of forecasts.

---

## ✅ Main Takeaways
- **Global Conflict Prediction:** Rising global temperatures alone are not reliable predictors of worldwide conflict trends.  
- **Middle East Conflict Prediction:** Regional temperature fluctuations appear to have predictive power, indicating a stronger link between localized climate stress and conflict in the Middle East than with overall global temperatures and conflicts.  
- **Complex Interactions:** Conflict is shaped not only by climate but also by political, social, and economic structures (e.g., power distribution, resource competition, livelihood insecurity).   

