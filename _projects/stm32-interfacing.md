---
layout: page
title: STM32 interface experiments
description: Interface Technology coursework, 2025
importance: 7
category: academic
---

Embedded C experiments on an STM32 development board (standard peripheral library), each documented in a lab report with code and results.

- **Timer-based key debounce:** 1 ms TIM3 interrupt sampling the last 100 key states and treating a key as pressed or released when at least 70 samples agree, avoiding blocking delays.
- **Long and short press:** timer-measured press duration (1 second threshold) mapped to different LED and buzzer actions, including a capacitive touch pad variant.
- **Serial control:** interrupt-driven UART (115200 baud) that parses a number sent from a PC and sounds the buzzer that many times.
