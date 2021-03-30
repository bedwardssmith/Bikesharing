<h1>Bikesharing</h1>
<h2>Overview</h2>
<p>Investors are currently looking at a request to invest in a bike sharing program in Des Moines.  Data from New York City's CitiBike bike sharing business has been used to create visualizations to assist investors with their investment decision.  A story was created using these visualizations that walks the investors through the findings.</p>
<br>
<h2>Analysis</h2>
<p>The analysis consists of a number of visualizations each of which is explained below.</p>
<br>
<h3>Top Bike Stations</h3>
<p>The first analysis consists of a map of starting points with each starting point being represented by a circle on the map.  The color of these circles darkens based on popularity; darker the color the popular the starting point.  From this map we can see that the most popular starting points are reflective of their appeal to tourists.  As the points move outside of tourist areas the numbers drop.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/Top_Bike_Stations.png" alt="Top Bike Stations">
<br>
<h3>August Peak Hours</h3>
<p>The second analysis shows the checkout times. Fom this we see that the most popular times are the hours of 5 and 6 pm.  This provides somewhat of a contradiction to the note in the first visualization that would indicate that tourism is a driving factor.  If the number of riders were driven only by tourism you would expect that there would be no particular spike in usage at the 5 and 6 pm hours. Of note also is the 8 am time frame which is the 3rd most popular time of checkout.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/August_Peak_Hours.png" alt="August Peak Hours">
<br>
<h3>Trip Duration</h3>
<p>The third analysis shows trip durations.  It is interesting that the largest number of riders checked out a bike for only 5 minutes.  If in fact the riders are due to tourism this may make sense in that tourists may simply check out a bike near one tourist destination only to check the bike in once they arrive at the next tourist destination. Additional analysis is required to determine why the highest trip duration is only 5 minutes.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/Checkout_Time_for_Users.png" alt="Checkout Time for Users">
<br>
<h3>Checkout Time for Users by Gender</h3>
<p>The fourth analysis shows trip durations by gender.  This visualization shows us that males generaly ride for longer durations, however, it levels off as the duration inceases.  As noted previously additional analysis is required to determine why the highest duration is only 5 minutes.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/Checkout_Time_By_Gender.png" alt="Checkout Time for Users by Gender">
<br>
<h3>Checkout Time by Weekday</h3>
<p>The fifth analysis shows checkout times by weekday.  This shows us that although usage on weekends is more consistent throughout the day it is weekday mornings and late afternoon that are the most popular times.  The only exception to this being Wednesday and Friday late afternoons in which demand weakens.  Once again this contradicts the theory that the success of CitiBike's bike sharing is driven by tourism given the times of popularity.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/Trips_By_Weekday_per_Hour.png" alt="Trips by Weekday">
<br>
<h3>Checkout Time by Weekday by Gender</h3>
<p>The sixth analysis shows checkout times by weekday by gender.  The times are consistent with our previous analysis, however, it also shows that the majority of riders are male.  As with the previous analysis this would contradict that tourism is driving the market as you would expect that the ridership would be more equally dispersed between males and females if it was predominately tourism related.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/Checkout_Time_By_Gender.png" alt="Checkout time by Gender">
<br>
<h3>Trips by Weekday by Gender and by Type; Subscriber or Customer</h3>
<p>The finaly analysis shows trips by weekday by gender and by type; subscriber and customer.  This shows us once again that riders are predominately male.  It also shows us that the majority of riders are subscribers. Once again the most popular days are weekdays rather than weekends with the exception of Wednesday which is similiar to weekends.  When looking at customers the riders appear to be evenly split between male and females which would be consistent with tourists.</p>
<br>
<img src="https://github.com/bedwardssmith/Bikesharing/blob/main/Images/User_Trips_by_Gender_by_Weekday.png" alt="Trips by Weekday by Gendera and by Type">
<br>
<h2>Summary</h2>
<p>Although one would expect that the success of CitiBike would be driven by tourism it is clear from the analysis that this is not the case.  From checkout times to riders being subscribers rather than customers, to gender it is clear that although tourism is one facet of their success there are other riders behind its popularity.</p>
<p>Based on the analysis completed I would recommend the following additional analysis with the given dataset:</p>
<ul>
<li>The number of bikes returned to the same station as the station checked out from versus being returned to another station.  This visualization, pie chart, would use the start station id and end station id.  Note that an if then statement would be required to determine if the start and end station id were the same.  The purpose of this visualization is to help to understand whether bikes are being used to get from point A to point B rather than for recreational purposes.</li>
<li>The trips by gender by weekday for which bikes were returned to the same station as the station checked out from.  Note that an if then statement would be required to determine if the start and end station id were the same.  This visualization, density, would use the start station id, end station, weekday, and gender.  Similiar to above the visualization is intended to understand whether bikes are being used to get from point A to point B.  However, layering on the weekdays and gender will provide further insight as to the type of usage.  Based on peak times it looks as though bikes may be used for commuting purposes given the early morning and late afternoon timing.</li>
 </ul>
<br>
<a href="https://public.tableau.com/profile/beverly.edwards.smith#!/vizhome/NYCCitibikeanalysis_16168739872070/Story1?publish=yes">Link to Tableau Story</a>
