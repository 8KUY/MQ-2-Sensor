# MQ-2-Sensor on STM32F103C8T6
MQ-2 gas sensor + I2C 128x64 display + UART

Here I'm using SSD1306 library to drive the display, and my own code to read data from the sensor. This way is can only sense Alcohol, bu, by using this article you can change it: https://jayconsystems.com/blog/understanding-a-gas-sensor

In the functions there is a parameter "pot" - it is equal to the resistance of the potentiometer on the sensor board (Gas Sensor v1.3) in kOhms
