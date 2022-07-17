# Building a Weather App

# problem statement

Accept a city name and find the weather data for that city

Show the map of that entered city on right hand side

Show the weather details of that city on Left hand side. Show min temp, max temp, wind, clounds, sunrise, sunset etc.

Use logos or icons while showing the data. ( you can show logo of sunrise, sunset etc ) Searchbar should be on top.
In the same weather app, show daily forecast of a city for next 7 days.

You can show this data on new html page or same one as well, your choice.

I have done this project individually and build the [Weather App](https://cozy-cat-93059e.netlify.app/) where user can search any city weather and on his/her location . I hope you will enjoy the reading….

## I had to implement the following user stories:

 1. User can view the weather in his/her current location.
 2. User can toggle the temperature unit (Celsius or Fahrenheit).
 3. Weather icon or background image will change depending on weather conditions.
 4. User can search for weather information of other places.

# Tech Stacks Used
HTML
CSS
JavaScript
<p>
  
   <img src="https://aedificogroup.com/wp-content/uploads/2021/08/Aedifico-web-development.gif"  width='500px' height='300px'/>
  
 
   
</p>
  

# Logic
After looking at an example API response from Open Weather, I figured I’ll need to get the longitude and latitude of the user to be able to serve weather information on page load.

The easiest way to do this was to use the HTML5 Geolocation API which was pretty straightforward it had already been covered it in the JSON and APIs section of the curriculum.
The Open Weather API gave me a way to update the location, temperature and weather description but I still needed to find a way to update the local time. After a bit of searching I found another API at Geonames.org which took care of this.
The last thing I did was to update the weather icon on the conditions in the user’s location or city of interest. I decided a good way to do this was to check the weather description and change the icon based on that.
So I considered a few possible scenarios such as wind, temp., sunrise, sunset e.t.c and wrote a bunch of conditional statements to check if the weather description contained one of keywords and then update the weather icon.
I have discovered, through various tests, that this method is not 100% foolproof but it worked well enough for me to stick with it.

# Key takeaway
My major takeaway from this project is that I learnt how to access each part of the returned JSON data from the API response and use it in different ways. Although my methodology needs some refining, it’s bound to get better with more practice.

# Sample Video

https://user-images.githubusercontent.com/101327895/170945687-a2947ab1-5e1e-467c-8783-9d06d8c36f05.mp4


