# 🔐 Password Security System – Digital Logic Design Project

## 📘 Overview

The **Password Security System** is a Digital Logic Design project that verifies a four-digit password (e.g., "2942") using basic logic gates. It provides visual (LEDs) and audio (buzzer) feedback based on whether the entered password matches the preset one. The input digits are also displayed on a seven-segment display.

---

## 📋 Project Details

- **Project Title**: Password Security System  
- **Subject**: Digital Logic Design  
- **Team Members**:
  - 👨‍💻 Ghulam Qadir  
  - 👩‍💻 Noor Malik  
  - 👩‍💻 Sara Tariq  
  - 👩‍💻 Khudema Haroon  
  - 👨‍💻 Muqeem Ahmed  
- **Software Used**: Proteus  
- **Hardware**: Breadboard, Logic Gates, 7-Segment Display, LEDs, Buzzer  
- **Date**: May 22  

---

## ⚙️ Task Description

- Implement a password-based authentication system using logic gates.
- Password digits are entered as 4-bit binary values.
- Each digit is decoded and checked via logic gates.
- Outputs:
  - ✅ Correct password → Green LED ON
  - ❌ Incorrect password → Red LED + Buzzer ON
- A BCD decoder drives the seven-segment display for real-time digit display.

---

## 🧠 Theory of Operation

The system continuously compares user input with the preset password (`2942`) using logic circuits.

- Digits are processed through **NOT** and **AND** gates.
- Matched results are combined into a final **AND** gate.
- Outputs are:
  - 🟢 **Green LED** for match
  - 🔴 **Red LED + Buzzer** for mismatch
- Digits are displayed via **BCD to 7-segment decoder**.

---

## 🛠️ Components Used

- ✅ AND Gates (4-input)
- ❌ NOT Gates
- 🔢 BCD to 7-Segment Decoder
- 🖥️ 7-Segment Display
- 🟢 Green LED
- 🔴 Red LED
- 🔊 Buzzer
- 🔌 Breadboard
- 🧪 Proteus Simulator

---

## 🧱 Block Diagram

[User Input] → [NOT Gates] → [AND Gates] → [Final AND Gate]
↓
┌────────────────────────────────────────────────┐
│ [Match Logic Output] │
└────────────────────────────────────────────────┘
↓ ↓
Green LED (Match) Red LED + Buzzer (Mismatch)

       ↓
  [BCD to 7-Segment Decoder]
       ↓
  [7-Segment Display Output]


---

## 🔬 Testing & Results

- ✅ Circuit was tested on both Proteus and a physical breadboard.
- 🔢 Digits were correctly decoded and displayed.
- 🔋 Outputs triggered properly based on match/mismatch:
  - Green LED ON for valid input.
  - Red LED and Buzzer activated for invalid input.

---

## ✅ Conclusion

This project demonstrates effective use of **combinational logic**, real-world hardware integration, and simulation. It fulfilled the goals of digital password authentication and served as an excellent practical application of logic gate theory.

---

## 📜 License

This project is open-source and available for educational and academic use under the **MIT License**.

---

## 📧 Contact

**Ghulam Qadir**  
📍 Rawalpindi, Pakistan  
📧 gqitspecialist@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ghulam-qadir-07a982365)

**Noor Malik**  
📍 Islamabad, Pakistan  
📧 noormalik56500@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/noormalik56500)

**Sara Tariq**  
**Khudema Haroon**  
**Muqeem Ahmed**

---
