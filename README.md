# Intro
- I had personal problems with commercial USBASP, so I decided to build my own. 
- In this repository, you can find a simple project for a USBASP based on the atmega328p.
- The design is done on Altium Designer 19.
# Components List:
|Component|Quantity|Description| Was Used|
|----|-----|-------|-------|
|Atmega328p|1|ATmega328p 8 bit Microcontroller DIP-28|Yes|
|AMS1117-3V3|1|3V3 LDO Linear Voltage Regulator SOT-223-3|Yes|
|16 MHz Crystal|1|16 MHz Crystal Oscillator 2 pins TH|Yes|
|3V6 Zener Diode|2|3V6 Zener Diode LL-35|Yes|
|LEDs|1* Green, 1* Red|SMD LED 0805|Yes|
|1.2 kOhm Resistor|3|1.2k Ohm SMD 0805|Yes|
|10k Ohm Resistor|1|10k Ohm SMD 0805|Yes|
|68 Ohm Resistor|2|68 Ohm SMD 0805|Yes|
|22pF Capacitor|2|22pF Ceramic SMD 0805|Yes|
|100nF Capacitor|4|100nF Ceramic SMD 0805|Yes|
|100uF Capacitor|1|100uF Polarized TH|Replaced with 1uF|
|Female Headers|1|TH Female Headers 2 * 3 Vertical pitch = 2.54mm|Yes|
|Male Headers|1|TH Male Headers 1 * 3 Vertical pitch = 2.54mm|Yes|
|Jumper|1| - |Yes|
|USB Port|1|TH USB - B|Yes|

# Schematics:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/c9c8799e-6ade-4f63-ae1f-6f964b84a706" width="600" height="auto">
</p>

# PCB:
Version I was designed on a single layer board, with through-hole components.
<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/c1fcc8fb-6719-4a1f-8c8c-ab6874f21360" width="500" height="auto">
</p>

Version II aimed for a smaller size using SMD components and double layer design.
<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/3f4467a8-25a9-45aa-afa7-54e8431b495c" width="500" height="auto">
</p>

<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/d8ce5e8b-a890-4f3a-a28d-a1f8fb029847" width="500" height="auto">
</p>

<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/e6204277-8d47-45d1-9b0b-2fce669fc03d" width="500" height="auto">
</p>

In Version III, it is aimed to minimize the size even more, and new capabilities, like PIC programming.

# Output:
<p align="center">
<img src="https://github.com/Ahmed0Sherif/USB_ASP/assets/93788514/d805d1f1-9082-4ccf-a757-93fbd208c9f4" width="500" height="auto">
</p>



