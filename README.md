# Private-Passenger-Automobile-Insurance

Our objective is to understand the relative risk of a policy, for each individual.
The relative risk of a policy, for each individual is given by relative pure premium, which is the ratio between pure premium for the individual and base pure premium (a particular pure premium value, taken as base).  

•Pure premium (calculated in units of money-currency) is given by the ratio between ‘total
dollars of claim losses’ and the ‘total number of autos’ insured. 

In our case study, we consider the risk factors, say, gender, geographical location and insurance scores, to have an affect on the relative risk of a policy.

An insurer’s ability in predicting a policy’s ultimate cost, determines how accurately a product is priced, and the extent to which adverse selection can be avoided. 
Under Property and Casualty Insurance, for example, say for a building, multiple factors such as the age of the insured building, its type of construction, its usage, are used to determine an appropriate premium (reflection of policy cost).
Insurers use predictive analytics to target potential clients, study their approach towards an insurance purchase, determine market specific products and 
identify potentially fraudulent claims.

Insurance policy makers weigh and combine selected credit attributes related to the concerned entity, to develop a single ‘insurance score’. This  gets added as a risk factor in accurately assessing the propensity for an insurance loss. 




•Note: . ‘Pure premium’ is
calculated in dollars, throughout our case study, even if it is
not mentioned each and every time, the term is used.

In order to perform the univariate analysis on our dummy dataset, we have adopted dummy variables, [male (M), female (F)-for gender], [north (N), south (S)-for geographical location (Say, we have divided an area into 2 regions-North & South)], each of which takes the value, 0 or 1, depending on the situation.

The interaction affects between the dummy variables, can be explained by variables (M*S, M*N, F*S, F*N) and we include our final explanatory variable I (insurance score). PP refers to pure premium, the explained variable.

Note: Dummy variables are qualitative variables, which can only be represented in yes (1) or no (0) format. 

