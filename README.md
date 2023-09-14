# Greeting HKWeather

A very simple python based microservices contain 3 component:

# UI
A web UI with 2 button

# Greeting
A service that will return random greeting phrase and current time

# Weather
A service that will reach out to HKO to get current werather info of Hong Kong

# To Build the image on M1 for x64
```
docker build --platform linux/amd64 -t imagename .
```
