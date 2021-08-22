# Adafruit IO Arduino Library

- [API Documentation](https://adafruit.github.io/Adafruit_IO_Arduino/) 

Adafruit's library wants SSID and Password as a constant. This adds in WifiManager so that it connects to wifi without SSID/password hardcoded

Used this to add WifiManager: https://github.com/tzapu/WiFiManager/issues/243#issuecomment-364804188

# Use
Download library as a ZIP file and rename the Zip to AdafruitIO_Arduino
Sketch > Include Library > Add .ZIP library and upload the Zip
Install WifiManager library: https://github.com/tzapu/WiFiManager

Declare IO as
```
AdafruitIO_WiFi io(IO_USERNAME, IO_KEY, nullptr, nullptr);
```