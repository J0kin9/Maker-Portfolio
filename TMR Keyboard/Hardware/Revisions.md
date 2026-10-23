# MacroPad
## Version: 1.0.0
This version was the first version of the board developed. This board used a STM32F072VB microcontroller.

Daniel's boo boos:
- VDDA: I was unaware that the VDDA pins powered . When I first designed the board I was under the presumption that since I was using the internal oscillator and wasnt using any pins for analog work I would not need to connect VDDA and subsequently analog ground. However, the microcontroller relies on VDDA to power the internal oscillator. Without this oscillator the MCU is unable to connect to other devices and this critical loss of functionality is how I found out of the problem.

- IC choice: The STM32F072VB IC is great microcontroller, however it is overkill for my application. 

## Version: 1.0.1

# Devlopment Board