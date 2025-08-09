# MamaHeal — Smart Postpartum Recovery Belt

**Team**: INCM4T208  
**Hackathon**: JIPMER × IITB MedTech Hackathon 2025

---

## Project Overview
MamaHeal is a lightweight wearable belt prototype designed to support mothers after C-section. The belt captures recovery-relevant signals (posture, ambient temperature & humidity, hydration reminders, and optional muscle activity) and streams them to a companion mobile app over Bluetooth Low Energy (BLE). It can also provide gentle vibration feedback for comfort and posture reminders.

> **Goal:** Provide personalized, continuous postpartum monitoring and actionable insights to reduce complications and aid recovery.

---

## Features
- Real-time posture detection using MPU6050 (accelerometer + gyroscope)
- Ambient temperature & humidity logging (DHT11)
- Water-intake and pelvic-floor exercise streak counters (app-driven)
- Gentle vibration motor control for non-invasive relief and pelvic muscle exercise guide
- BLE-based data streaming and control (ESP32)
- App-friendly JSON payload structure for easy parsing

---

## Hardware (Suggested Components)
- ESP32 development board (BLE-capable)
- MPU6050 (accelerometer + gyroscope) — posture detection
- DHT11 — temperature & humidity
- Optional EMG module (for pelvic floor muscle monitoring) — future expansion
- ERM / LRA vibration motor + MOSFET / motor driver
- Li-ion battery + TP4056 charging module
- Wires, connectors, soft enclosure / breathable belt straps

---

## Software Structure
