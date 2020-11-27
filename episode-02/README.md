# Episode #2 - Apache NiFi

## What is it? 

Demo flow for collecting and integrating API data through Apache NiFi

## Requirements

This demo is based on Docker containers and uses Docker Compose to run the services.

This demo also requires a valid API key for [OpenWeather API](https://openweathermap.org/api). If you don't have a valid API key, please [sign up](https://home.openweathermap.org/users/sign_up) and create your API key.

## How to run

If you have Docker and Docker Compose installed:

```
$ docker-compose up
```

A couple minutes later, you may open NiFi's main URL in your favorite browser at http://localhost:8080/nifi

There's a NiFi template in this repo called `OpenWeatherData.xml` that you can import into NiFi as a start

Please refer to the [episode](https://www.youtube.com/watch?v=rPCGeouN58U) on YouTube for futher instructions (Portuguese)