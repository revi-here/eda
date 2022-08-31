# Vehicle Sales Analysis  
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.    

![Vehicle Sales Analysis.](images/car_sales_eda.jpg 'Vehicle Sales analysis.')  

# Hypothesis.  
The more the age of the vehicle , price is reduced.

Mileage and condition of the vehicle should also be analyzed.. Parameters to be analyzed:  
1.price  
2.vehicles age  
3.mileage  
4.condition  

# Data Exploration.  
#### Age of the vehicles sold.  
![Vehicle age analysis.](images/eda_vehicles_age_frequency.png 'Vehicle age analysis.')  
The above histogram shows that most of the vehicles age between 0-10yrs (35,000),fewer
ones in the range 10-20yrs(15,000) and very few more than 20yrs of age(very close to 0)..
This helps to conclude that vehicles of age 0-10yrs are the ones we need to consider..   

#### Number of days listed of the vehicles sold.   
![Vehicle types and days listed.](images/eda_vehicle_ads_listed.png 'Vehicle types and days listed.')  
The above graph shows that most of the ads were around 0-50 days..

#### Vehicle types and ads.  
![Vehicle types and ad.](images/eda_vehicle_type_ad.png 'Vehicle types and ad.')  
SUV and sedan are the vehicle types with greatest number of ads.  

### SUV Analysis  

#### SUV Age vs Price
![SUV Age Analysis.](images/eda_suv_age_price.png 'SUV Age analysis.')  
we see that as the 'vehicle_age' increases , 'price' reduces..  

#### SUV Condition vs Price  
![SUV condition Analysis.](images/eda_suv_condition_price.png 'SUV condition analysis.')  
From the above plot , we see that with the better condition ,price increases.  

#### SUV Mileage vs Price
![SUV mileage Analysis.](images/eda_suv_mileage_price.png 'SUV mileage analysis.')  
As mileage increases ,price reduces though not very significantly..  

#### SUV Transmission
![SUV Transmission type.](images/eda_suv_transmission_box.png 'SUV Transmission type.')    

#### SUV Paint color   
![SUV Paint colors.](images/eda_suv_color_box.png 'SUV Paint Colors.')  

Conclusion:  
We see that price is negatively correated with age.The older the vehicle ,lesser the price.
We dont see much correlation with mileage.
With the condition of car being around 2-4,the price is more.
Suvs show slight increase in manual transmission with 'black' and 'white' paint colors having incresed price.  

### Sedan Analysis.  

#### Sedan Age vs Price  
![Sedan Age vs Price.](images/eda_vehicle_age_price.png 'Sedan Age vs Price.') 

#### Sedan Mileage vs Price  
![Sedan Mileage vs Price.](images/eda_vehicle_mileage_price.png 'Sedan Mileage vs Price.') 

#### Sedan Condition vs Price  
![Sedan Analysis.](images/eda_vehicle_price_condition.png 'Sedan analysis.')  

#### Sedan Transmission   
![Sedan Transmission.](images/eda_vehicles_transmission_boxplot.png 'Sedan Transmission.')  

#### Sedan Paint Color.  
![Vehicle Paint Color.](images/eda_vehicles_paint_color_boxplot.png 'Vehicle Paint color.') 

Conclusion:  
We see that 'price' reduces with increse in 'vehicle_age'.  
Observing the data in sedan , we see similarity with that of SUV.
The 'automatic' transmission increases the price of vehicle in this case.
vehicle age reduces the price.
Mileage does not show a significant correlation with price.

# Final Conclusion.  
Analyzing the number of ads and the average price for each type of vehicle we plot a graph showing the dependence of the number of ads on the vehicle type. We found that the 'SUV' and 'truck' are the two types with the greatest number of ads.

Plotting the important parameters like 'price','vehicle_age','mileage_per_year' shows negative correlation between 'vehicle_age' and 'price' proving our hypothesis. Also we see that 'mileage_per_year' and 'condition' also affects the 'price'.


