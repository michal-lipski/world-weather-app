[![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/michal-lipski/world-weather-app)
[![Build Status](https://secure.travis-ci.org/michal-lipski/world-weather-app.png)](http://travis-ci.org/michal-lipski/world-weather-app)
World Weather Application
=============

Sample application on top of Creatary platform.
Receives weather forecast inquiry via SMS and responds with SMS containing weather conditions fetched from google API.
Uses Creatary location API to locate subscriber

More information on www.creatary.com

Installation
-----------

To use application you need to deploy it in web and connect to Creatary platform

## Deployment on heroku

  * install heroku client
  ```$ wget -qO- https://toolbelt.heroku.com/install.sh | sh```
  * login using your heroku account
  ```$ heroku login```
  * create application
  ```$ heroku create --stack cedar```
  * push your changes to heroku
  ```$ git push heroku master```

## Connecting to Creatary

  For more information about connecting your application to Creatary platform on www.creatary.com/documentation

Usage for Subscriber
-----------

  weather          -   returns weather forecast for you current location
  weather London   -   returns weather forecast for given location

Testing
-------

To run the tests:

    $ rake spec




