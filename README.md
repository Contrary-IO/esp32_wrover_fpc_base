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
* 1 30 port horizontal 1.0 MM FPC connector
#### Power/IO
* 1 30 port horizontal 1.0 MM FPC connector
#### Power/IO
* 1 50 port Mezzanine connector
 
### PINOUTS:
#### 20P FPC:
* GND
* IO23
* EN
* IO22
* TXD0
* RXD0
* IO21
* IO32
* IO19
* IO18
* IO25
* IO26
* IO27
* IO14
* IO12
* IO0
* EXT1 (external 1)
* EXT2 (external 2)
* VDD33
* VDD33

#### 30P FPC:
* GND
* EN
* IO22
* TXD0
* SENSOR_VP
* RXD0
* SENSOR_VN
* IO21
* IO34
* IO35
* IO32
* IO19
* IO33
* IO18
* IO25
* IO5
* IO26
* IO27
* IO14
* IO4
* IO12
* IO0
* IO2
* IO13
* IO15
* EXT1 (external 1)
* EXT2 (external 2)
* VDD33
* VDD33

#### 50p Mezzanine
* GND
* EN
* IO22
* TXD0
* SENSOR_VP
* RXD0
* SENSOR_VN
* IO21
* IO34
* IO35
* IO32
* IO19
* IO33
* IO18
* IO25
* IO5
* IO26
* IO27
* IO14
* IO4
* IO12
* IO0
* IO2
* IO13
* IO15
* EXT1 (external 1)
* EXT2 (external 2)
* VDD33
* VDD33

Easyeda link:
https://easyeda.com/Contrary.IO_pub/esp32_wrover_fpc_base

#### Partlist
* JUSHUO AFA07-S10ECA-00 - C262737
* JUSHUO AFA07-S10FCC-00  - C262720
* 605 - 10K - Resistor - C25804
* 605 - 1uf - Capacitor - C15849
* 605 - 10uf - Capacitor - C1691
* 605 - 100nf - Capacitor - C1591

