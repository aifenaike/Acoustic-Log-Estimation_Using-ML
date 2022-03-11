# Acoustic-Log-Estimation_Using-ML


In most hydrocarbon fields, it is not uncommon for some log records to be absent. This could be as a result of incomplete logging, bad borehole conditions, damaged instruments, or data loss. In any of such cases, it is important to devise means of estimating some vital logs where absent. This repository presents a machine learning technique that integrates several logs for P-wave prediction to minimize errors and uncertainties associated with traditional estimation methods. The well borehole diameter and several logging measurements such as resistivity (RT), bulk density (RHOB), porosity (NPHI), radioactivity content (GR), and photoelectric absorption factor (PEF) of the formation, are used as predictors. 

## Objective
To provide a blueprint for predicting the values of missing p-sonic logs where needed. This project can be tweaked with appropriate modifications of the algorithms to any area of well logging studies, where missing log values are needed. 

## Dataset
The data used in this research is from the open database for the Volve oil field in Stavanger at the southern end of the Norwegian sector in the North Sea. 

## Model Architecture
Four intelligent models were used in this work.
- Gradient Boosting
- Random Forest
- Extreme gradient boosting
- Linear Regression
