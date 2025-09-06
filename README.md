# Self-Balancing Robot using ESP32 and Nema17  

This project is a **self-balancing robot** powered by an **ESP32** and two **Nema17 stepper motors**. It uses a **GY-521 (MPU6050) gyro sensor** for orientation and stability feedback, while a second ESP32 acts as a remote controller. The system is compact, efficient, and designed for experimenting with robotics and control systems.  

---

## Features  
- **Dual Nema17 Stepper Motors** for smooth and precise motion.  
- **GY-521 Gyro Sensor** to measure tilt and balance.  
- **ESP32-based Control** with one ESP32 onboard the robot and another as a wireless remote.  
- **OLED Display** for real-time status and feedback.  
- **Li-ion Battery Powered** for portability and extended runtime.  
- **Push Button** for easy resets or control inputs.  

---

## Parts List  

| Qty | Component              |  
|-----|------------------------|  
| 2x  | Nema17 Stepper Motor   |  
| 2x  | DRV8825 Stepper Driver |  
| 2x  | ESP32 (1 robot, 1 remote) |  
| 1x  | GY-521 Gyro Sensor (MPU6050) |  
| 2x  | Rubber Wheels          |  
| 2x  | PCB 8x12               |  
| 3x  | 3.7V Li-ion Battery    |  
| 1x  | 0.96" OLED Display     |  
| 1x  | Push Button            |  

---

## How It Works  
The robot constantly reads data from the **GY-521 gyro sensor** to detect tilt. Based on this feedback, the ESP32 adjusts the stepper motors via the DRV8825 drivers to maintain balance.  
- One ESP32 handles the **real-time balancing logic**.  
- Another ESP32 is used as a **remote controller**, sending wireless commands to the robot.  
- The **OLED display** shows sensor data, system status, or battery info.  

---


### Project Goal  
The Self-Balancing Robot is an exploration in combining **control systems**, **sensor integration**, and **embedded programming**. It serves as both a learning platform and a stepping stone toward more advanced robotics projects.  
