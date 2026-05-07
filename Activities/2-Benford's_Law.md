# Benford's Law

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Rozklad_benforda.svg/1920px-Rozklad_benforda.svg.png" width="400px" />

## Overview

Benford's Law is one of the all-time great "I can't believe this is a thing" results. It states that, in many real-world quantitative data sets, **1 is by  far the most common leading digit**.

- Just over 30% of the numbers in the data set should start with a leading 1
- About 17% of data values should start with 2
- About 13% start with 3
- Leading 9's occur less than 5% of the time

This is surprising, because you might expect the distribution of leading digits to be uniform, with about 11% of entries starting with 1, another 11% with 2, and so forth.

The law is named after physicist Frank Benford, who called it *The Law of Anomalous Numbers* in a 1938 paper. Benford's Law has applications to fraud detection and accounting, because it can be used to identify fake data that has an unnatural distribution.

You're going to write a program to validate Benford's Law against a real-world data set: the county-level population estimates produced by the U.S. Census Bureau.



## Get the data

County-level population estimates are availble on the Census Bureau's web site:

https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-total.html

Scroll down to find the file `co-est2024-alldata.csv` near the bottom of the page and download it. If you open the file, you'll see that it's another example of the CSV format:

```
SUMLEV,REGION,DIVISION,STATE,COUNTY,STNAME,CTYNAME,ESTIMATESBASE2020,POPESTIMATE2020,POPESTIMATE2021, POPESTIMATE2022
040,3,6,01,000,Alabama,Alabama,5024356,5031362,5049846,5074296
050,3,6,01,001,Alabama,Autauga County,58802,58902,59210,59759
050,3,6,01,003,Alabama,Baldwin County,231761,233219,239361,246435
050,3,6,01,005,Alabama,Barbour County,25224,24960,24539,24706
050,3,6,01,007,Alabama,Bibb County,22300,22183,22370,22005
```

The first line lists the names of each field. The data is organized alphabetically by state, then by county within each state. The first line of data is the population for the entire state of Alabama, followed by the estimate for Autauga county, and so forth. The first entries on each line are some numerical encodings used by the census bureau to identify each county.


## Analyze

Go to your Claude chat. Paste the census data file into the chat window.

Then prompt:

> I'd like to analyze the county level population data in this CSV file and check if it agrees with Benford's Law. The column I want to analyze is POPESTIMATE2024. Write a Python script that does that analysis using Pandas and produce a bar chart showing the fraction of occurrence of each leading digit. Ask me if you have questions.

Claude should crank for a moment, then produce a script and plot showing the occurrence of each leading digit.
