# noSleepCam
A smart alarm system using a Raspberry Pi camera that detects if you're still lying in bed and whether the bed is organized. The alarm only stops when you're out of bed and the bed is clean. It connects with a mobile app for status updates and control.

## 📸 What It Does

- Detects if someone is still lying on the bed using a camera.
- Verifies if the bed is made (organized) based on a reference image.
- Triggers an **alarm (buzzer, speaker, etc.)** if you're still in bed.
- Communicates with a mobile app to show status and control alarms.
- Can use **Arduino** for physical components like buzzers, vibration motors, etc.

## 💡 Motivation

Fake wake-ups? Not anymore. This project ensures you get out of bed **and** make it — or face the consequences of an annoying alarm!

## 🧰 Hardware

- **Raspberry Pi** (with camera module)
- **Buzzer / Speaker / Vibration motor**
- Optional: LEDs, Bluetooth module

## 🧠 Software

- Python (for Raspberry Pi logic)
- OpenCV or TensorFlow Lite for image recognition
- Flask or MQTT for communication
- Mobile app: Flutter or React Native (TBD)

## 🚀 Features

- Bed presence detection via image processing
- Clean/unclean bed detection using reference image
- Alarm activation until both conditions are met
- App to show real-time status and control options

## 📦 Coming Soon

- Smart snooze (limited time)
- Cloud logging
- App notification scheduler
- Smart plug integration to disable room power until bed is clean

## 🔧 Setup

_To be added once prototype is finalized. Will include:_
- Circuit diagrams
- Arduino + Raspberry Pi wiring
- Mobile app pairing instructions

---

> PRs, feature ideas, and contributions welcome!
