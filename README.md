
Introduction:

Weather affects almost every decision we make in our daily lives — from choosing what to wear, planning travel, or even scheduling outdoor events. Our Weather App is a simple yet powerful solution that provides real-time weather updates for any city around the world.

By integrating the OpenWeatherMap API, the app delivers accurate information such as temperature, humidity, wind speed, and weather conditions with easy-to-understand visuals. With its user-friendly design and instant feedback, the app ensures that users can quickly check weather details anytime, anywhere.

This project demonstrates how modern web technologies and API integration can be combined to build an application that is not only technically sound but also practical and impactful in everyday life.



🔹 Algorithm for Weather App

1) Start

2) Input city name from user (via search box).

3) Check input

   If empty → Show error: “Please enter a city name”.

4) Send request to OpenWeatherMap API with the given city.

5) Receive response from API.

6) If response is invalid → Show error: “Invalid city name”.

   If valid response:

   Extract temperature, humidity, wind speed, and weather condition.

   Convert wind speed from m/s to km/h.

   Select appropriate weather icon based on condition (rain, clear, snow, etc.).

   Display results on the app screen.

7) End
