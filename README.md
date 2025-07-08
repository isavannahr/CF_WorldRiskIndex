# World Risk Index

## About the Dataset

This dataset reports each country’s disaster risks annually. A disaster risk is a country more likely for 
“potential loss of life, injury or destroyed or damaged assets” due to “system, society or a community”.1 
The world risk index is a geometric mean of exposure and vulnerability. Exposure is the exposure to 
natural disasters that a population faces such as drought, earthquakes, tsunamis, etc. Vulnerability is 
composed of susceptibility coping, and adaptation.   
  - **Susceptibility** are the conditions of a society such as: socio-economic development, 
deprivation, disparities, disease and epidemic exposure within a country. A large susceptibility 
increases the likelihood that populations will be harmed in a disaster event. 
  - **Coping** involves how a society can counteract disaster events.  
  - **Adaptation** is the long-term processes put in place to avoid significant impacts from a disaster 
event.

## Objective  

The aim is to complete a global level analysis to determine where relief may be needed and to determine the 
types of risk management that would be effective to help people avoid potentially devastating 
impacts of disaster. Details about the columns as well as data consistency can be viewed within 
the jupyter notebook.

## Methodology

1. **Data Preparation**: Cleaned data by renaming columns, checking for missing data and duplicates. Cleaned data set yielded 1,915 WRI, Exposure, Vulnerability, Lack of Coping, Susceptibility and Lack of Adaptation level observations for 181 countries over 11 years (2011 – 2021).
2. **Regression and Cluster Analysis**: Use python machine learning commands (LinearRegression(), kmeans()) to analyze patterns, predictions and trends across various WRI features.
3. **Reporting**: Storytelling by Tableau visualizations such as pie charts, barcharts, boxplots, time-series, maps and butterfly charts. Defined important variables in dataset, visualized key points, reported a final hypothesis and gave recommendations for reducing risk worldwide.


# Tableau 

View final presentation here: https://public.tableau.com/app/profile/isavannah.reyes/viz/WRI_17483175830870/WorldRiskIndexAnalysis?publish=yes

# References

Bundnis Entwicklung Hilft. (2024). The World Risk Report. Retrieved from Bundnis Entwicklung Hilft: https://weltrisikobericht.de/worldriskreport/#  
Herring, D. (2020, October 29). What can we do to slow or stop global warming? Retrieved from Climate.gov: https://www.climate.gov/news-features/climate-qa/what-can-we-do-slow-or-stop-global-warming  
Kropf, C. M., Vaterlaus, L., & Pellissier, L. (2025). Tropical cyclone risk for global ecosystems in a changing climate. Nature Climate Change.  
United Nations Office for Disaster Risk Reduction (UNDRR). (n.d.). Definition: Disaster Risk. Retrieved from undrr.org: https://www.undrr.org/terminology/disaster-risk  
World Bank Group. (2021). Climate Risk Country Profile: Vanuatu. Washington DC: World Bank Group. Retrieved from https://climateknowledgeportal.worldbank.org/sites/default/files/country-profiles/15825-WB_Vanuatu%20Country%20Profile-WEB.pdf  

