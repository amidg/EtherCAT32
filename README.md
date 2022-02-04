# EtherCAT32
EtherCAT32 - Open-source board designed for industrial applications and device simulation over EtherCAT fieldbus. Main controller is ESP32-WROVER with external SPI Flash and PSRAM. EtherCAT controller is LAN9252, same as Beckhoff EL9800. 

This board is designed to demonstrate SOEM capabilities (https://github.com/OpenEtherCATsociety/SOEM) to be used on embedded applications such as:
- ROS
- Arduino projects
- Robotics and other self-driving machines

# Revisions:
## Revision #1:
- LAN9252 + ESP32-WROVER-B (16MB, 8MB PSRAM)
- IO functionality (IO link)
- Simple BDC driver for 24V applications: DRV8847

## Revision #2: 
- LAN9252/54 + ESP32-S3
- IO functionality (IO link)
- BLDC high-power driver + servo
