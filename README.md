
official repo: https://github.com/donny681/ESP32_CAMERA_QR

I want to use the [ESP-IDF](https://dl.espressif.com/dl/esp-idf-tools-setup-2.3.exe) to compile the project(ESP32_CAMERA_QR),
but must use the cmake.
So I add the CMakelists.txt.

Please change the config to connected your route.

in the file sdkconfig:
```
CONFIG_WIFI_SSID="KFC"  # use your SSID
CONFIG_WIFI_PASSWORD="89562278" # use your password
```



