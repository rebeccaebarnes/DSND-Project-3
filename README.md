# Identify Customer Segments with Arvato
This project was completed as part of the course requirements of Udacity's [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) certification. If you find it helpful and want to reference it later, please consider forking the repo rather than cloning. 

## Overview
The project used a proprietary data set of German population data and customer data from a mail-order company to be able to identify under- and overrepresentation of customer segments between the two populations. 

An online summary of the material can be found at [my blog](https://rebeccaebarnes.github.io/). 

The project involved data wrangling and feature engineering to develop a functional analysis data set, using Principle Component Analysis to segment the data and KMeans to compare segments between the two datasets.

## Technologies Used
- Python 
- Libraries: sklearn, pandas, numpy, matplotlib, seaborn, 
- Jupyter Notebook

## Key Findings
- A number of segments were able to be clearly identified and defined including city-living youth, "traditional German" elders, and savvy male investors
- Analysis of the missing data did suggest that they were a different population segment and this was included in the segment comparisons
- There were a number of segments for the mail-order company that were over- and underrepresented compared to the general population
- Over- and underrepresentation appeared to follow expectations based on some stereotypes associated with the segments, for example, city-living youth were underrepresented and "traditional German" elders were overrepresented
