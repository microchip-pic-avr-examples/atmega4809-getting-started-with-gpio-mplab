[![MCHP](../images/microchip.png)](https://www.microchip.com)

 # Wake Up on Button Press

This use case demonstrates how to wake up the microcontroller from Sleep mode by pressing a button. The microcontroller exits Sleep on button press, turns on an LED and goes back to Sleep. On button release, exits Sleep, turns off the LED and goes back to Sleep.

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [TB3229 - Getting Started with General Purpose Input/Output (GPIO)](https://ww1.microchip.com/downloads/en/Appnotes/Getting-Started-with-GPIO-DS90003229B.pdf)
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATmega4809XplainedPro)

## Software Used
- MPLAB® X IDE 5.40 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.30 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- ATmega_DFP 2.2.108 or newer Device Pack

## Hardware Used
- ATMEGA4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)

## Setup
The ATMEGA4809 Xplained Pro Development Board is used as test platform.

<br><img src="../images/atmega4809_xplainedpro.jpg" height="300">

The following configurations must be made for this project:

- Clock configured for 3.33 MHz
- Power-Down sleep mode set
- Global interrupts enabled
- Interrupt enabled for pin PB2, the button
- Pin PB2 configured with internal pull-up

 |Pin                       | Configuration      |
 | :---------------------:  | :----------------: |
 |            PB2           |   Digital input    |
 |            PB5           |   Digital output   |

 ## Operation
 1. Connect the board to the PC.

 2. Open the Wake_Up_On_Button_Press.X project in MPLAB® X IDE.

 3. Set the Wake_Up_On_Button_Press.X project as the main project. Right click on the project in the **Projects** tab and click **Set as Main Project**.

<br><img src="../images/Set_as_Main_Project.PNG" height="500">

 4. Clean and build the Wake_Up_On_Button_Press.X project: right click on the **Wake_Up_On_Button_Press.X** project and select **Clean and Build**.

<br><img src="../images/Clean_and_Build.PNG" height="500">

 5. Select the **ATMEGA4809 Xplained Pro** in the Connected Hardware Tool section of the project settings:
   - Right click on the project and click **Properties**
   - Click on the arrow right next to Connected Hardware Tool
   - Select the ATMEGA4809 Xplained Pro (click on the **SN**), click **Apply** and then click **OK**:

<br><img src="../images/Tool_Selection.PNG" height="500">

 6. Program the project to the board: right click on the project and click **Make and Program Device**.

<br><img src="../images/Make_and_Program_Device.PNG" height="500">

## Demo

<br><img src="images/demo.png">

In this demo, the button is pressed, the microcontroller exits Sleep mode and turns on the LED.

## Summary

This use case demonstrates how to wake up the microcontroller from Sleep mode by pressing a button.
