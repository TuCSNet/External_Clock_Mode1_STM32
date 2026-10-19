# External_Clock_Mode1_STM32

## Overview

This project demonstrates how to use TIM3 in External Clock Mode 1, with MCO1 as the external clock source, to control the LED blinking frequency.

Note: Connect PA8 to PA7 with a jumper wire to observe the LED's behavior.

## Hardware

- STM32 Nucleo-F446RE development board
- USB connection to PC

## Software and Tools

- STM32CubeIDE
- STM32CubeMX
- STM32 HAL
- C programming language

## Features

- TIM3 is configured in External Clock Source 1, using the 16Mhz MCO1 output as its external clock source, to blink the LED at 0.5Hz

## Project Structure

- `Core/Inc/` — application header files
- `Core/Src/` — application source files
- `Drivers/` — STM32 HAL and CMSIS dependencies
- `.ioc` — STM32CubeMX configuration file
