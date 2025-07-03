# STM32-I2C
STM32F446RE Nucleo communicating with peripheral via I2C

Must have:
   1. Easy configuration to be able to switch between windows and linux workstations. 
   2. STM32F446RE communicate with an MPU6050 via I2C
   3. Display I2C data input through a terminal (probably through serial)
   4. Store received I2C data to a unique file (must not overwrite previous files)

Outcome:
* The STM32F446RE was able to communicate effectively with the MPU6050 through I2C
* Through UART, I'm able to display the accelerometer and gyroscope values
* Using Putty, I'm able to log the incoming UART data to a csv file for readability and graphing. 

,
This repo is designed to hold the entire package - STM32 src code, python scripts, etc. This also assumes that you will have to configure the Cube IDE to your own device specifications, and modifications to code may be necessary for certain signals and HAL calls.

# TODO
   * Research python packages required for project
   * Apply a filter to the I2C signal for a smoother application
   * Apply a "current angle" relative to a horizontal using the given acceleration values (i have a previous project that had formulas for the given values)
   *