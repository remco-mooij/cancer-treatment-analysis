# Cancer Treatment Analysis
![Metastatic site changes](https://github.com/remco-mooij/matplotlib-challenge/blob/master/Pymaceuticals/Images/Metastatic_Site_Changes.png)

In this analysis a dataset from a recent animal study on the effectivenss of certain treatments to squamous cell carcinoma (SCC) was analyzed. In this study, 250 mice were treated with various treatmens, and physioloigcal responses were monitored in a 45-day period. Here, the effectiveness of four of these treatments - Capomulin, Infubinol, Ketapril, and Placebo - are compared.

Using Pandas and Matplotlib, 4 different scatter plots were created, each one comparing the 4 different treatments:
- Tumor volume changes over time
- Metastatic site changes over time
- Survival rate over time
- Total % tumor change after 45 days

OBSERVATIONS ABOUT RESULTS
-----------------------------

#### OBSERVATION 1:
Capomulin exhibits a reduction of nearly 20% in the mean tumor volume of treated mice after 45 days.
Mice treated with any of the other three drugs all exhibit an increase of over 45% in tumor volume over the same period.

#### OBSERVATION 2:
Mice treated with Capomulin exhibit fewer metastatic site changes over 45 days than mice treated with any of the other three drugs analyzed in this study. This indicates that the spreading of cancer is slowed down due to the effect of Capomulin.

#### OBSERVATION 3:
Mice treated with Capomulin demonstrate a survival rate of over 80%. All the other treatments result in a survival rate of 60% to less than 40%.
