# USED CAR DATA
## by Muaz Hassan

## Dataset
The data consists of information regarding used cars which contain about 7,906 cars, including their selling price, engine size, model names, 
and other features. The dataset was sourced from Kaggle (https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?select=UserCarData.csv).


## Summary of Findings
In the exploration, I found that there was a strong correlation between some variables such as car engine and selling price, 
max_power and selling price, and max_power and engine. Most car engines and mileage fall between 1000 – 1500 and 15 – 20 respectively and are populated by manual type of transmission. 
The number of cars used by the city was determined and could be seen that New York City has the greatest number of cars used. 
Car mileages were also determined and most mileage falls within 20. Generally, from the analysis, it could be depicted that most car transmissions were manual, 
and most fuel types were diesel. The most used car was Maruti followed by Hyundai.
Further exploration shows most cars were still in stock when the categorical column (‘sold’) was compared to the region column which depicts that a numerous number 
of cars are readily available in the market and most car seller types are mostly individuals populating the region overall. 
The relationship between car mileage and selling price was also determined and could depict that most car mileage falls between 20m and selling price was within the 
range of 30k – 100k dollars. 
The relationship between car transmission and selling price was also explored and it could be illustrated that the automatic type of transmission 
has the most expensive selling price with a minimum selling price of about 6k dollars when compared to manual having a minimum of 4k dollars.



## Key Insights for Presentation
For the presentation aspect, I focused on checking cities with the highest number of used cars, followed by the most common fuel type used, 
the most common car used car name, then plot them in a bar chart.
Afterward, I investigated the relationship between car mileage and selling price, 
I also investigated the categorical variables one by one, looking at the relationship between transmission and selling price and mileage and region with the use of a box plot.
Furthermore, I looked at the variation in car transmission by region, car owners by region, and car sellers by region. 
In addition, I try to segregate years of selling cars price into 8 years interval by summing the selling price and comparing them with one another using a pie chart. 
Lastly, I investigated the relationship between car engine, mileage, and transmission as well as the correlation between mileage','engine','max_power’, and 'selling_price using heatmap.
I've made sure to use different color palettes for each quality variable to make sure they’re different between plots.

