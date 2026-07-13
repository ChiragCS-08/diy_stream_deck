# Programmable-Input-Device
Open-source, low-cost Stream Deck alternative built on the RP2040 (MicroPython). Features a TCA9548A I²C multiplexer driving 6 OLED displays for dynamic key icons, USB HID macro execution, and a fully custom KiCad PCB with zero-violation ERC. An affordable, hackable input handler for streamers, devs, and productivity workflows.

Programmable Input Handler — a DIY, fully customizable macro keypad and Stream Deck alternative, designed as a low-cost, open-source answer to expensive commercial input devices.
Built around an RP2040 microcontroller running MicroPython, the device uses a TCA9548A I²C multiplexer to drive 6 independent OLED displays, giving each key a dynamic, reprogrammable icon. It acts as a USB HID device, sending keyboard shortcuts and macros to trigger actions in tools like OBS Studio, VS Code, and Spotify.

Custom 2-layer PCB designed in KiCad (zero-violation ERC)
Dynamic per-key OLED labeling via I²C multiplexing
USB HID macro execution — no proprietary software required
Python-based automated test suite for hardware validation
Fully open-source hardware + firmware, built for hackability and extension
=======
# diy_stream_deck
