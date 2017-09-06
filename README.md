It's a weather information fulfillment service that uses [Yahoo! Weather API](https://developer.yahoo.com/weather/).
The services takes the `geo-city` parameter from the action, performs geolocation for the city and requests weather information from Yahoo! Weather public API.
The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.
