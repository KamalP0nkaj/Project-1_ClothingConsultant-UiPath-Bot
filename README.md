<b> Introduction </b> 

This simple robot will show you the forecast and suggest clothing that’s appropriate for the day’s temperature & weather.

A user enters a city name, the robot then scrapes data from google for the temperature and weather in that city, the robot then process data and makes a decision which will then suggest a clothing type to wear by use.
For example: If rainy weather outside then robot suggest you to bring an umbrella so you don’t want wet!

See if you augment clothing consultant to help you pack for a trip.


<b> Technologies </b>

<b> UiPath Studio|RPA Development </b>

<b> Activity Details </b>

1.	<b> Input dialog box: </b> This activity is used for get input city name by user.
2.	<b> Open browser: </b> This activity is used for open any browser then in side of open browser type the www.google.com URL in URL section.
3.	<b> Type into: </b> This activity is used for type weather in Raipur (city name) in Fahrenheit in google search engine.
4.	<b> Get text: </b> This activity is used for scraping temperature & weather data in the enter city name.
5.	<b> Flow chart: </b> This activity is used for analyse temperature & weather for user outfit suggestion.
6.	<b> Flow decision: </b> This activity is used for check condition of temperature & weather in the city name given by user.
7.	<b> Assign: </b> This activity is used for store as checked condition by flow decision.
8.	<b> Massage box: </b> This activity is used for show outfit suggestion to user.
