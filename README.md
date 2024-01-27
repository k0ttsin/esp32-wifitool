# ESP32 Wi-Fi Penetration Tool
Wi-Fi Penetration Tool with ESP32

<a href="https://github.com/risinek/esp32-wifi-penetration-tool.git">Original Tool</a>
Crd To Owner [@risinek]

I fixed the errors from original code and builded as a single bin file to flash ESP32 easily.

##Hardware Requirements

1. ESP32
2. Android USB Type B

##How To Flash

Download `wifitool.bin`

In terminal (linux), `esptool.py --chip esp32 write_flash 0x0 wifitool.bin`

And You will see *SSID*:`ManagementAP`. 
Connect it with *password*:`mgmtadmin`.
Go to `192.168.4.1` and you'll see web interface.
