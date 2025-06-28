# 🚘 Smart Automotive Safety System | Road Hypnosis Alert + Anti-Theft Face Recognition

This project is an basic system idea designed for enhancing safety in modern vehicles, especially in highway and autonomous driving scenarios. It contains two key modules:

1. 🧠 *Highway Hypnosis Detection System* – Monitors driver eye activity using video and alerts in case of trance/drowsiness.
2. 🔐 *Anti-Theft Face Recognition System* – Authenticates the identity of the driver before allowing vehicle ignition.

---

## 🛠 Application Domain
*Automotive / Smart Vehicle Safety Systems*

---

## 🎯 Motivation

The increase in expressways and high-speed travel routes has caused a spike in road accidents, especially due to drowsiness, and road hypnosis.

- ⚠️ Deaths due to such incidents have risen by *18%*.
- 🛑 Road hypnosis is a *mental state* where the driver continues driving without conscious awareness or recollection.
- ❗ Such drivers remember nothing of the last 15–20 minutes, making them vulnerable to collisions.

---

## 🧠 Module 1: Highway Hypnosis Detection

This module:
- Takes a *video input of the driver*
- Analyzes *eye blinking rate*
- Detects *hypnosis or trance state*
- Issues an alert (console/text-based) when signs are detected

### 📥 Input:  
- This notebook expect a video file as input. (You can test with any driver-facing camera footage.)

### 📤 Output:
- Text: "Trance" or "Normal" based on eye blink patterns.
- Audio: A beep sound (expected to add audio file (frequency of 1khz to 2khz can be created using audio editing softwares))

---

## 🔐 Module 2: Anti-Theft Face Recognition System

This module:
- Uses *face recognition* to allow only registered users to start the car
- Compares captured input with *authorized faces*
- Triggers if an intruder is detected

### 📥 Input:
- Notebook expects images of registered users and test images. You can create a 'sample_faces/' folder and add any test images to try it yourself.

---

## 🚗 Future Scope

- 🔄 Integration with car dashboard cameras and vehicle systems.
- 📡 Send alerts to owner via mobile app.
- 🔊 Add alarm beeps, vibration feedback, music triggers.
- 🚘 Extension for *autonomous vehicles* to include:
  - In-cabin wellness monitoring
  - AR-based real-time surrounding alerts

---
