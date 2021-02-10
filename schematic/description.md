# MCU

``STM32F103C8T6`` is a MCU with ARM®Cortex-M3 32-bit RISC core operating at a 72 MHz frequency, high-speed embedded memories (Flash memory up to 64 Kbytes and SRAM up to 20 Kbytes), and an extensive range of enhanced I/Os and peripherals connected to two APB buses. 

Board offer two 12-bit ADCs, three general purpose 16-bit timers plus one PWM timer, as well as standard and advanced communication interfaces: up to two I2Cs and SPIs, three USARTs and a CAN.



# Power

The power supply of the board is 12V. It contains ``LT1763CS8`` (Analog Devices) voltage regulator. This regulator are capable of supplying 500mA of output current with a dropout voltage of 300mV.

A key feature of the LT1763x regulators is low output noise. With the addition of an external 0.01µF bypass capacitor, output noise drops to 20µVRMS over a 10Hz to 100kHz bandwidth.



# Peripheral

Board provides contact pads (headers) for connecting external devices via ``SPI``, as well as a programmer via ``SWD`` and a couple of ``GPIO`` outputs.


# LED Driver

All LEDs are PWM-dimmable via ``LED6001`` (ST) single channel LED driver with integrated boost controller. The high-side current sensing, in combination with a P-channel MOSFET, provides an effective protection in case the positive terminal of the LEDs is shorted to ground.
