# 👋 Hi, I'm Joel Kevin Likane

🎓 Embedded Systems Graduate
💻 Embedded Software Engineer | C/C++ | ARM Cortex-M
🔧 Passionate about Bare-Metal Programming & Hardware-Software Interaction

---

## 🧠 About Me

I am an Embedded Systems graduate with hands-on experience in **automotive development environments**, gained through internships, a working student position, and my thesis in **charging infrastructure systems**.

My focus is on **bare-metal programming and low-level driver development**, where I build software directly on hardware using **register-level control**.

I am particularly interested in:

* Embedded software architecture
* Real-time systems
* Reliable and efficient driver design

I aim to contribute to the development of **robust, production-quality embedded systems** while continuously deepening my expertise.

---

## 🛠️ Technical Skills

### 🔹 Embedded Programming

* Embedded C (strong)
* C++ (basic)
* Bare-metal development (no HAL)
* Register-level programming

### 🔹 Microcontrollers

* STM32 (ARM Cortex-M4, STM32F4 series)
* Arduino (used for communication testing)

### 🔹 Communication Protocols

* UART / USART
* SPI / I2S
* I2C

### 🔹 Peripherals & Hardware

* GPIO
* Timers / SysTick
* DMA (basic exposure)

### 🔹 Tools & Debugging

* STM32CubeIDE
* ST-Link Debugging
* Logic Analyzer (protocol validation & signal timing)
* Git / GitHub

### 🔹 Core Concepts

* Hardware-Software Interaction
* Bitwise Operations
* Interrupt-driven programming
* Embedded driver development
* Peripheral configuration at register level

---

## 🚀 Featured Projects

### 🔹 STM32 Driver Stack (Bare-Metal)

Developed a complete **embedded driver stack from scratch** for STM32F407:

* GPIO
* I2C
* SPI
* USART

📌 Key Highlights:

* Fully **register-level implementation (no HAL)**
* Modular and reusable driver architecture
* Designed for scalability and clarity

🧪 Validation:

* Communication tested using **Arduino as external device**
* Signals verified using a **logic analyzer**
* Ensured protocol correctness and timing accuracy

🔗 Repository:
👉 [View Project](https://github.com/Jokeli93/stm32f407-baremetal-drivers)
---

### 🔹 Real-Time Clock with LCD Interface

Designed an embedded system displaying real-time date and time using:

* **DS1307 RTC (I2C)**
* **16x2 LCD (HD44780, 4-bit mode)**

📌 Features:

* Custom LCD driver (GPIO, timing-critical)
* RTC driver over I2C
* **SysTick interrupt-based periodic update**
* Clean layered architecture:

  * MCU Drivers → Device Drivers → Application

📌 Key Learnings:

* Hardware timing constraints (LCD interface)
* Interrupt safety and synchronization
* Debugging real hardware issues

🔗 Repository:
👉 [View Project](https://github.com/Jokeli93/RealTimeClock-on-LCD)
---

## 🎯 Current Learning Focus

* FreeRTOS (task scheduling, synchronization)
* Advanced interrupt handling
* DMA-driven communication
* Automotive communication protocols (CAN)

📌 Upcoming Projects:

* UART Command-Line Interface (CLI)
* CAN Bus Communication
* FreeRTOS-based applications
* Advanced Embedded driver libraries

---

## 📫 Contact

* 🔗 LinkedIn: https://www.linkedin.com/in/joel-kevin-likane-692006316
* 📧 Email: [likanejoel@yahoo.fr](mailto:likanejoel@yahoo.fr)

---

⭐ *I am actively seeking opportunities as a Junior Embedded Software Engineer and am eager to contribute to real-world embedded systems development.*
