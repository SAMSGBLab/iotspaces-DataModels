# Smart NGSI-LD Data Models for Devices

This repository contains a collection of NGSI-LD based data models for smart devices, their observations, and actuations. The goal is to create a standardized approach to modelling smart devices that simplifies the development of portable applications that leverage high-level observations rather than specific device properties.

## Overview

In smart spaces such as homes and buildings, IoT devices like sensors and actuators vary in type, function, and the data types they produce. By separating the physical devices from the observations or actuations they perform, our models enable developers to create applications that are more portable and maintainable.

This repository includes the following data models:

- A generic Device Model
- An Observation Model
- An Actuation Model
- A Smart Light Bulb Model
- A Smart Thermostat Model
- More to come!

You can also find instances of specific devices using our data models in a designated folder.

## Observations and Actuations Categories

We provide a list of observation and actuation categories for developers to use as a reference, although they are not limited to these categories. The categories include:

connectedDevices, airPollution, atmosphericPressure, averageVelocity, batteryLife, batterySupply, cdom, conductance, conductivity, depth, eatingActivity, electricityConsumption, energy, fillingLevel, freeChlorine, gasConsumption, gateOpening, heading, heat, humidity, light, location, milking, motion, movementActivity, noiseLevel, occupancy, orp, pH, power, precipitation, pressure, refractiveIndex, salinity, smoke, soilMoisture, solarRadiation, speed, tds, temperature, trafficFlow, tss, turbidity, waterConsumption, waterFlow, waterLevel, waterPollution, weatherConditions, weight, windDirection, windSpeed, airQualityIndex, carbonDioxide, carbonMonoxide, chemicalPollutants, distance, doorStatus, energyGeneration, fireAlarm, floodDetection, gasLeak, glassBreak, heartRate, indoorAirQuality, luminosity, methane, nitrogenDioxide, ozone, particulateMatter, peopleCount, proximity, radiation, soilNutrients, soundIntensity, ultraviolet, vibration, volatileOrganicCompounds, waterQuality, waterTemperature, windowStatus


## Contributing

We welcome contributions from the community. If you have suggestions for improvements or new data models, please create a pull request or open an issue to discuss your ideas.

## License

These data models are released under the [MIT License](LICENSE).

