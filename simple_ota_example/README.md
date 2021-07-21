# Simple OTA example

This example is based on `esp_https_ota` component's APIs.

## Configuration

Refer README.md in the parent directory for setup details.

Example also supports binding to specific interface (either "Ethernet" or "WiFi Station"), which will allow firmware upgrade to happen through specific interface (in case multiple networking interfaces are enabled). Please see more on this through example configuration in `idf.py menuconfig -> Example Configuration -> Support firmware upgrade bind specificied interface->Choose OTA data bind interface`.

//iarv comments
1) run the following command in the folder of binary file 
python -m http.server 8070
2) build and flash this app
The host IP should be 192.168.1.11 . See on sdkconfig.defaults
