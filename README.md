# Smart Meter Circuit Design
#### Client Name: Manu Evans

## Project Requirements
Below are the core features needed from the PCB:
- DC power supply 5-~60V (DC jack + PoE splitter dual input)
- ESP32 based chipset
- Serial transceiver: RS232, RS485 and RS422. Each UART on the ESP32 that is available should have connection to all these transceivers. However, only one transceiver will be active at one time.
- USB for programming and debugging
- Ethernet transceiver should be simple; just RMII connection. Some suggestions RTL8201 or LAN8720A as main chipset
- CAN Transceiver
- SD Card Interface
