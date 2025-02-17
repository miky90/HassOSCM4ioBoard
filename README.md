![image](gitResources/cm4ioboard.jpg)
This Addon enables and activates automated active cooling.

# Installation

Within HA

1. Click Supervisor.
1. Click Add-on Store.
1. Click the … button (in top left).
1. Add this Repository URL.

Click CM4 IO Board Active Cooling and install.

![image](gitResources/addonSelect.jpg)

# Configuration

## Celsius or Fahrenheit

Choose Celsius or Fahrenheit.

- **CorF** - Configures Celsius or Fahrenheit.

## Temperature Ranges

![image](gitResources/FanRangeExplaination.png)

Set your fan ranges appropriately.

- **LowRange** Minimum Temperature to turn on 33%. Lower will turn the fan off.
- **MediumRange** to be the temperature divider between 33 and 66%.
- **HighRange** to be the maximum temperature before 100% fan.

# Enable I2C

In order to enable i2C, you must follow one of the methods below.

## The easy way

[Use the addon](https://community.home-assistant.io/t/add-on-hassos-i2c-configurator/264167)

## The official way

[Use the guide](https://www.home-assistant.io/hassio/enable_i2c/)
