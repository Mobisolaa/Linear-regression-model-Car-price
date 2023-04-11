## Linear-regression-model-Car-price
A model aimed at establishing the features with the highest predictive power in determining the price of a second-hand Nissan Qashqai.  Specifically focusing on Wolverhampton UK market.
## Introduction
The study started by examining the car based on its characteristics and popularity to obtain a general understanding. Sample data of 85 cars with a maximum age of 5 years was taken from WV4 6BD +10 miles environment to help draw the conclusions. The age of the cars were restricted to 5 years because that is a close range - including wider years creates a possibility that the sample would contain extremely higher prices or extremely lower prices, and as such can distort the overall conclusions. 
The characteristics of the cars hitherto obtained were the Year of making, Price, Engine size, Mileage, Gearbox, Horsepower (denoted in PS), Number of previous owners, Fuel type, and ULEZ compliance (Ultra Low Emission Zone), but as we cleaned data, characteristics like Number of previous owners, ULEZ compliance were eliminated because the infos were missing for some of the cars. 
## Data Scraping
Data was scraped from the Auto traders’ website on the 30th of Nov 2022 focusing on Nissan Qashqai cars available for sale within a 10-mile radius of the wv46bd postcode. A population of 310 Nissan Qashqai cars between the ages of 1 and 5 were selected for the study before being cleaned for outliers, resulting in 85 datapoints.
## Tools utilized
- Excel was used for data cleaning and manipulation 
- SPSS was used for analysis and model building . 
## Data Visualization
Graphical representations were used to tell stories of the data in a very simple format with efficiency and precision.
![overview](https://user-images.githubusercontent.com/122166125/231163711-1f52d1b8-b4b6-405d-a205-4e881937290f.png)

![price distribution](https://user-images.githubusercontent.com/122166125/231164567-faa211b9-82f6-4bbd-bedc-ac745b5b4c75.png)
## Hypothesis Testing 
The statistics of the data show that the average price is £16,909, and it was derived that there is a 95% chance that the average market price of the second Nissan Qashqai in the UK is between £16,693 and £17,125. To ascertain this, price was obtained from the public domain and a one sample T test was conducted, the results showed no significant difference between the average UK price and the mean price calculated in our sample.
## Correlation Analysis
This is to show how strongly these characteristics are related to the price of the car or the degree of association between them. The gearbox had the highest correlation at 0.534, and the least correlated was its horsepower of 140 at 0.079. 
