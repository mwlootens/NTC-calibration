# NTC calibration

## Introduction

Makes use of the [**Steinhart-Hart**](https://www.wikiwand.com/en/Steinhart%E2%80%93Hart_equation) equation to calibrate thermistors. This is achieved by:

* Retrieving an analog to digital converted signal via an microcontroller, This value stands in relation with the resistance of the micro controller.
* Fetching the resistance of the [Thorlabs TSP01]() temperature logger.

These values are feeded into the [Steinhart-Hart class](Visualization/SteinhartHart.py) and will be used to calibrate the coefficients.

## Other method to retrieve the voltage from the ADC signal

If your circuit doesn't make use of a (simple) voltage devider, you will need another conversion method. This can be achieved by:

* Creating a new method in the conversion class



## Visualization


## Contributing
