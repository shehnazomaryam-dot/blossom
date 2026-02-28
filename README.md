
# 🌸 Blossom – IV Fluid Level Monitoring & Alert System

Blossom is a simple, cost-effective IV fluid level monitoring system designed for healthcare settings. It continuously monitors the fluid level in an intravenous (IV) bottle and alerts healthcare staff when the fluid level becomes critically low.

This helps prevent **blood backflow** into the IV tube, reduces risks to patients, and ensures timely replacement or shutdown of the IV system.

---

## 📌 Table of Contents

- Overview
- Problem Statement
- Proposed Solution
- System Features
- Components Used
- Block Diagram
- Working Principle
- Advantages
- Future Improvements
- License

---

## 🏥 Overview

Intravenous (IV) therapy is widely used in hospitals to deliver fluids and medications directly into a patient's bloodstream. Continuous monitoring of IV fluid levels is essential to avoid complications.

Blossom provides an automated alert system that:
- Detects low IV fluid levels
- Triggers a buzzer and/or LED indicator
- Helps medical staff respond quickly
- Prevents blood backflow due to empty IV bottles

The system is designed using **simple electronic components**, making it affordable and practical for small clinics and hospitals.

---

## ❗ Problem Statement

In many healthcare settings, IV fluid levels are monitored manually. This leads to several challenges:

1. **Human Error** – Nurses and healthcare workers manage multiple patients simultaneously. It is easy to miss a low IV bottle.
2. **Blood Backflow Risk** – If the IV bottle empties and is not stopped in time, blood may flow back into the IV tubing.
3. **Patient Safety Concerns** – Backflow can lead to contamination, infection risk, and additional medical intervention.
4. **Increased Workload** – Continuous manual checking increases workload for staff.
5. **Lack of Affordable Monitoring Systems** – Many automated systems are expensive and not accessible to smaller healthcare facilities.

### Our Objective

To design a **low-cost, reliable, and easy-to-install IV fluid monitoring system** that alerts staff before the IV bottle becomes completely empty.

---

## 💡 Proposed Solution

Blossom uses a simple sensing mechanism to detect the fluid level inside an IV bottle. When the fluid level drops below a predefined threshold:

- A **buzzer** sounds an alert.
- An **LED indicator** turns on.
- Staff are notified immediately.

The system ensures the IV is turned off or replaced before backflow occurs.

---

## ⚙️ System Features

- ✅ Low-cost and simple design  
- ✅ Real-time fluid level monitoring  
- ✅ Audio alert (Buzzer)  
- ✅ Visual alert (LED)  
- ✅ Easy to install and maintain  
- ✅ Low power consumption  
- ✅ Suitable for hospitals, clinics, and home care  

---

## 🔩 Components Used

The system is built using basic electronic components:

1. Microcontroller (e.g., Arduino / ATmega-based board)
2. Fluid level sensor (conductive / float / IR sensor)
3. Buzzer
4. LED indicator
5. Resistors
6. Transistors (if required)
7. Power supply (5V/9V battery or adapter)
8. Connecting wires
9. Breadboard or PCB
10. IV bottle setup (for testing/demo)

---

## 🧩 Block Diagram

```

```
       +-------------------+
       |   Power Supply    |
       +---------+---------+
                 |
                 v
       +-------------------+
       |   Level Sensor    |
       +---------+---------+
                 |
                 v
       +-------------------+
       |  Microcontroller  |
       +---------+---------+
                 |
      +----------+-----------+
      |                      |
      v                      v
```

+-------------+        +-------------+
|     LED     |        |    Buzzer   |
+-------------+        +-------------+

```

---

## 🔍 Working Principle

1. The **fluid level sensor** is placed at a predefined minimum level inside the IV bottle.
2. As long as fluid is above the sensor level, the system remains inactive.
3. When the fluid level drops below the threshold:
   - The sensor detects the change.
   - The microcontroller processes the signal.
   - The buzzer activates.
   - The LED indicator turns ON.
4. Medical staff respond by replacing or turning off the IV.
5. Once replaced, the system resets and resumes monitoring.

---

## 🎯 Advantages

- Prevents blood backflow
- Enhances patient safety
- Reduces staff workload
- Affordable and scalable
- Easy to implement
- Requires minimal maintenance

---

## 🚀 Future Improvements

- Wireless notification (Wi-Fi / GSM alerts)
- Integration with hospital monitoring systems
- Mobile app notification
- Battery backup with charging module
- Multiple IV monitoring with a single control unit
- Automatic IV flow cutoff mechanism

---

## 📜 License

MIT License

```

MIT License

Copyright (c) 2026 Blossom Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

---

## 🌸 Blossom – Ensuring Safe and Smart IV Monitoring

A simple idea. A safer healthcare environment.
```
