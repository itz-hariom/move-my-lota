# Move My Lota 🚰✨

A real-world to virtual object mapping project using **ESP32**, **MPU6050**, **WebSocket**, and **Unity**.

---

## 🔧 Project Overview

This project synchronizes the motion and touch interaction of a physical *lota* (metal pot) with its 3D digital twin in Unity. It uses:
- ESP32 microcontroller
- MPU6050 accelerometer + gyroscope
- Capacitive touch sensing
- WebSocket for real-time communication
- Unity 3D engine for virtual object animation

---

## 📁 Folder Contents

| File/Folder | Description |
|-------------|-------------|
| `Arduino Script.txt` | Code running on ESP32 to transmit motion + touch data |
| `Unity Script.txt` | Unity-side script to receive data and animate the lota |
| `Lota.glb` | 3D model of the lota used in Unity |
| `GLTFUtility-master` | Utility to import `.glb` files in Unity |
| `websocket-sharp.dll` | WebSocket library used in Unity |
| `JSON NET For Unity.unitypackage` | JSON parsing library for Unity |

---

## 📹 Demo

👉 [Click here to watch the demo video]([https://drive.google.com/your-demo-link-here](https://drive.google.com/file/d/1DWPom6yaC6crkTKnZGvnPpQnTFm4Jif3/view?usp=sharing))  

---

## 🚀 How It Works

1. Real Lota is equipped with ESP32 + MPU6050 and touch wire.
2. Motion and touch values are sent via WebSocket over WiFi.
3. Unity receives the data and animates the 3D Lota accordingly — rotation, position, and touch-triggered effects.

---

## 👨‍💻 Author

**Hariom Tiwari**  
Under the guidance of **Prof. Anmol Srivastava**

---

## 📬 Contact

Feel free to reach out for feedback, collaboration, or queries.

---

**Made with ❤️ by Hariom Tiwari**
