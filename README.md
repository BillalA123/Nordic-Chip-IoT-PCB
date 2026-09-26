# Nordic Chip IoT PCB

Low power wireless IoT sensing PCB integrating a Nordic nRF52805 Bluetooth MCU, GNSS receiver, expandable capacitor energy storage, and micropower power management.

## PCB

![Nordic Chip IoT PCB](Images/Nordic%20Horizontal.jpeg)

## Features

- Nordic nRF52805 Bluetooth LE MCU
- u-blox MAX-M10S GNSS receiver
- 800 µF onboard capacitor energy bank
- 12 expandable through-hole capacitor positions for additional energy storage
- Automatic MCU and GNSS startup at approximately 3.3V through a micropower startup circuit
- Desolderable 0 Ω Resistors for configurable GNSS connections
- Low power thermistor temperature sensing
- MCU voltage monitoring
- Micropower load switching and power management
- External SMA connector for the GNSS antenna

## Design Goal

The PCB is designed for energy constrained wireless IoT applications where energy is accumulated in the capacitor bank before the MCU and GNSS subsystem are activated. The expandable capacitor architecture allows additional energy storage to be added when the GPS operating requirements exceed the onboard capacitance.

## Hardware

| Subsystem | Implementation |
|---|---|
| Wireless MCU | Nordic nRF52805 |
| GNSS | u-blox MAX-M10S |
| Energy storage | 800 µF onboard capacitance |
| Expansion | 12 through-hole capacitor positions |
| Startup control | 3.2 V micropower automatic startup |
| Temperature sensing | Thermistor |
| Voltage monitoring | MCU ADC |
| GNSS antenna | SMA connector |
| Debug/programming | SWD |

## Repository Contents

- `PCB Files/` contains the PCB design files.
- `Images/` contains project images.
