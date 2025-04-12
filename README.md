# QuadBalance-PID

# 🛸 PID Controlled Self-Balancing Quadcopter

This is a personal project to help me learn the basics of control systems and controllers. Right now, it's a simple quadcopter that uses a **PID controller** to maintain stable hovering. 

I'm currently focusing on getting the hover stable using just PID tuning. I plan to continue improving this project during the summer when I'm back from college.

## 🚀 Features

- Maintains a stationary hover using PID control
- Powered by an **ESP32** microcontroller for fast data processing from the transmitter module
- Real-time response tuning and control loop updates

## 📅 Roadmap / TODO

- [ ] Improve PID tuning for more stability
- [ ] Add altitude hold with barometer
- [ ] Implement pitch, roll, and yaw control
- [ ] Integrate IMU Kalman filtering
- [ ] Add safety failsafes and remote kill switch

## 📦 Hardware Used

- ESP32 Microcontroller
- Brushless motors + ESCs
- Transmitter/Receiver module
- MPU6050 (for IMU data)

## 📜 Notes

This project is for learning purposes only and isn’t production-level. Everything is being tuned and tested manually, and the PID controller is written from scratch.

## 📌 Disclaimer

I'm still a student and learning as I go, so feel free to suggest improvements or corrections if you notice anything!

---

