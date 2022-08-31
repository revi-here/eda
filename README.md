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
![Vehicle age analysis.](images/eda_vehicles_age_frequency.png 'Vehicle age analysis.')  
The above histogram shows that most of the vehicles age between 0-10yrs (35,000),fewer
ones in the range 10-20yrs(15,000) and very few more than 20yrs of age(very close to 0)..
This helps to conclude that vehicles of age 0-10yrs are the ones we need to consider..

![Vehicle types and days listed.](images/eda_vehicles_ad_listed.png 'Vehicle types and days listed.')  
The above graph shows that most of the ads were around 0-50 days..

![Vehicle types and ad.](images/eda_vehicle_type_ad.png 'Vehicle types and ad.')  
SUV and sedan are the vehicle types with greatest number of ads.  

![SUV mileage Analysis.](images/eda_vehicle_mileage_price.png 'SUV mileage analysis.')  
As mileage increases ,price reduces though not very significantly..  

![Sedan Analysis.](images/eda_vehicle_price_condition.png 'Sedan analysis.')  


![SUV Transmission type.](images/eda_vehicles_transmission_boxplot.png 'SUV Transmission type.')    

![SUV Transmission type.](images/eda_vehicles_transmission_boxplot.png 'SUV Transmission type.')  



![Vehicle Paint Color.](images/eda_vehicles_paint_color_boxplot.png 'Vehicle Paint color.')    

# Final Conclusion.  
Analyzing the number of ads and the average price for each type of vehicle we plot a graph showing the dependence of the number of ads on the vehicle type. We found that the 'SUV' and 'truck' are the two types with the greatest number of ads.

Plotting the important parameters like 'price','vehicle_age','mileage_per_year' shows negative correlation between 'vehicle_age' and 'price' proving our hypothesis. Also we see that 'mileage_per_year' and 'condition' also affects the 'price'.


