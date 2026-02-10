# 📟 Microwave Oven Controller Using PIC16F877A

## 📌 Project Overview

This project is a simulation-based embedded system that demonstrates the working of a microwave oven controller using the PIC16F877A microcontroller. It implements multiple cooking modes, user interaction through a keypad, real-time display using an LCD, and fan control for proper heat circulation.

The system is developed using Embedded C and tested using simulation tools to understand real-time embedded system behavior.

---

## 🎯 Project Objectives

- Design a microwave oven controller using a microcontroller  
- Implement multiple cooking modes  
- Provide user interaction using keypad and LCD  
- Control timer and fan operations  
- Simulate real-time embedded system behavior  

---

## ⚙️ Features

- Multiple Operating Modes (Micro, Grill, Convection, Start)  
- User-Defined Time Settings  
- Start, Pause, Resume, and Stop Controls  
- 16x4 LCD Display Interface  
- 4x4 Matrix Keypad Input  
- Fan Control Simulation  
- Power Level Display (Micro Mode)  
- State Machine-Based Control Logic  

---

## 🛠️ Technologies Used

- Embedded C (XC8 Compiler)  
- PIC16F877A Microcontroller  
- MPLAB IDE  
- PICSIMLAB Simulator  
- GPIO Interfacing  
- Timer Configuration  

---

## 🧩 Hardware Components

- PIC16F877A Microcontroller Board  
- 4x4 Matrix Keypad  
- 16x4 LCD Display  
- Cooling Fan (Simulated)  
- Power Supply Module  

---

## 📂 Project Structure
Microwave_oven_simulation/
│
├── Microoven.X/
│ ├── Source files
│ ├── build/
│ └── dist/
│
├── README.md


---

## 🔄 Operating Modes

### 1️⃣ Micro Mode
- Simulates standard microwave heating  
- Displays power level and remaining time  
- Fan runs continuously  

### 2️⃣ Grill Mode
- Simulates grilling operation  
- Used for browning and roasting  
- Shows timer and status  

### 3️⃣ Convection Mode
- Simulates hot air circulation  
- Supports temperature setting  
- Includes preheating feature  

### 4️⃣ Start Mode
- Quick start with default 30 seconds  
- Time increases in 30-second steps  
- Supports pause and stop  

---

## 🚀 Working Principle

1. System starts in idle state  
2. User selects mode using keypad  
3. Time/temperature is configured  
4. Press Start to begin operation  
5. Fan and timer are activated  
6. LCD shows remaining time  
7. User can pause/resume/stop  
8. System returns to idle mode  

---

## 💡 Challenge & Solution

### LCD Overlapping Issue

**Problem:** Display content overlapped due to improper screen clearing.

**Solution:** LCD clear function was implemented before updating content to ensure proper display.

---

## ▶️ How to Run the Project

1. Clone the repository:
git clone https://github.com/Baba-Shareef-Shikilghar/Microwave_oven_simulation.git
2. Open in MPLAB IDE  
3. Compile using XC8 Compiler  
4. Run in PICSIMLAB or upload to hardware  

---

## 📚 Learning Outcomes

- Embedded C programming  
- PIC16F877A working  
- Keypad and LCD interfacing  
- Timer configuration  
- Debugging techniques  
- Real-time system design  

---

## 🔮 Future Enhancements

- Hardware implementation  
- Door safety sensor  
- Buzzer indication  
- IoT integration  
- Temperature sensor  

---

## 👨‍💻 Author

**Baba Shareef Shikilghar**  
B.Tech ECE | Embedded Systems Enthusiast  

GitHub: https://github.com/Baba-Shareef-Shikilghar  

---

## ⭐ Acknowledgements

Thanks to Emertxe Technologies for training and guidance.

---

## 📄 License

This project is for educational purposes.  
Free to use with proper credit.


