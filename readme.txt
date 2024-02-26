This is part of my master thesis entitled "Unraveling Circular Pathways: Using Causal Machine Learning in Exploring Causal Relationships for Sustainable Economies"

Discussion

Traditional vs Causal Machine Learning

After doing the four steps in causal analysis, namely creating a causal graph, identifying estimands, estimating estimand effects, and refuting the results; no variable showed significant causal relationship 
with the circular material use rate. Although both correlation and estimated causal effects were low, it showed that there are differences in results when using correlation and using causal analysis when 
analyzing the relationships between variables. GDP and waste collection coverage had the highest correlation with circular material use rate while recycling rate had the highest estimated causal effect when 
confounding variables are considered. The coefficients in the simple linear model also showed different results from the causal models since the simple linear model does not consider the relationships between 
the variables.

Causal Machine learning

The double machine learning model resulted in smaller estimated causal effect than the linear causal model. This may be because DML considers the relationship between the confounding variables and the 
treatment and between the variables and the outcome. All models showed no significant causal relationship between the variables and the circular material use rate. If there really is no actual or no 
trong causal relationship between the variables, then DML showing a lower estimated causal effect may imply that DML would be a better model for causal analysis, especially for more complex data. The DML 
also showed promising values for the new estimated effect after refutation, although the p-values were high to make a statistically supported claim. Even if the p-values after refutation in DML were low, 
the estimated causal effect of recycling rate was also low, only with a 0.02 increase in circular material use rate per unit increase in recycling rate.

Implications

The chosen variables showed a weak causal relationship with circular material use rate, with Recycling Rate having the highest estimated causal effect of 0.11 according to linear causal model and 
only 0.02 according to DML model. Considering that the recycling rate has a mean of 55% and the circular material use rate has a mean of 8%, the causal effect of 0.11 can be considerable. This means 
that the increase of 1 percentage point in recycling rate would mean an increase of 0.11 percentage points in circular material use rate. However, the DML model showing that the estimated causal effect 
is only 0.02 seems to imply that recycling does not really help with circular material use rate, nonetheless, it is important to note that the circularity of an economy does not only depend on the circular
material use rate. There are many factors and variables that can indicate a nation’s progress towards a circular economy.

Another main factor that affected the results is that the data set involved all countries and sovereign states in the world, including those that do not have active efforts towards a circular economy. The 
results may also imply that the recycling efforts in context of the whole world is not yet enough to show significant causal relationship to circular material use rate. It may be best to conduct more research 
focusing on countries that are actively trying to achieve sustainable development.
It is also important to note that circular material use rate also considers the usage of raw materials. Even if the usage of circulated is high, if the amount of raw materials used is also high, then 
circular material use rate remains the same.

Although having a high circular material use rate is a good indicator of a sustainable circular economy, a perfectly circular economy would be almost unachievable as there would always be unavoidable
waste. Losses in the material cycle will always be present and can be reduced through optimization processes that also require additional resources (Desing and Blum, 2023). For future work, researchers 
can focus on strategies that reduce environmental impacts instead of maximizing the amount circulated materials.


Limitations and Recommendations for Future Work
One factor that may have affected the results is the imputation of data. Most of the data in the analysis were imputed by iterative imputer and are not based on real data. For future work, finding a 
complete data set is recommended to have more reliable results. The variables selected and the causal graph were also only based on the limited domain knowledge of the researcher. For best results, a 
blend between causal machine learning and an expertise on the domain is highly recommended. The appropriate selection of variables for analysis and the proper creation of the causal graph is of high 
importance, especially since there are numerous indicators and variables that can be a measure of sustainability.

As already discussed in the implications section, the data included all the countries and sovereign states in the world, this could have impacted the results as not all countries have active efforts 
towards sustainability. Selecting only countries which have notable efforts regarding having a sustainable circular economy would be a good case for future studies. Time-varying data would also be an 
interesting case to study, especially for countries that are actively trying to improve their circular economy.

If there were significant causal relationship found between the variables, it is highly suggested to apply and compare more causal models to identify which model works best in predicting the outcome
based on the treatment and other variables.
