# frischluft
ESPHome file for the frischluft.works CO2 Sensor
---
This is a yaml file for using the [frischluft.works](https://frischluft.works/) with [ESPHome](https://esphome.io/).
I also added an ultrasonic sensor [SR04T](https://www.openelectronics.eu/Vandeniui-atsparus-ultragarsinis-atstumo-jutiklis-JSN-SR04T-AJ-SR04M) to the board to track the height of my standing desk to the PINs 25 and 32. This is optional and can be deleted from the config easily.
**Note**
The color mapping is for some reason not correctly translated into the Home Assistant Color view, but the color codes are the correct ones for Green, Yellow and Red.

To enable the correct output of the LCD screen the fonts listed in the yaml file must be added manually, I don't provide them here due copyright restrictions.
