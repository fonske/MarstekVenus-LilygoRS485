Config for managing and monitoring a Marstek Venus Battery over Modbus in Home Assistant using an Lilygo RS485 or other ESP controller with ESPHome.
(https://gathering.tweakers.net/forum/list_messages/2282240)


- 6-6-2025 Github added LilyGo T-POE-Pro @MUN0X
- 20-7-2025 Max, Min en Delta Battery voltage sensors
- 22-7-2025 Wifi Signal Strength
- 22-7-2025 float (0) in marstek_venus_battery_control.yaml
- 24-7-2025 
  - WebUI with icons
  - WIFI /BT /CLOUD status
  - WIFI strength %
  - Battery WIFI strength %
  - Software/Firmware/BMS version
  - Power restriction status
- 9-8-2025 Lilygo Github BMS V2.15 Cell temp scale

- 3-8-2025 Lilygo Github neopixelbus > esp32_rmt_led_strip

- 21-9-2025 Type changed from arduino to esp-idf.  
- 24-9-2025 Added Debug information and switch to CPU Frequency: 240 MHz (was 160MHz)
- 30-9-2025 added Captive portal
- 18-10-2025 Correct Max/Min Cell Temperature by multiplying value by 0.1 for BMS versions < V2.13
