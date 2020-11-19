# Household Energy Prediction for Utility Load Forecasting

_Version 1.0_  
_Author(s): Jon Reifschneider, Duke University Pratt School of Engineering_

# Case Scenario
You are working as an analyst for the Canadian electic utility BC Hydro, which serves 1.8 million customers in British Columbia. You have been asked to work on the utility's load forecasting model for predicting future energy demand. Accurate demand prediction is critical for the utility to produce sufficient power to meet demand on a short-term and long-term basis.

The expansion of smart meter usage among many utilities has created increasing interest in machine learning models which predict energy demand at the individual home or building level, which can then be aggregated to a utility's entire territory. You have been asked to explore this approach using your organization's smart meter data. A review of advantages and limitations of different machine learning based approaches can be found <a href='https://www.informs-sim.org/wsc15papers/396.pdf'> here</a>.

In particular, you have been asked to better understand the relationship between changing weather conditions and the electric demand for a household. Your first objective is to examine the relationships between various weather parameters and electric consumption and determine which weather parameters most influence a home's energy usage. Once you have understood these relationships, you have been asked to evaluate different machine learning approaches to modeling a home's energy usage and report back to your team on what features are most valuable to use in prediction, which modeling approach(es) have shown most promise, and how well you are able to predict load at an individual home level.

# About this Teaching Case
**Level:** Intermediate  
**Language:** Python  
**Libraries:** pandas, matplotlib, scikit learn  
**Industry:** Energy

**Learning Topics:**  
- Time Series
- Exploratory Data Analysis
- Feature Engineering & Feature Selection
- Supervised Learning Model Selection
- Hyperparameter Tuning

**Learning Objectives**   
- Learn strategies for feature engineering and creation with time series data
- Build skills in exploratory data analysis using visual and statistical analysis techniques
- Learn how to apply the different methods of feature selection
- Build experience in supervised model selection, tuning and validation/testing

**Pre-requisites**  
- Basic proficiency in Python and pandas
- Familiarity with the theoretical foundations of supervised machine learning algorithms

**Case Structure**  
This teaching case is structured to follow the ***Modified CRISP-DM Data Science Process*** used in Duke University's AI for Product Innovation graduate programs. 

**Datasets Used**  
Makonin, S., Ellert, B., Bajić, I. et al. Electricity, water, and natural gas consumption of a residential house in Canada from 2012 to 2014. Sci Data 3, 160037 (2016). https://doi.org/10.1038/sdata.2016.37

Data has been adapted from the original dataset for purposes of this learning activity. The original dataset can be accessed from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FIE0S4