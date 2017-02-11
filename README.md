# web-smart-mirror
HTML &amp; JS based passive display

[View it live](https://fleker.github.io/web-smart-mirror/?darksky=6bb985b59e0265149fc0e4d7159ff9b2&lat=39.7029&lon=-75.1118&newsapi=7755875d17a946ed9977bbc0420f0915&stocks=UA,NLS,HMC,WEN)

Settings can be configurable through GET parameters in the URL. These parameters may be required for a certain widget to appear.

* Weather
    * Weather is powered by [DarkSky](https://darksky.net/). You can obtain a Dark Sky key and use `darksky={API KEY}`.
    * Latitude and longitude can be set as well with `lat={LATITUDE}&lon={LONGITUDE}`
* News
    * News uses BBC only at the moment and the service [News API](https://newsapi.org/). You can obtain an API key for free and use `newsapi={API KEY}`
* Stocks
    * Stocks are powered by [Markit On Demand](http://dev.markitondemand.com/MODApis/) and do not require an API key. Stocks shown can be configured with `stocks={STOCK A, STOCK B}` in a comma-separated list
    
## Contributing
Want to add another widget or another setting? Contributions are welcome!