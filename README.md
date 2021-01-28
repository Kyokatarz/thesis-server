# Home Automation System Using Raspberry PI

This is the back end where the Raspberry Pi will hit after receiving change of state of the sensors.

* When motion sensor hits _/api/motionSensor_, the server will log its activity to motion.log
* When flame sensor hits _/api/flameSensor_, the server will log its activity to flame.log
* When temperature sensor sends data to _/api/temperature_, the server will assign the new data
* When the server is hit on _/api/all/_, the server will return the logs, the temperature and humidity level.
