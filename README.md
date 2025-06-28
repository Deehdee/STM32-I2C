# STM32-I2C
STM32F446RE Nucleo communicating with peripheral via I2C

Must have:
   1. Easy configuration to be able to switch between windows and linux workstations. 
   2. STM32F446RE communicate with an MPU6050 via I2C
   3. Display I2C data input through a terminal (probably through serial)
   4. Store received I2C data to a unique file (must not overwrite previous files)

Outcome:
* The STM32F446RE was able to communicate effectively with the MPU6050 through I2C. Through UART, I'm able to display the accelerometer and gyroscope values. Using Putty, I'm able to log the incoming UART data to a csv file for readability and graphing. 
