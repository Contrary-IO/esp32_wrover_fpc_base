# esp32_wrover_fpc_base
The goal of this project is to make a board system that can replace 90% of my raspberry pi projects.

### esp32_wrover_fpc_base advantages:

* Size
* Prize
* Flexibuility
* Less constrains

### esp32_wrover_fpc_base disadvantages:
* It cant even be a bad desktop computer

### Design goals (ongoing):
* Easy to assemble, all smd, one side components
* Default pins, use as many of the default pin outputs
* High flexibility, add as few of contraints to base board
* Low production price

### Outputs:

#### IO:
* 1 14 port horizontal 1.0 MM FPC connector
* 1 14 port vertical 1.0 MM FPC connector
#### Power/IO
* 1 10 port horizontal 1.0 MM FPC connector
* 1 10 port vertical 1.0 MM FPC connector
 
### IO connections:
#### IO:
* I2C SCL     IO22
* I2C SDA     IO21
* SPI MOSI    IO23
* SPI MISO    IO19
* SPI CLK     IO18
* SPI CS      IO5
* DAC DAC2    IO26
* RTC         IO25-36
* ADC ADC1    IO32-39
* GND
* 3V3
* 3V3
* EXT

#### Power/IO:
* 3V3
* 3V3
* TX
* RX
* EN
* FLASH   IO0
* RTC/ADC/PWM IO25
* SCL
* SDA
* GND

Easyeda link:
https://easyeda.com/Contrary.IO_pub/esp32_wrover_fpc_base

#### Partlist
* JUSHUO AFA07-S10ECA-00 - C262737
* JUSHUO AFA07-S10FCC-00  - C262720
* 605 - 10K - Resistor - C25804
* 605 - 1uf - Capacitor - C15849
* 605 - 10uf - Capacitor - C1691
* 605 - 100nf - Capacitor - C1591

