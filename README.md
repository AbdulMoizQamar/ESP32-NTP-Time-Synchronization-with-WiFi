# ESP32-NTP-Time-Synchronization-with-WiFi
This project demonstrates how to connect an ESP32 to a WiFi network and synchronize its internal clock using the Network Time Protocol (NTP). The ESP32 obtains accurate local time from an NTP server, displays the current time via Serial output, and then disconnects from WiFi to save power.

Description:
This project demonstrates how to connect an ESP32 to a WiFi network and synchronize its internal clock using the Network Time Protocol (NTP). The ESP32 obtains accurate local time from an NTP server, displays the current time via Serial output, and then disconnects from WiFi to save power.

Features:
Connects to a specified WiFi network.
Retrieves accurate time from a public NTP server (pool.ntp.org).
Applies GMT offset for local timezone adjustment.
Prints formatted current time (hour, minute, second) to Serial Monitor.
Disconnects WiFi after synchronization to reduce power consumption.

Hardware required:
ESP32 development board
USB cable for programming and serial communication
This project is ideal for applications needing accurate timekeeping without an external RTC module, using WiFi and NTP.
