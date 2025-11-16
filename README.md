# platam_pcb
Industrial Medical-Grade Signal Measurement & Waveform Generation PCB

High-precision | Low-noise | LCD Display | Industrial-ready

This repository contains the hardware design files, schematics, PCB layout, and documentation for an industrial-grade medical/measurement PCB designed for accurate analog waveform generation, biosignal acquisition, low-noise performance, and rugged field operation.

The board is not a wearable device — it is intended for bench-top and industrial environments requiring reliability, isolation, and clean analog performance.

🚀 Features
🎚️ Precision Waveform Generation

16-bit high-accuracy external DAC (AD5686R or equivalent)

Low-noise buffer stage (OPA16xx series)

Supports sine, square, triangle, custom waveforms

Clean, stable output with reconstruction filtering

🩺 Medical/Industrial Signal Acquisition

High-resolution ADC (ADS131E08 / ADS1115) for biosignals

Ultra-low-noise instrumentation amplifier (INA333/AD8226)

Optional digital MEMS microphone (I²S)

Optional MAX30102 / MAX86150 for pulse/SpO₂/PPG sensing

Galvanic isolation options for patient safety

💡 Display & UI

4.3” industrial TFT LCD (480×272)

Parallel or SPI interface

Compatible with LVGL UI framework (STM32)

📡 Connectivity

Industrial Ethernet (with magnetics) for MQTT/HTTP

Optional Wi-Fi + Bluetooth module (ESP32)

UART/SPI/I²C expansion ports

🔌 Industrial Power Design

9–36V DC input

Isolated DC-DC converter for safety

Low-noise analog LDOs (TPS7A4700 / LT3042)

Separate analog/digital ground planes

🛠️ Hardware Architecture

MCU: STM32H7 or equivalent

DAC: AD5686R (16-bit, SPI)

ADC: ADS131E08 / ADS1115

AFE: INA333 / AD8226 + filtering

MIC: INMP441 / ICS-43434 (I²S)

PPG sensor: MAX30102 family

Ethernet PHY: LAN8720 / TLK110

LCD: 4.3” TFT with integrated driver

Power: Isolated DC-DC → LDO rails

Protection: TVS, ESD diodes, common-mode chokes
