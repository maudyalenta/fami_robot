# Multipurpose Agricultural Robotic Platform

An autonomous agricultural rover prototype designed to optimize time and labor in small-scale farming through automated seed sowing and targeted irrigation.

---

## 📌 Project Overview
Manual farming operations like repetitive seed dispersion and field irrigation are labor-intensive. This prototype explores field automation using an embedded rover system capable of remote seed delivery and autonomous soil-moisture-triggered watering.

- **Role:** Project Leader & Full-Stack Hardware Programmer
- **Project Type:** Group Academic Project
- **Focus Areas:** Embedded Systems, Circuit Design & Soldering, Firmware Development, Mechanical Prototyping

---

## 🚀 Key Features
* **Wireless Seed Sowing:** Custom dispensing mechanism controlled remotely via Bluetooth gamepad commands.
* **Smart Moisture Irrigation:** Integrated soil sensor that autonomously triggers the water pump when dry soil thresholds are met.
* **Isolated Power Architecture:** Decoupled power rails separating the high-current pump and servos from logic circuits to prevent voltage sags and microcontroller reset loops.

---

## 🛠️ Hardware & Tech Stack
* **Microcontroller:** Embedded C/C++ Firmware
* **Wireless Communication:** HC-05 Bluetooth Module
* **Sensors & Actuators:** Soil Moisture Sensor, 5V Mini Submersible Water Pump, Servos, DC Motors & Motor Drivers
* **Power Distribution:** Regulated dual-rail power supply

---

## 📂 Project Resources & Documentation
Access the complete project documentation, source materials, and demo assets below:
https://drive.google.com/drive/folders/1OkVY8UqeChHE9i9DRk7Ga9Mpuw4MB8Ql

---

## 💡 Engineering Challenges & Key Learnings
* **Firmware Conflicts:** Resolved communication drops by debugging naming collisions between user-defined variables and underlying communication libraries.
* **Power Management:** Mitigated servo jitters and floating digital logic states by redesigning the circuitry with an isolated power distribution setup for high-load actuators.
* **System Requirements:** Emphasized the critical need for upfront mechanical-sensor alignment to ensure reliable real-world interaction between the soil probe and the water delivery tube.
