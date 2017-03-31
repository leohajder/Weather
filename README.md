# Weather

A local weather checker made as an assignment for [FreeCodeCamp](https://www.freecodecamp.com/).

## Resources

* [Bootstrap](http://getbootstrap.com/)
* [Bootswatch](https://bootswatch.com/)
* [FontAwesome](http://fontawesome.io/)
* [FreeGeoIP](http://freegeoip.net/)
* [jQuery](https://jquery.com/)
* [OpenWeatherMap API](https://openweathermap.org/api)


## How does it work?

An AJAX request gets a JSON response from FreeGeoIP containing the location data, and then another one gets a JSON response from OpenWeatherMap containing the weather data, with the location parameters passed to it. Register for free to get the required OpenWeatherMap app ID.  
**NOTE:** Use http instead of https. 

Live example on [CodePen](http://codepen.io/leohajder/full/OpVZqb).
