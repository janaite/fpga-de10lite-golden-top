# FPGA DE10-Lite golden top

All on-board hardware is exposed

- Clock
- SDRAM
- Seven segment display
- Push Keys
- LEDs
- Switches
- VGA output (RGB444)
- Accelerometer
- Arduino
- GPIO

It also contains an instance of a Megafunction PLL clock generator

See more info at: <http://de10-lite.terasic.com>

## FPGA
- MAX 10 10M50DAF484C7G Device
- Integrated dual ADCs, each ADC supports 1 dedicated analog input and 8 dual function pins
- 50K programmable logic elements
- 1,638 Kbits M9K Memory
- 5,888 Kbits user flash memory
- 144 18 × 18 Multiplier
- 4 PLLs

## Memory
- 64MB SDRAM, x16 bits data bus


# Some important Files

| ext | description                 |
|-----|-----------------------------|
|*.cdf| programmer chain            |
|*.ppf| Megafunction config         |
|*.qip| Megafunction config         |
|*.qpf| Quartus II Project File     |
|*.qsf| Quartus II Setting File     |
|*.sdc| Synopsis Design Constraints |