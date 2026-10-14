# dyness-bms-esphome-canbus
Connecting the Dyness battery to monitoring via Home Assistant.

To obtain data from the battery, we will need an ESP32 doit-devkit-v1 and an MCP2515 CAN module.

I connected a Dyness DL5.0C Heating battery (5.12 kWh / 51.2 V).

We take 5V power from the COM port (pins 1, 2) and the CAN bus from the IN port (pins 4, 5).

We create a new device in ESPHome Builder, then merge the generated code with mine.
