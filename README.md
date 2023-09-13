# esp32-rgbww
This is a custom ESP32-based LED controller that easily links with
ESPhome and Home Assistant.

The device has 5 low-side MOSFETs for controlling LEDs up to 24V. Terminal block
rated for 8A of current, barrel jack rated for 6A. Device must be flashed
using a Tag-Connect TC2030-USB-NL cable. Two config files are available.


## Support
No support provided.

## Configuration


### 2channel-monochrome.yaml
Provides 2 independent channels of monochrome LED support (trivially extendable
to 5).

### rgbww.yaml
Provides 5 channels of LED support, intended for 6 wire LED strips (RGB, CW,
WW).

Exposed to ESPhome/Home Assistant as a RGBWW light with color interlock
enabled.


