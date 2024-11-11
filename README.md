# Econometrics Project: The Impact of Police Presence on Crime Rates

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Findings and Insights](#findings-and-insights)
  
## Project Overview
This project investigates the complex relationship between police presence and crime rates across U.S. counties. By examining socioeconomic, crime, and law enforcement data, this analysis provides insights into how policing practices impact crime reduction. Inspired by the study of Cornwell and Trumbull (1994), it explores potential strategies for effective crime control. The analysis examines:
- Crime Rate Trends: Investigates year-to-year changes in crime rates at the county level.
- Law Enforcement Effectiveness: Evaluates the role of arrest probability, conviction rates, sentencing, and police per capita on crime deterrence.
- Economic and Social Context: Considers the influence of factors like population density, tax rates, and labor market composition on crime rates.
- Modeling Techniques: Builds a regression model to quantify the impact of police presence while addressing multicollinearity. 
## Data Description
The dataset, crime4.csv, includes 51 variables across multiple counties and years. Key variables:
- crmrte: Crime rate in each county.
- prbarr, prbconv, prbpris: Probabilities of arrest, conviction, and imprisonment.
- polpc: Police presence per capita.
- Socioeconomic indicators such as density, taxpc, and pctmin80.
This data allows for a robust analysis of how police presence and socioeconomic factors influence crime rates.
## Methodology
This analysis uses multiple linear regression models to understand the impact of police presence on crime rates. Various socioeconomic and law enforcement variables are included as predictors. The study also addresses potential multicollinearity among predictors and evaluates model performance based on explained variance. Python libraries such as statsmodels and sklearn are used for statistical modeling and analysis.
## Findings and Insights
The final model explained 95.3% of the variance in crime rates, highlighting the significant role of police presence in reducing crime. Additionally, socioeconomic factors showed notable effects, suggesting that addressing crime requires a holistic approach, integrating both policing and social policies.
