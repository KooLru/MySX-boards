# STM32F103C8T6 Blue pill

Some chars about blue pill board

SPI1 for NRF24

SPI2 for W5100|W5500 module (MYSX_SPI)

I2C 2 (MYSX_I2C) SDA PB11  SCL PB10

Before begin call

  Wire.setSDA(MYSX_SDA);

  Wire.setSCL(MYSX_SCL);


[Arduino_Core_STM32](https://github.com/stm32duino/Arduino_Core_STM32) 

Sketch file

[MySensors STM32 Cores / branch stm32_cores](https://github.com/KooLru/MySensors/tree/stm32_cores)

[MySensors STM32 Cores / branch spi2](https://github.com/KooLru/Ethernet/tree/spi2)


MySensors Gateway with w5500 | w5100 | Serial adapter

## PCB
![TOP](images/pcb_rev1_top.png) 
![Bottom](images/pcb_rev1_bottom.png)

[Actial GERBER files](pcb/bluepill_rev1_2019-06-23.zip) 

## Components

**STM32F103C8T6 "Blue pill" board**  [Aliexpress](https://l.kool.ru/stm32)

The Chinese development boards are available from webshops like Ebay, AliExpress, Wish, Taobao, and many more. 

More info: [stm32-base.org](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill.html) 

**MYSX Pinheader** [2x10 male](http://ali.pub/3063a0 ) 

**NRF24 Pinheader** [2x4 female](https://l.kool.ru/hdrf1r)

**S1 switch** [xxxx](https://l.kool.ru/) 

AMS-1117-3.3 LDO

Passive componetns

C1 capacitor
C2 capacitor
C3 capacitor

R1-R2 

L1-L3

## Useful links
[OpenHardware.io](https://www.openhardware.io/view/793/MySX-STM32-BluePill)

[Assembled on Ebay](https://www.ebay.com/itm/383620630882)

[Set up STM32 "blue pill" for Arduino IDE](https://www.onetransistor.eu/2017/11/stm32-bluepill-arduino-ide.html)

[Program "blue pill" with STM32 Cores in Arduino IDE](https://www.onetransistor.eu/2020/01/stm32-bluepill-arduino-support.html)

[How to burn STMduino bootloder (RUS)](https://elchupanibrei.livejournal.com/30157.html)

[Pinout source](https://predictabledesigns.com/introduction-stm32-blue-pill-stm32duino/)

