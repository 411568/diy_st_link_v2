<p align="center"><img src="https://socialify.git.ci/411568/diy_st_link_v2/image?description=1&name=1&pattern=Circuit+Board&theme=Dark" alt="diy_st_link_v2" width="640" height="320" /></p>


<h2>🧐 Features</h2>

ST-LINK is a programmer used with STM32 microcontrollers. It is sold by STMicroelectronics and by many other manufacturers and is included in a number of Nucleo/Discovery/etc. development boards.
Because of that, the schematics for it are available on the internet and you can build one yourself... and that is what I did.

My schematic was inspired by two diy projects, available under the following links: [STM32World](https://stm32world.com/wiki/DIY_STM32_Programmer_(ST-Link/V2-1)), [EmbdedBlog](https://embedblog.eu/?p=780). 
The design was then compared with one of STMs own designs from a Nucleo board.
You may think that the schematics could be easily reverse engineered, but you can't get the firmware for it, as it is proprietary STM softwa, right? Well, it seems someone has already done the job for us: [bootloader](https://github.com/Krakenw/Stlink-Bootloaders).

The schematic and PCB were both designed using KiCAD 6.0

![Schematic kicad](/assets/images/st_link/schematic.png)

![PCB kicad](/assets/images/st_link/pcb.png)

![3d view](/assets/images/st_link/3dview.png)

<h2>💻 Parts list</h2>

* STM32F103C8T6 microcontroller (you can use the CBT6 for more memory)
* TC1263 3.3V linear regulator
* IDC connector
* pin header for programming
* USB B connector
* 2x 0805 SMD LED
* 2x 220Ohm resistor
* 2x 100Ohm resistor
* 1MOhm resistor
* 3x 10kOhm resistor
* 2x 100kOhm resistor
* 2x 4.7kOhm resistor
* 1.5kOhm resistor
* 36kOhm resistor
* 470pF ceramic capacitor
* 1uF electrolytic capacitor
* 4x 100nF ceramic capacitor
* 2x 20pF ceramic capacitor


<h2>📝 Assembled project</h2>

![st link photo](/assets/images/st_link/assembled.jpg)


<h2>🛡️ License:</h2>

This project is licensed under the MIT License.


<h2> 🙋‍♂️Authors </h2>

- Krzysztof Sikora

<h2>💖Like my work?</h2>

If you have any questions about the project feel free to contact us via email: krzysieksikora717@gmail.com