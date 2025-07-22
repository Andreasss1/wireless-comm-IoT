# 🌐 DHT22 IoT Project with Wireless Communication Code Examples

The **DHT22** is a temperature and humidity sensor widely used in IoT projects due to its simplicity and reliability. This repository provides **implementation examples** for multiple wireless communication technologies, along with a comparison of their **strengths and weaknesses** for IoT use cases.

---

## 🚀 About This Project

This project helps developers understand:
- 📝 How to write code for DHT22 data transmission over different wireless protocols.
- 📡 The trade-offs between BLE, Zigbee, LoRa, Sigfox, NB-IoT, GSM, and 4G/5G.
- 🔒 Security and performance considerations for each technology.

---

## 📡 Wireless Technology Comparison

| Technology | Range         | Bandwidth           | Latency         | Power         | Node Capacity     | Security                          | Primary Use Case                        |
|------------|---------------|---------------------|------------------|---------------|--------------------|-------------------------------------|------------------------------------------|
| **BLE**    | 10–100 m      | 1–3 Mbps            | 3–300 ms         | Very Low      | 1–8               | AES-CCM encryption (128-bit)       | Personal Area Networks, Wearables       |
| **Zigbee** | 10–100 m      | 250 Kbps            | 20–100 ms        | Low           | 65,000            | AES-128 encryption                 | Smart Home, Building Automation         |
| **Z-Wave** | 30–100 m      | 40–100 Kbps         | 50–200 ms        | Low           | 232               | S2 Security (Elliptic Curve, AES)  | Premium Smart Home Devices              |
| **LoRa**   | 2–15 km       | 0.3–50 Kbps         | 1–10 seconds     | Very Low      | 1,000+            | AES-128 encryption                 | Agriculture, Smart City                 |
| **LoRaWAN**| 2–15 km       | 0.3–50 Kbps         | 1–10 seconds     | Very Low      | Millions          | AES-128 encryption, MIC            | Wide Area IoT Networks                  |
| **Sigfox** | 3–50 km       | 100–600 bps         | 20–30 seconds    | Ultra Low     | Millions          | Lightweight AES-based encryption   | Asset Tracking, Utility Monitoring      |
| **NB-IoT** | 1–35 km       | 200 Kbps            | 1.6–10 seconds   | Low           | 50,000+           | LTE-level encryption (128-bit)     | Smart Meters, Agriculture               |
| **GSM**    | 1–35 km       | 14.4 Kbps           | 500 ms – 2 s     | Medium        | 1,000+            | A5/1 & A5/3 encryption             | Remote Monitoring, Legacy IoT           |
| **4G/5G**  | 1–100 km      | 150 Mbps – 10 Gbps  | 10–100 ms        | High          | 1,000–10,000       | 256-bit encryption, SIM-based auth | Video Streaming, Real-Time Applications |

---

## 🌱 Why DHT22?

The DHT22 sensor offers:  
- ✅ High accuracy for temperature (±0.5°C) and humidity (±2–5%).  
- ✅ Wide operating range (-40°C to 80°C, 0–100% RH).  
- ✅ Simple integration with microcontrollers (ESP32, Arduino, Raspberry Pi).  

---

## 🚀 Example IoT Implementation

This project demonstrates how the DHT22 sensor can be integrated with multiple wireless communication technologies for diverse IoT use cases such as **smart agriculture**, **environment monitoring**, and **industrial IoT**.

---

## 📖 Contents

- 📦 DHT22 sensor setup guide  
- 🌐 Wireless communication configuration (BLE, Zigbee, LoRa, etc.)  
- ⚡ Power optimization for IoT nodes  

---

<div align="center">

## 📬 Need a Similar Project? Let's Collaborate!
If you need a **custom IoT project** for **smart home, agriculture, industrial monitoring**, or other use cases,  
I’m ready to assist you!  

📧 **Reach out at:**  
### andreas.sebayang9999@gmail.com  

Let’s create something amazing together! 🚀

</div>
