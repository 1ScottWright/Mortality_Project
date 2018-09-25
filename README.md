# Mortality Improvement/Disimporvement Project
This repo contains the work for my capstone project at General Assembly.  Mortality rates in the United States change over time such that a femail aged 45, for example has a different probaility of death in one year in 2017 cmopared to a 45 year old female in 2000.  This rate of rate in mortality is commonly called mortality improvement.  As the name suggests, mortality has historically improved year over year due to improvements in medicine, public health, and other at-large risk measures taken such as safey measures incorporated in automobiles.   

However, recently, there are trends emerging that the mortality for middle aged men, as well as other demographic groups, is starting to go the opposite way -- ie, their mortality is starting to get worse over time.  

The measurement of mortality improvement, or disimprovement, relies on a measurement of the mortality experience for the US population.  These results of these studies are then compared to prior studies to measure the trends for the current year.  The production of a mortality study on the US population takes time to compile and so the results are not as timely as one would like.  

My work in this project is to try to tie the mortality improvement/disimprovement rate to other factors that are measured more timely so that an estimated/predicted mortaltiy improvement/disimprovement rate can be produced in a more timely manner.  

### Data Sources
The base mortality data was obtained from the Social Security Administration.  This information is loaded with initial EDA performed in the Data_load_and_clean notebook.

Currently, I have obtained drug abuse rates by sex and age category from the Department of Health and Human Services.  This information is contained in pdf tables.  I have not yet loaded this information into the notebook.  

I will also need, at some point, population data so that the raw mortality study infomration can be combined into age groupings.  I plan to either use the CDC Wonder database to get this information or obtain the inforamtion from the Census Bureau.

### Project Status
Currently, I am still obtaining data and thinking through the methodology.  
