# Students_Performance_Analysis_py_EDA

# Python_EDA

### Students Performance Analysis:

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the students performance in diiferent subjects. By analyzing various aspects of the students data provided, We seek to identify trends, Make data-driven recommendations, and gain a deeper understanding of the students performances so that the institute/educatores can make data driven decisions .


### Data Sources :

Students Data: The primary dataset used for this analysis is the "StudentPerfromance.csv" file, containing detailed information about each and every students.

### Tools :
- Ms Excel :
  - for loading data set and data cleanning

- JupiterNotebook :
  - Data Cleaning
  - Data Analysis
  - Creating charts and observations


### Data Cleaning/Preparation :

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis :

EDA involved exploring the sales data to answer key questions, such as:

- What is the Gender distribution in the class?
- Performance analysis based on Gender?
- students performance based on parents education?

### Data Analysis :

Include some interesting code/features worked with

```Python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
df1=df.groupby(["parental level of education"]).agg({"math score":"mean","reading score":"mean","writing score":"mean"})
```

### Results/Findings :

#### The analysis results are summarized as follows:

  - Female students are more in number in comparison to Male students.

  - Through the above data displayed in the heatmap we can observe that student marks are dependent on parents education,
  i.e Higher level of parents education shows higher performance in childs score.

  - Female students are scoring good avg score as compared to Male students.

  - In maths subject students are strugging to get good score as compared to other subjects.

  - Majority of the Students belongs to ethnic group:"C","D" and "B".

  - Students with test preparation course got good score as compared to none.


### Recommendations :

#### Based on the analysis we reccomend the following actions:

- Parents educations should be checked for students better performances.

- Teachers should focus more on Male students to improve theire performance score.

- Extra hours/time should be give for Maths subject since most of the students are struggling to score good score.

- Test preperation course should be made mandatory if possible for every student.
    

### References

 1.Kaggle
 
2.[Stack Overflow](https://stack.com)




