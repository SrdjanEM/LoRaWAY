# LoRaWAY
![ESP32-C3](https://img.shields.io/badge/ESP32--C3-E7352C)
![LoRa](https://img.shields.io/badge/LoRa-Semtech-blue)
![LoRaWAN](https://img.shields.io/badge/LoRaWAN-Enabled-green)
![IoT](https://img.shields.io/badge/IoT-Embedded-orange)

LoRaWAY is an ESP32-C3–based project that interfaces with the **KG200Z LoRa module** to enable both **peer-to-peer (P2P) LoRa communication** and **LoRaWAN connectivity**.

The ESP32-C3 acts as a controller and bridge, handling configuration, command parsing, and data exchange with the KG200Z module via AT commands.
![LoRaWAY](LoRaWAY.png)
## Features

* 📡 **LoRa P2P communication**

  * Direct device-to-device data exchange
  * Suitable for testing, prototyping, and local networks
* 🌍 **LoRaWAN support**

  * Ability to join and communicate with a LoRaWAN network
  * Supports standard LoRaWAN workflows (join, uplink, downlink)
* 🔁 **Flexible data handling**

  * Exchange various types of information (sensor data, status, commands)
* ⚙️ **ESP32-C3 control**

  * Configuration and communication managed by ESP32-C3 firmware
  * Easy integration with additional peripherals if needed

## Hardware

* **MCU:** ESP32-C3
* **LoRa Module:** KG200Z
* **Communication Interface:** UART (AT commands)

## Project Structure

* ESP32-C3 firmware handles:

  * KG200Z initialization
  * Mode switching (P2P ↔ LoRaWAN)
  * Data transmission and reception
* KG200Z module handles:

  * LoRa radio operations
  * Network communication

Features and functionality may be expanded as development continues.

