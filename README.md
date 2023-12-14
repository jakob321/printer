# Printer
Notes on printer

## Hardware
* BTT SKR mini e3 v3
* Raspberry Pi 3b+

## Setup

1. Go to “pi imager” install os → other specific purpose os → 3d-printing→ mainsail 32-bit

### Raspberry pi
Usename: jakob

Password: m*********

Ip: 192.168.1.123

Tip: use putty, otherwise terminal GUI might not work

KLIPPER_ARGS="/home/jakob/klipper/klippy/klippy.py /home/jakob/printer_data/config/printer.cfg -l /home/jakob/printer_data/logs/klippy.log -I /home/jakob/printer_data/comms/klippy.serial -a /home/jakob/printer_data/comms/klippy.sock"

### Calibrate BL_TOUCH
run "PROBE_CALIBRATE" in klipper console

## Good videos

[bl_touch](https://www.youtube.com/watch?v=5vmjBXvY6BA&ab_channel=PrintsLeo3D)

[UART](https://www.youtube.com/watch?v=AtW3GqkKUz8 )

[UART](https://www.youtube.com/watch?v=ZOL-motmkos )

[UART](https://github.com/Klipper3d/klipper/issues/2913 )