# stm32_bootloader
## Description 
a custom bootloader for a STM32F4 microcontroller with the following capabilities: 
* In Application Programming (IAP).
* Read the microcontroller specific data saved in flash. 
* Flash related configurations: setting up read and write protections for different flash sectors.
* Flash Mass/Sector erase. 
* Read and display the protection status of the flash memory.
* Jump to the specified address to execute the code on the flash memory.
The HOST/python contains the source code for the host to communicate with the STM32 board.
The User_app_stm32f446x/Src contains the user application that will be loaded to the flash

## Usage

For this project [Nucleo-F446RE](https://www.st.com/en/evaluation-tools/nucleo-f446re.html) board was used, but you can use code and adjust it to your board.
