

# 💧 Water Level Controller using 8051 Microcontroller By Gowtham Varshith

---

## 🚀 Overview

This **Water Level Controller** project leverages the **8051 microcontroller** to automatically control the water motor by detecting the water level in a tank. The system monitors the tank's water level and turns **ON** the motor when the water is low and **OFF** when the tank is full. This prevents water overflow and helps conserve resources. The real-time water level is displayed on an LCD screen, allowing easy monitoring.

---

## ✨ Introduction

The **Water Level Controller** automatically manages water levels in overhead tanks, pumps, and containers. This project, built with an **8051 microcontroller**, solves the issue of water wastage by ensuring the motor operates only when needed, turning off once the tank is full. It’s a practical solution for homes, apartments, and commercial spaces where manual monitoring is impractical.

This project integrates an **LCD display** to show water levels, providing a visual update on whether the tank is **empty, filling, or full**. The controller is programmed to ensure reliable water management, conserving both water and electricity by preventing overflow and unnecessary motor usage.

---

## 🌟 Need for the Project

Controlling the water level manually can lead to wastage, especially in large setups like buildings or industrial systems. The **Water Level Controller** solves this by:
- Ensuring **continuous water supply** by filling the tank automatically when needed.
- **Saving energy** by switching off the motor when the tank is full.
- Providing real-time updates on the water level, reducing the need for manual checks.

---

## ⚙️ Applications
- **Fuel level indicator** for vehicles.
- **Water management** in large buildings or complexes.
- Industrial use for **automated liquid level control**.
- **Homes and apartments** to prevent water overflow and conserve resources.

---

## 🧰 Components Used
- **AT89S52 Microcontroller** (or any 8051 based Microcontroller)
- 8051 Programmer (Programming Board)
- 11.0592 MHz Quartz Crystal
- 2 x 33pF Capacitor
- 2 x 10KΩ Resistor (1/4 Watt)
- 10µF Capacitor
- Push Button
- 1KΩ x 8 Resistor Pack (for Pull-up)
- 16 x 2 LCD Display
- 5V Relay
- 4 x 2N2222 (NPN) Transistors
- DC Motor (for demonstration)
- 10KΩ Potentiometer
- 1N4007 PN Junction Diode
- Power Supply
- **Keil µVision IDE** for programming
- **Proteus** for circuit design and simulation

---

## 🔄 How It Works

The **Water Level Controller** works by continuously monitoring the water level via sensors:
- **Low Water**: The motor automatically switches **ON** when the water falls below a certain level.
- **Half-Full Tank**: When the water reaches the midpoint, the motor continues running.
- **Full Tank**: Once the water hits the full level, the motor switches **OFF** to prevent overflow.

The system also ensures the water level is displayed on an **LCD screen**, showing real-time updates about the tank’s status.

---

## 📝 Algorithm for Water Level Control
```ruby
1. Configure the microcontroller pins P0.0, P0.1, and P0.2 as inputs for detecting water levels. Use P0.7 as an output to control the motor.
2. Initialize the LCD to display water levels.
3. Continuously monitor the sensor input pins:
   - If all pins are LOW, display "TANK EMPTY" on the LCD and set P0.7 HIGH to run the motor.
   - If P0.0 is HIGH, display "WATER LEVEL: LOW" and keep the motor running.
   - If P0.1 is HIGH, display "WATER LEVEL: HALF" and continue running the motor.
   - If P0.2 is HIGH, display "TANK FULL" and set P0.7 LOW to turn off the motor.
```

---

## 🔧 How to Operate the Water Level Controller

1. **Write the program** for the Water Level Controller in **Keil µVision IDE** and generate the **.hex** file.
2. **Burn the program** into the microcontroller using an external programmer and simulate using **Proteus**.
3. Set up the circuit as per the provided diagram and connect the sensors and motor.
4. Monitor the water level through the LCD:
   - If the water is below the lowest sensor, the motor turns **ON**.
   - When the water reaches the full level, the motor turns **OFF**.

---

## 📊 Results

### Simulation - **Empty Tank**
![Tank Empty](https://user-images.githubusercontent.com/77826589/120591918-96bcfa00-c45a-11eb-99a3-404d0307d29d.PNG)
**TANK IS EMPTY AND MOTOR IS ON**

### Simulation - **Full Tank**
![Tank Full](https://user-images.githubusercontent.com/77826589/120592119-f3201980-c45a-11eb-88a3-73d976a3438d.PNG)
**TANK IS FULL AND MOTOR IS OFF**

---

## ⚠️ Limitations
- Metal parts may **rust** or **deteriorate** over time.
- The wiring inside the tank should be replaced every two years for optimal performance.

---

## 🔗 References
- [Water Level Controller Using 8051](https://www.circuitsarena.com/2018/03/water-level-controller-by-using-8051.html)
- [8051 Microcontroller Project](https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/)

---


## 📋 License

This project is licensed under the **MIT License**. See the full license terms below:


---


## 📞 Contact Information

For any questions or further information, feel free to reach out:

- **Gowtham Varshith**  
- **Email:** gowthamb461@gmail.com  
- **GitHub:** [Gowtham-Varshith](https://github.com/Gowtham-Varshith)  
- **Portfolio:** [Gowtham's Portfolio](https://gowtham-varshith.github.io/Gowtham/)

---

### 🔗 Links

- [Home Automation Project Repository](https://github.com/Gowtham-Varshith/Home-Automation)






