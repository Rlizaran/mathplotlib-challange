# mathplotlib-Pymaceuticals
The power of Plots

## Background

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Observations and Insights
* Observations found after the filtering process and different analyticals approaches, we can conclude that the Drug Regimen most succesful are Capomulin and Ramicane.
* Capomulin has a Tumor Volume average of 40.676 mm3 while Ramicane has 40.217 mm3.
* The total amount of mice used on the experiment was 248 where 49.60% are Female and 50.40% are Male
* The Drug Regimen Infubinol, has an lower bound at 36.83 and an upper bound at 82.74 and it has possible outliers at 36.3213458
* The Drug Regimen Ceftamin, has an lower bound at 25.36 and an upper bound at 87.67 and has no outliers
* The Drug Regimen Ramicane, has an lower bound at 17.91 and an upper bound at 54.31 and has no outliers
* The Drug Regimen Capomulin, has an lower bound at 20.7 and an upper bound at 51.83 and has no outliers

![Tumor size](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/Images/Tumor%20Size%20by%20Drug%20Regime.png)


* After creating a regression line for Capomulin Regimen based on Average Tumor Volume vs. Weight, shown that the heavier the mouse, the bigger average tumor volume has. However, after randomly selecting a mouse from Capomulin Regimen, we observed that they always have a decline on tumor volume over time points.

![Tumor Mouse](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/Images/Tumor%20volume%20vs%20Time%20Point%20(days)%20of%20Mouse%2C%20treated%20with%20Capomulin.png)

* Regression line --> y = 0.95x + 21.55

![regression line](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/Images/Average%20Tumor%20Volume%20vs.%20Mouse%20Weight%20for%20Capomulin%20Regimen.png)

# Summary

I have found duplicate information attached to a specific mouse ID and it was been removed all the data related to that mouse ID as it was asked for the project, leaving a total of 248 mice in the study group. The mice gender population was found to be a total of 50.4% male and 49.6% female.  After comparing the results and observations with the help of a scatter graph and box graphs, we can conclude that the second-best Drug Regimen is Capomulin after Ramicane. The results are very promising and not very different than Ramicane.  Overall, the drug regimen is very effective in reducing the tumor volume over 45 days.

# File Description
### Images
* Images store from the main script
### data
* csv files used for the project 
  * [Mouse_metadata.csv](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/data/Mouse_metadata.csv)
  * [Study_results.csv](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/data/Study_results.csv)
### Main script
* [pymaceuticals_starter.ipynb](https://github.com/Rlizaran/mathplotlib-challenge/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb)
