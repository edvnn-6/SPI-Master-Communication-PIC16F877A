# SPI Master Communication – PIC16F877A

This project demonstrates **SPI Master mode** communication using the **PIC16F877A** microcontroller. The user can increment, decrement, and send an 8-bit data value over SPI using push buttons.

## 👨‍💻 Author
**Edvin Jose Vakaparamban**  
📅 Created on: [Your Date]

---

## 🔧 Overview

- SPI is configured in **Master mode**.
- **3 push buttons** control data operations:
  - **RB0 (UP):** Increments the data byte.
  - **RB1 (Down):** Decrements the data byte.
  - **RB2 (Send):** Sends data via SPI.
- Data is also displayed on **PORTD** for monitoring.

---

## 🧰 Hardware Requirements

- PIC16F877A Microcontroller
- Push buttons (x3) on RB0, RB1, RB2
- LEDs or logic analyzer on PORTD (optional)
- SPI-compatible Slave device (for testing)
- 16 MHz crystal oscillator, breadboard, and wiring

---

## ⚙️ Configuration

| Feature         | Setting        |
|----------------|----------------|
| SPI Mode       | Master, Fosc/64|
| Clock Polarity | CKP = 1        |
| Clock Phase    | CKE = 1        |
| SDO Pin        | RC5 (Output)   |
| SDI Pin        | RC4 (Input)    |
| SCK Pin        | RC3 (Output)   |
| Clock Freq     | 16 MHz         |

---


