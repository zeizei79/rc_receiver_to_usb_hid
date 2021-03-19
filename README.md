# SBUS/CRSF-receiver to USB HID for wireless simulator connection
6 Analog channels for Throttle/Yaw/Pitch/Roll sticks and 2 Dials/Sliders
8 Buttons
# preparing
### precompiled binaries
Precompiled binaries can be downloaded from [releases](https://github.com/zeizei79/rc_receiver_to_usb_hid/releases) page.

### compiling
Platformio is used. Check https://docs.platformio.org/en/latest/core/quickstart.html for more info.

# install
Flash using ST-Link or using FTDI (this tool can be used https://www.st.com/en/development-tools/flasher-stm32.html).

# receiver connection
wiring:
| receiver | Bluepill |
| -------- | -------- |
| TX       | PA3 (USART2 RX |
| 5V       | 5V       |
| GND      | GND      |
