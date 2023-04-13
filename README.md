## Linear-regression-model-Car-price
A model aimed at predicting the price of a second-hand Nissan Qashqai using the features with the highest predictive power. Specifically focusing on the Wolverhampton UK market.
## Introduction
The study started by examining the characteristics and popularity to obtain a general understanding of the car. Sample data of 85 cars with a maximum age of 5 years was taken from WV4 6BD +10 miles environment to help draw the conclusions. The age of the cars were restricted to 5 years because that is a close range - including wider years creates a possibility that the sample would contain extremely higher prices or extremely lower prices, and as such can distort the overall conclusions. 
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
## Regression Analysis 
Finally, we built a model to predict the value of the car ( using the features with the highest predictive power), then tested the model for adequacy and goodness of fit. The analysis shows that Mileage, age, Gearbox and Horsepower (110PS, 140PS,160PS) were the most significant.

![model summary](https://user-images.githubusercontent.com/122166125/231270393-d298b6bb-6dcc-48c3-aa39-b7fec8608747.png)

This is a moderate model, it means that the independent variables can explain 59.1% of the variation in the price of the car, also there are other variables not factored here that might have improved the quality of the model e.g., number of previous owners, ULEZ compliance or just sheer sentimental value attached to the car because of the size and usefulness for large families. 
## Statistical Model

![sig](https://user-images.githubusercontent.com/122166125/231777807-441862b8-38bd-43f3-a0de-e11548b1e563.png)

The equation of the model to predict a car can thus be described through the Unstandardized Coefficient B as:


- 19,976 -0.061*(mileage of the car) -560.393*(Age of the car) +2527*(Automatic) -1754*(PS) +errors. 

i.e., If mileage increases, price falls, and as age of the car increases, price also falls, an automatic will increase the price of the car, while a manual will fall by the same value, a 110Ps reduces the price by 1754, but a 140 and 160PS will increase the price by 919.6 and 1155.3 respectively. 

In conclusion, to predict the price of an automatic 160PS 2020 model Nissan Qashqai with a mileage of 74,640. 
= 19,976 -0.061*(74,640) -560.3*(3) +2527*(1) +1155.3*(1) 
= £17,424.4 

For full read, which includes the correlation analysis, multicolinearity, and all the assumptions tested please

