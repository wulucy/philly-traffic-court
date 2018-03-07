# Philadelphia Traffic Court Verdicts

In this project, we attempt to predict verdicts in Philadelphia's traffic courts from 2006-2014. Using features like the defendant's age and sex, the violation in question, and the identity of the judge, we predict the verdict of the case.

## Data

Data comes from [OpenDataPhilly](https://www.google.com/search?q=opendataphilly&oq=opendataphilly&aqs=chrome..69i57j69i61j69i60j69i61.1653j0j7&sourceid=chrome&ie=UTF-8), provided by a Pennsylvania Right-to-Know request filed with the Philadelphia Traffic Court.

## Background

In 2014, the offices of the Philadelphia Traffic Court were raided by the FBI. Ultimately, 9 judges were indicted on 77 counts of ticket-fixing-related behavior and the traffic court was dissolved.

While the data was originally obtained in order to investigate motivations behind ticket-fixing, we will not be investigating this topic in this analysis.

## Project Overview

This project can be broadly split into three parts:  
1. **Data cleaning** Only 25% of entries in the dataset are complete across all features; in addition, the data was entered inconsistently. In this part of the project, we deal with the missing data and construct dummy variables for the categorical features. The code for this part is in Analyzing Citations - Data Cleaning notebook.
2. **Feature construction** Several features in this dataset can yield additional information (for example, zip code can yield demographic information). In this part of the project, we construct new useful features from existing features. The code for this part is in the Analyzing Citations - Feature Construction notebook.
3. **Modeling** Finally, we implement and optimize a model to predict verdicts. The code for this part is in the Analyzing Citations - Modeling notebook.

## Further Information

Those interested in learning more about this dataset and exploring how it relates to the judicial corruption case may want to look at the work done by OpenDataPhilly [here](https://github.com/fulldecent/philadelphia-traffic-court-rtk).
