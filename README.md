 <a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# Getting Started with GPIO (General Purpose Input/Output) Examples (MPLAB® X) Using the ATmega4809 Microcontroller

  This repository contains examples of bare metal source code for General Purpose Input/Output (GPIO) as described in the [TB3229 - Getting Started with General Purpose Input/Output (GPIO)](https://ww1.microchip.com/downloads/en/Appnotes/Getting-Started-with-GPIO-DS90003229B.pdf) document from Microchip. The repository contains three  MPLAB® X projects:

- [<strong>Blink an LED:</strong>](Blink_an_LED) This use case shows how to toggle a pin connected to an LED (for more details, see [<strong>Blink an LED</strong>](Blink_an_LED))
- [<strong>Long and Short button press:</strong>](Long_And_Short_Button_Press) This project uses a pin as input to distinguish between a long and short button press, defined by a delay threshold (for more details, see [<strong>Long and Short button press</strong>](Long_And_Short_Button_Press))
- [<strong>Wake-Up On Button Press:</strong>](Wake_Up_On_Button_Press) Exits Sleep on button press, turns on an LED and goes back to Sleep. On button release, exits Sleep, turns off the LED and goes back to Sleep (for more details, see [<strong>Wake-Up On Button Press</strong>](Wake_Up_On_Button_Press))

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATMEGA4809XplainedPro)
- [Getting Started with General Purpose Input/Output (GPIO)](https://ww1.microchip.com/downloads/en/Appnotes/Getting-Started-with-GPIO-DS90003229B.pdf)


## Software Used
- [MPLAB® X IDE](http://www.microchip.com/mplab/mplab-x-ide) v6.15 or newer
- [MPLAB® XC8](http://www.microchip.com/mplab/compilers) v2.45 or newer
- [ATmega_DFP](https://packs.download.microchip.com/) v3.1.264 or newer


## Hardware Used
- [ATMEGA4809 XPLAINED PRO](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)

<br><img src="images/atmega4809_xplainedpro.jpg" height="300">