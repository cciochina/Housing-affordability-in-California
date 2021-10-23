# Housing-affordability-in-California

## Overview

This project was about visualing data. The intention behind this selection of data was to look at housing prices across the United States to see if COVID-19 had any short term affect on average prices. 

The data was downloaded from https://www.zillow.com/research/data/ 


This repository includes:

- 3 csvs
    - housing price data from zillow
    - zipcode to lat and long 
    - A final merged, cleaned and filtered csv
- jupyter notebook file that was used to merge csvs, filter data, create sqlite database
- index.html 
- app.js
- app.py



## Visualization 

![image](https://user-images.githubusercontent.com/81276857/138538783-4bd4a9f7-8c0c-4a76-9b28-81bd6a3a7758.png)





## Features on the site

### Dropdown Menu and Summary

Dropdown menu that allows you to select state and year. This affects the summary panel and the bar chart. The summary panel lists the selected state's  max, min, and average house price.


<img width="240" alt="summary panel" src="https://user-images.githubusercontent.com/81276857/138537772-57d87ae6-37aa-4c0e-abeb-396e55493822.png">  <img width="240" alt="Drop down menu" src="https://user-images.githubusercontent.com/81276857/138539353-8670849f-9433-498d-bcb1-cd2297e73872.png">



### Barchart 

Displays and compares a select number of cities from the state that has been selected average housing prices.


<img width="400" alt="bar chart" src="https://user-images.githubusercontent.com/81276857/138537780-b7658ff5-490d-49bb-83d6-19c4e95b9d27.png">


### Heatmap 

Heatmap was built using Leaflet and shows the distribution of house price across the United States. The map showed that the areas with the highest averages were located on the coasts of California and coast of New England. 

![image](https://user-images.githubusercontent.com/81276857/138537919-fd12d613-4837-4b05-998b-8adb7d37e6c1.png)



