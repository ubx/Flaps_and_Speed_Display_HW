# Flaps & Speed

A KiCad project for a hardware module designed to interface with flap and speed sensors, likely for aviation or automotive applications.

## Features
- **CAN Bus Communication:** Includes CAN-In and CAN-Out interfaces using the SN65HVD230 transceiver.
- **Connectors:** Utilizes M12 5-pin connectors for reliable external connections.
- **Power:** Designed for 12V input with onboard 3.3V regulation, [Micro BEC SE-0509](https://de.aliexpress.com/item/1005010499841098.html?spm=a2g0o.order_list.order_list_main.4.743e1802VIZ0pe&gatewayAdapt=glo2deu)
- **Display:** Connected (H7-H14) to a [ESP32-S3-Touch-AMOLED-1.75](https://de.aliexpress.com/item/1005008989323572.html?spm=a2g0o.order_list.order_list_main.206.743e1802VIZ0pe&gatewayAdapt=glo2deu)

## Software

This hardware module is designed to run the following software:
[Flaps and Speed Display](https://github.com/ubx/Flaps_and_Speed_Display)

## Todo
- [ ] Review PCB toward a more professional layout
- [ ] Crate a PCBWay ready BOM
- [ ] Add more professional displays connector