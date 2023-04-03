# Predictive-Analytics-of-Concrete-Compressive-Strength-
Supervised - Regression models 
Aim : To predict the compressive Strength of Concrete with the following parameters.
Input:
- $ Cement: $ g of cement (component 1) in a m^3 mixture.
- $ Slag : $ kg of blast furnace slag (component 2) in a m^3 mixture.
- $flyash : $ kg of fly ash (component 3) in a m63 mixture
- $water: $ kg of water (component 4) in a m^3 mixture.
- $superplasticizer: $ kg of super plasticizer (component 5) in a m^3 mixture.
- $coarseaggregate: $  kg of coarse aggregate (component 6) in a m^3 mixture.
- $fineaggregate: $  kg of fine aggregate (component 7) in a m^3 mixture.
- $Age: $  Day (1~365)
- $cs MPa $  Concrete compressive strength in MPa

MODELS USED:
Linear Regression
Lasso regression 
Ridge Regression
RandoM Forest
Decision trees Regressor
Gradient Boosting Regressor
KNN regressor
XG Boost regressor

#Hyper Parameter Tuning is performed for XGBoost, RandoMForest Regressor, and GradientBoosting Regressor. As, they give higher accuracy score in basic model.

Highest  r2 score is obtained by XGB Regressor is 0.9243
