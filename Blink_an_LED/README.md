 <a href="https://www.microchip.com" rel="nofollow"><img src="../images/microchip.png" alt="MCHP" width="300"/></a>

 # Blink an LED Using the ATmega4809 Microcontroller

This code example demonstrates how to blink an LED connected to a GPIO pin. The LED spends 500 ms in each ON and OFF states.

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATmega4809XplainedPro)
- [Getting Started with General Purpose Input/Output (GPIO)](https://ww1.microchip.com/downloads/en/Appnotes/Getting-Started-with-GPIO-DS90003229B.pdf)

## Software Used
- [MPLAB® X IDE](http://www.microchip.com/mplab/mplab-x-ide) v6.15 or newer
- [MPLAB® XC8](http://www.microchip.com/mplab/compilers) v2.45 or newer
- [ATmega_DFP](https://packs.download.microchip.com/) v3.1.264 or newer

## Hardware Used
- [ATMEGA4809 XPLAINED PRO](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)

<br><img src="../images/atmega4809_xplainedpro.jpg" height="300">

## Operation

To program the ATMEGA4809 Xplained Pro board with this MPLAB® X project, follow the steps provided in the [How to Program the ATMEGA4809 Xplained Pro Board](#how-to-program-the-atmega4809-xplained-pro-board) chapter.<br><br>

## Setup

The following configurations must be made for this project:

System clock: 3.33 MHz

 |Pin                       | Configuration      |
 | :---------------------:  | :----------------: |
 |            PB5           |   Digital output   |

 ## Demo

<br><img src="images/demo.png" width="800">

The image above shows the waveform of the pin connected to the LED. The pin spends 500 ms in High state and 500 ms in Low state.

## Summary

This project shows how to blink an LED connected to a GPIO pin of the microcontroller.

##  How to Program the ATMEGA4809 Xplained Pro Board

This chapter shows how to use the MPLAB X IDE to program an AVR® device with an `Example_Project.X`. This can be applied for any other projects. 

1. Connect the board to the PC.

2. Open the `Example_Project.X` project in MPLAB X IDE.

3. Set the `Example_Project.X` project as main project:
  <br>Right-click the project in the **Projects** tab and click Set as Main Project.
  <br><img src="../images/Program_Set_as_Main_Project.PNG" width="400">

4. Clean and build the `Example_Project.X` project:
  <br>Right-click the `Example_Project.X` project and select Clean and Build.
  <br><img src="../images/Program_Clean_and_Build.PNG" width="400">

5. Select the ATMEGA4809 Xplained Pro in the Connected Hardware Tool section of the project settings
  <br>Right-click the project and click **Properties**.
  <br>Click the arrow under the Connected Hardware Tool.
  <br>Select the ATMEGA4809 Xplained Pro by clicking on the SN.
  <br>Click **Apply** and then **OK**.
  <br><img src="../images/Program_Tool_Selection.PNG" width="600">

6. Program the project to the board:
  <br>Right-click the project and then Make and Program Device.
  <br><img src="../images/Program_Make_and_Program_Device.PNG" width="600">

<br>

- [Back to Top](#blink-an-led-using-the-atmega4809-microcontroller)
- [Back to Setup](#setup)
- [Back to Demo](#demo)
- [Back to Summary](#summary)
