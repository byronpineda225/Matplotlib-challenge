# Matplotlib Homework - The Power of Plots

## Background

![Laboratory](Images/Laboratory.jpg)

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Observations and Insights

1) Please note that a female mouse identified as "g989" was removed from the analysis as there was duplication of data for that particular mouse. That left 123 female and 125 male mice for a total of 248 for this study making for a fairly even distribution between sexes.

2) The correlation between mouse weight and the average tumor volume was 0.84 for the Capomulin regimen as seen in the the last scatter plot. This indicates a strong positive relationship between higher mouse weight and increased average tumor volume specifically with the Capomulin regime. The subject mice weight started around 15 (g) and the average tumor volume was roughly 36 (mm3). The heaviest mice weighed roughly 25 (g) and the tumor volume increased to nearly 46 (mm3). It should be noted that the Capomulin regimen also had the most participants at 230 mice for this study.

3) The Linear regression for this particular study for the Capomulin is y = 0.95x + 21.55, where the variable being predicted or dependent variable is the tumor volume (y value) and the variable that is the predictor (x) or independent variable is the mouse weight. The R-squared value is nearly .71 for this particular study. This represents a fairly small difference between the observed data and predicted values. In addition,the p-value is extremely small at 1.3225722434712642e-07. This is well below the standard p-value cutoff of .05. The stderr, which quantifies the uncertainty of the estimates, shows it is just 0.12754359033201335 - a very low number indeed. All of these indicate the our linear regression model is a good fit for the data.

4) The box plots of the final tumor volume of each mouse across the regimens Capomulin, Ramicane, Infubinol, and Ceftamin show that Capomulin and Ramicane were significantly more effective at reducing tumor volumes. Specifically this is what the median values show for the four regimens in this part of the study:

The median of Capomulin tumors: 38.125164399999996 
The median of Ramicane tumors: 36.56165229 
The median of Infubinol tumors: 60.16518046
The median of Ceftamin tumors: 59.85195552 
