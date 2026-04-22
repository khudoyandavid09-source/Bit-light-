# 📡 Bit Light — AI-Powered Autonomous System



## 🚀 About the Project
**Bit Light** is an advanced, distributed hardware pentesting tool designed as an autonomous AI companion . It combines high-performance edge computing with multi-protocol radio interaction. Unlike standard ESP32 projects, Bit Light offloads heavy AI logic to a dedicated **NVIDIA DGX** host, using a dual-ESP32 architecture for seamless voice and signal processing.

> **Warning:** This project is for educational and research purposes only. Use it responsibly and according to your local laws.

---

## ⚡ Key Features

### 🧠 Intelligence & Voice
* **Jarvis Core:** Integrated AI assistant running on NVIDIA DGX.
* **Voice Interaction:** Real-time speech-to-text and text-to-speech via I2S.
* **Smart UI:** Interactive menu navigation via hardware Joystick.

### 📶 Radio & Signal Intelligence
* **Sub-GHz (CC1101):** Scanning and interacting with 315/433/868/915 MHz.
* **NRF24:** 2.4GHz protocol analysis and device interaction.
* **Infrared:** Reading and sending IR codes for appliances control.

### 🔌 Connectivity
* **API Bridge:** Dedicated ESP32 node for high-speed synchronization with the AI Host.
* **Storage:** SD-Card support for logs, database, and offline voice assets.

---

## 🛠️ Required Components (BOM)

| Component | Description |
| **ESP32-S3 (N16R8)** | Main interface and Voice MCU (16MB Flash / 8MB PSRAM) |
| **ESP32 (any)** | Dedicated API Connectivity Bridge |
| **NVIDIA DGX** | Main AI/LLM Computing Host |
| **CC1101** | Sub-GHz Radio Module |
| **NRF24L01** | 2.4GHz RF Module |
| **Display (LCD/OLED)** | SPI/I2C Screen for telemetry |
| **Joystick** | 2-Axis Analog Joystick for navigation |
| **I2S Kit** | Microphone & Speaker for Voice AI |
| **IR Set** | IR Transmitter and Receiver |

---



