# 💡 Room Lamp Control (Arduino + Bluetooth)

A **smart room lamp control system** built with **Arduino** and **Bluetooth communication**.  
The device can be controlled **manually** using a physical switch or **wirelessly** via a mobile app.

---

## ✨ Features
- 🔘 **Dual control**: manual switch & Bluetooth mobile app
- 📲 Mobile app for wireless on/off control
- 💡 Real-time lamp state feedback
- ⚡ Low-cost and easy to implement
- 🔧 Expandable for home automation integration

---

## 🛠️ Hardware & Tools
- **Arduino Nano**
- **Bluetooth Module HC-05**
- **Relay Module** (for lamp control)
- **Physical Switch / Push Button**
- Mobile app (custom app or Serial Bluetooth Terminal)

---

## 🔗 System Architecture
```mermaid
flowchart LR
  Switch[Manual Switch] --> |Control| Arduino
  Phone[Mobile App] --> |Bluetooth| Arduino
  Arduino --> Relay[Relay Module] --> Lamp[Lamp]
