# Overview of the analysis: 
The purpose of this analysis is to create a story in Tableau and show a variety of visualizations about the CitiBikes August 2019 dataset.                       
Click here to see my [Tableau Story](https://public.tableau.com/views/Module14_CitiBikeChallenge/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)

# Results: 
## Page 1: August 2019 Summary
![page1](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page1.jpg)                                         
In August 2019 there were just over 2.3 million bike rides with data collected. The ~65% of all riders are male and the vast majority of them are subscribers. The majority of non-subscribers (ie customers) are listed as gender unknow suggesting that non-subscribed riders may not be prompted to give details such as their gender. 

## Page 2: Bike Riders Trip Duration
![page2](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page2.jpg)                                           
The graph above shows the number of bikes that were checked out on rides vs the trip duration. The panel A shows trips that lasted from 0-60minutes (ie hour 0), panel b shows trips that lasted 60-120 minutes, and panel c shows trips that lasted 120-180 minutes. The trip duration for any ride drastically decreases after about 5 minutes suggesting that riders are mostly taking small rides that are 0-5 minutes long and few riders are taking trips up to 60 minutes long.

## Page 3: Bike Riders Trip Duration by Gender
![page3](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page3.jpg)                                           
This graph shows a similar trend as the previous one. As expected the male riders are renting the most amount of bikes. The male riders are also taking longer trips than the female and unknown riders. 

## Page 4: Number of Trips By Usertype, Gender, and Weekday
![page4](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page4.jpg)                                           
This visualization shows the number of trip (less = light green, more= dark green) that where taken by male, female, and unknown riders sorted by whether or not they are a subscriber and what day they utilitzed CitiBike. Females are mostly subscribers using the bikes frequently through out the week. Males are mostly subscribers using the bikes primarily Monday through Friday suggesting they may be bike commuters. The unknown riders are mostly non-susbscribers and are riding more frequently on the weekends suggesting they may be tourists.

## Page 5: Number of Trips By Weekday and Hour
![page5](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page5.jpg)                                           
This visualization shows the most popular starting hours and days of the week. 8am, 5pm, and 6pm Monday through Friday are generally the busiest times for CitiBike suggesting most riders are using the service for commuting to work.

## Page 6: Number of Trips By Weekday and Hour (sorted by gender)
![page6](https://github.com/nsmeltz/Module14_Challenge/blob/d0d99eaf46bb89f84cf8e5537b87e0e34cfa717b/Images/page6.jpg)      
Again, this plot shows that males are the predominant user of CitiBikes. The majority of males and female bike rides occur during morning and evening commute times (6-10am and 4-8pm respectively). Unknown users are riding mostly on Saturday and Sunday between 9am-7pm.  

# Summary: 
In summary CitiBikes is a sucessfull bike sharing business that is characterized by customers who are predominantly male riding to and from locations in New York city around typical morning and evening commute times. Rides typically last 0-5 minutes and rarely more than 60 minutes. This business could expand by looking into the unknown rider data and investigating why they are typically weekend riders. I also think it would be interesing to do analysis on how far people are going on these short 0-5minute long rides and how that effects the maintenance schedule of the bikes. 
