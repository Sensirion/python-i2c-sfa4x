# Python I2C Driver for Sensirion SFA4X

This repository contains the Python driver to communicate with a Sensirion SFA40 sensor over I2C.

<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sfa4x/master/images/SFA4x.png"
    width="300px" alt="SFA4X picture">


Click [here](https://sensirion.com/products/catalog/) to learn more about the Sensirion SFA40 sensor.


Not all sensors of this driver family support all measurements.
In case a measurement is not supported by all sensors, the products that
support it are listed in the API description.



The default I²C address of [SFA40](https://sensirion.com/products/catalog/) is **0x5d**.



## Connect the sensor

You can connect your sensor over a [SEK-SensorBridge](https://developer.sensirion.com/product-support/sek-sensorbridge/).
For special setups you find the sensor pinout in the section below.

<details><summary>Sensor pinout</summary>
<p>
<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sfa4x/master/images/SFA4x-pinout.png"
     width="300px" alt="sensor wiring picture">

| *Pin* | *Cable Color* | *Name* | *Description*  | *Comments* |
|-------|---------------|:------:|----------------|------------|
| 1 | black | GND | Ground |
| 2 | red | VDD | Supply Voltage | 1.62V to 3.6V
| 3 | blue | SDA | I2C: Serial data input / output |
| 4 | yellow | SCL | I2C: Serial clock input |


</p>
</details>


## Documentation & Quickstart

See the [documentation page](https://sensirion.github.io/python-i2c-sfa4x) for an API description and a
[quickstart](https://sensirion.github.io/python-i2c-sfa4x/quickstart.html) example.


## Contributing

In case you want to contribute to this project, please read the [contribution guidelines]((https://sensirion.github.io/python-i2c-sfa4x/contributing.html)).

## License

See [LICENSE](LICENSE).