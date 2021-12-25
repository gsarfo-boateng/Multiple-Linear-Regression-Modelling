# Multiple-Linear-Regression-Modelling
Multiple Linear Regression for Estimating Invasive Meningitis Disease (IMD)
Meningococcal disease refers to any illness caused by bacteria called Neisseria meningitidis, also known as meningococcus. These illnesses are often severe and can be deadly. They include infections of the lining of the brain and spinal cord (meningitis) and bloodstream infections (bacteremia or septicemia).

These bacteria spread through the exchange of respiratory and throat secretions like spit (e.g., by living in close quarters, kissing). Doctors treat meningococcal disease with antibiotics, but quick medical attention is extremely important. Keeping up to date with recommended vaccines is the best defense against meningococcal disease.

Antibiotics Resistance 

Recent reports of β-lactamase-producing N. meningitidis serogroup Y in the United States, including eleven cases also resistant to ciprofloxacin. CDC has new information for healthcare providers and public health staff to consider regarding treatment, prophylaxis, and surveillance activities based on these findings.

Signs and Symptoms 

Signs and symptoms of meningococcal disease usually start suddenly and include fever, headache, and a stiff neck. It can start with symptoms similar to influenza (flu).  Often people with meningococcal disease also have nausea, vomiting, increased sensitivity to light, rash, and confusion. Learn more about signs and symptoms.

Multiple Linear Regression

Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. Its goal is to model the linear relationship between the explanatory (independent) variables and response (dependent) variables. In essence, multiple regression is the extension of ordinary least-squares (OLS) regression because it involves more than one explanatory variable.

Formula and Calculation of Multiple Linear Regression

yi=β0+β1xi1+β2xi2+...+βpxip+ϵ
where, for i=n

 observations:
 
yi=dependent variable

xi=explanatory variables

β0= y-intercept (constant term)

βp= slope coefficients for each explanatory variable

ϵ= the model’s error term (also known as the residuals)
 
The coefficient of determination (R-squared) is a statistical metric that is used to measure how much of the variation in outcome can be explained by the variation in the independent variables. R^2 always increases as more predictors are added to the MLR model, even though the predictors may not be related to the outcome variable.

R2 by itself can't thus be used to identify which predictors should be included in a model and which should be excluded. R2 can only be between 0 and 1, where 0 indicates that the outcome cannot be predicted by any of the independent variables and 1 indicates that the outcome can be predicted without error from the independent variables.

I use ML Regression analysis to estimate the IMD of N. Meningitis infection in two Datasets. See https://www.hindawi.com/journals/cmmm/2020/5105120/ for the actual paper for your reference. 
	
