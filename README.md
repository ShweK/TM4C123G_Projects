# TM4C123G LaunchPad Embedded Projects

This repository contains a collection of embedded systems projects developed on the Texas Instruments TM4C123GXL LaunchPad. Each project demonstrates practical applications using C and low-level hardware interfacing.

## 📁 Projects

| # | Project | Description |
|--|---------|-------------|
| 01 | Blink LED | Basic GPIO toggle with delay |
| 02 | Button Input | Read button state and control LED |
| 03 | PWM Buzzer | Use PWM to generate tone on buzzer |
| 04 | ADC Temperature | Read analog temp sensor and display |
| 05 | UART Echo | Echo characters back over UART |

## 🧰 Tools

- Code Composer Studio (TI)
- TivaWare Peripheral Driver Library
    Download TivaWare from TI: https://www.ti.com/tool/SW-TM4C
    Extract it somewhere, e.g., C:/ti/TivaWare_C_Series-2.2.0.295
- Optional: GNU ARM + Makefile for CLI build

## 🧪 Hardware Used

- TM4C123GXL Eval Board
- Breadboard, LED, Push Button, Buzzer, TMP36 Sensor

## 🗂 Structure

- `projects/` – Each project with own source and config
- `common/` – Shared drivers or utilities
- `hardware/` – Schematics and wiring diagrams
- `docs/` – Setup guides and development notes

