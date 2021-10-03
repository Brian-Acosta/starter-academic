---
date: "2021-03-20-T00:00:00Z"
image:
  caption: 'Pomodoro Timer'
  focal_point: Smart
summary: I designed and built this 3D-Printed Pomodoro timer based on the Raspberry Pi Pico microcontroller board this past spring. It now sits on my desk in lab to keep me focused!
tags:
- Design
title: Pomodoro Timer
---

The timer uses a periodic interrupt to keep time. A finite state machine starts, stops, and resets the clock when button presses trigger I/O interrupts. The LED 7-segment display is driven by a multiplexer which comminicates with the pico board over I2C.  