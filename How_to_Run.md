# ⏰ Real Time Clock (RTC) using 8051 Microcontroller

A hardware-based embedded systems project focused on implementing a **Real Time Clock (RTC)** using the **8051 Microcontroller** on a custom-designed PCB.
This project demonstrates real-time tracking and display of hours, minutes, and seconds using RTC interfacing with the 8051 microcontroller.

---

## 🚀 Project Overview

The objective of this project was to understand and implement:

* Real Time Clock Interfacing
* Time & Date Management using RTC Module
* 8051 Microcontroller Programming
* PCB Designing and Hardware Interfacing
* Embedded System Timing Applications
* Real-Time Display and Monitoring

The system was designed and tested on a custom PCB using the 8051 microcontroller and RTC module.

---

## 🛠️ Features

* Real-Time Clock Display
* Hours, Minutes, and Seconds Tracking
* RTC Module Interfacing with 8051
* Accurate Timekeeping using Crystal Oscillator
* PCB-Based Hardware Implementation
* Embedded C / Assembly Programming
* Expandable for Alarm and Calendar Functions

---

## 🧰 Technologies & Tools Used

* **Microcontroller:** 8051
* **RTC Module:** DS1307 / DS3231
* **Programming Language:** Embedded C / Assembly
* **Software Tools:** Keil µVision, Proteus
* **PCB Design:** EasyEDA / Custom PCB

---

## ⚡ Working Principle

1. The RTC module continuously maintains current time and date.
2. The 8051 microcontroller communicates with the RTC module.
3. Time data is read periodically from the RTC.
4. The current time is displayed on LCD / Seven Segment Display.
5. The system updates automatically in real time.

---

## 📷 Project Demonstration

* Custom PCB Implementation
* RTC Time Display
* Hardware Testing and Simulation
* Real-Time Clock Operation

*(Add your project images, PCB screenshots, circuit diagrams, and simulation results here)*

---

## 📂 Repository Contents

```bash id="2z8x8z"
├── Source Code
├── PCB Design Files
├── Circuit Diagram
├── Proteus Simulation
├── RTC Library Files
├── Documentation
└── Images
```

---

# ▶️ How to Run the RTC Project

## 🧩 Step 1: Open Keil µVision

1. Install and open **Keil µVision**
2. Click:

```text id="2azdzm"
Project → New µVision Project
```

3. Create a new project folder
4. Give the project a name

Example:

```text id="s71xzi"
RTC_8051_Project
```

---

## ⚙️ Step 2: Select the Microcontroller

1. Select your 8051 microcontroller

Example:

```text id="nrfbxv"
AT89C51
```

or

```text id="1z5ocm"
AT89S52
```

2. Click **OK**

---

## 📄 Step 3: Add the Source File

1. In the Project window:

   * Right-click on **Source Group 1**
   * Click:

```text id="5f1hdt"
Add New Item to Group 'Source Group 1'
```

2. Select:

   * C File (`.c`) OR Assembly File (`.asm`)

3. Give the file name

Example:

```text id="7zkqes"
rtc.asm
```

or

```text id="uh7sm8"
rtc.c
```

4. Paste the RTC code
5. Save the file

---

## 🔨 Step 4: Build the Project

Compile the project using:

```text id="6qpkew"
F7
```

or:

```text id="c4q4pr"
Project → Build Target
```

---

## 📦 Step 5: Generate HEX File

1. Go to:

```text id="jlwmxb"
Project → Options for Target
```

2. Open the **Output** tab
3. Enable:

```text id="jlwm9t"
☑ Create HEX File
```

4. Click **OK**
5. Rebuild the project again

---

## 📁 Step 6: Locate the HEX File

Inside the project folder:

```text id="n83m8p"
Objects → RTC_8051_Project.hex
```

---

## 🖥️ Step 7: Open the Proteus Simulation

1. Open the attached Proteus `.pdsprj` file from the repository
2. Double-click the 8051 microcontroller in the circuit

---

## 📂 Step 8: Load HEX File into Proteus

1. In the **Program File** section:

   * Click the 📁 folder icon
2. Select the generated HEX file

Example:

```text id="e7ksq0"
RTC_8051_Project.hex
```

3. Click **OK**

---

## ▶️ Step 9: Run the Simulation

Click the **Play ▶️** button in Proteus.

The RTC system will now start functioning and display the real-time clock.

---

## ⚠️ Important Notes

* Ensure proper RTC connections:

  * SDA
  * SCL
  * VCC
  * GND

* Crystal oscillator commonly used:

```text id="cr1d3u"
32.768 kHz
```

* For 8051:

```text id="9r6vgk"
11.0592 MHz Crystal
```

* Check LCD or Seven Segment connections properly

---

## ✅ Expected Output

* Accurate Real-Time Clock Display
* Continuous Time Updating
* Proper RTC Communication with 8051
* Successful Proteus Simulation and PCB-Level Operation

---

## 🎯 Learning Outcomes

* RTC Interfacing with Microcontrollers
* Embedded System Time Management
* PCB Designing Experience
* Simulation and Hardware Debugging
* Real-Time Embedded Applications

---

## 🔮 Future Improvements

* Alarm Clock Feature
* Calendar Integration
* Temperature Monitoring
* Battery Backup System
* IoT-Based Time Synchronization

---

## 👨‍💻 Author

Developed by **Swapnil Varma**
Electronics Engineering Student at The Maharaja Sayajirao University of Baroda

---

## ⭐ Support

If you found this project useful, consider giving this repository a ⭐ on GitHub!
