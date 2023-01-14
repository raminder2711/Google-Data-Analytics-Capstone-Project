# Google Data Analytics Capstone Project (MS Excel and Tableau)
![Image_Bike](https://user-images.githubusercontent.com/119749518/211970785-a7ca2157-7010-42d0-8543-e4dea4be6c59.png)
<h2>Case Study: How Does a Bike-Share Navigate Speedy Success?</h2>

<h2>Table of Contents</h2>

- Introduction<br>

- Business Task<br>
- Data<br>
- Tools<br>
- Data Cleaning <br>
- Analysis and Viz(Excel) <br>
- Analysis and Viz(Tableau) <br>
- Conclusion and Recommendations

<h2>Introduction</h2>
The project is a part of Google Data Analytics Certification course capstone.
Welcome to the Cyclistic bike-share analysis case study! This case study, will perform many real-world tasks to answer the key business questions.

<h2>Business Task</h2>  
<b></b>How do annual members and casual riders use Cyclistic bikes differently?

<h2>Data</h2>
<b>License</b>: The data has been made available by Motivate International Inc. under the below license.
  
[Check Here](https://www.divvybikes.com/data-license-agreement)

<b>Our Data Range</b>: October and November 2022 (2 months data)  
  
<h2>Tools</h2>
<h3>Data Cleaning Tools</h3>
- MS Excel<br>

<h3>Data Visualisation and Data Analysis Tools</h3>
- MS Excel<br>
- Tableau<br>

<h2>Data Cleaning (MS Excel)</h2>

 - It was observed that there were several entries where ride length was 0 (zero), because started at and ended at times were similar. So, that data was <b>deleted</b>.

![Data-Cleaning_ride length 0](https://user-images.githubusercontent.com/119749518/212465117-54ed8505-9dfe-4f53-b8de-802061b0281a.png)

- It was observed that there were some irregularities with time where started time was greater than the ended time of the ride. The same was <b>corrected</b>.

![date greater](https://user-images.githubusercontent.com/119749518/212465365-cb3b9ad5-f863-4ae7-bb97-4769ea172887.png)

<h2>Analysis and Viz (Excel)</h2>

<h3><I>Average Ride Length</I></h3>
The Average ride length of casual riders is more than the ride length of member riders. This greately signifies that our cycles are used more by the casual riders.


![Average ride_length](https://user-images.githubusercontent.com/119749518/211985058-d8885540-5664-4136-bb39-8261bff26359.png)


<h3><I>Busy Days (Based on Average Ride length)</I></h3>
We can clearly find out that the busiest day for the casual riders is Sunday with averge ride length of close to 22 minutes. Furthermore, busiest day for the member riders are Saturday and Sunday with average time of 12.28 minutes and 12.29 minutes respectively.

![Busiest Days](https://user-images.githubusercontent.com/119749518/211985160-b544ca5d-6f93-487a-8df6-7e394a571873.png)


<h3><I>Favourite Bike (Based on Average Ride length)</I></h3>
The Favourite bike (irrespective of the type of riders) is the docked bike. The popularity is immense with 66% of usage.<br> 


![Favourite Bike](https://user-images.githubusercontent.com/119749518/211985211-4878c09c-bc2d-48bd-9dfa-33887ae136e2.png)


<h2>Analysis and Viz (Tableau)</h2>

<h3><I>Day Wise Traffic (Based on Overall Data and sorted by highest to lowest casual riders)</I></h3>
It is observed that Wednesday and Saturday generates high traffic for member and casual riders with <b>95,069 and 63,277 riders</b> respectively.

![Day wise Traffic](https://user-images.githubusercontent.com/119749518/212466578-54d55d8f-9e3c-45a0-8590-b9c310021b84.png)


<h3><I>Favourite Ridebale type (Based on Overall Data)</I></h3>
Electric bike is the favourite bike with <b>57.76%</b> of share, then comes the classic bike and docked bike with <b>40.16% and 2.08%</b> of share respectievly.

![Favourite rideable type](https://user-images.githubusercontent.com/119749518/212466590-5e86e6b0-cb7b-4a4d-9e6a-01cf887d34eb.png)


<h2>Conclusion and Recommendations</h2>

- A common observation is that casual riders are using the bike rentals more than the member riders.
- Targetted on-ground marketing strategies to convert casual riders to members.
- Discounting campaigns for new members should be initiated to lure the casual riders to enrol for members.


  
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
