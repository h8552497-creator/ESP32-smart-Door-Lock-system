# ESP32-smart-Door-Lock-system
Smart RFID Door Lock System using ESP32, RC522 RFID Reader, Servo Motor, and LEDs for secure access control and authentication.

# SDL5102 - Smart RFID Door Lock Using ESP32

## Overview

This project implements a Smart Door Lock System using an ESP32, RC522 RFID Reader, Servo Motor, and Status LEDs.

Authorized RFID cards can unlock the door, while unauthorized cards are denied access. The system provides visual feedback using LEDs and physical locking using a servo motor.

---

## Features

* RFID Authentication
* Servo-Based Door Lock
* Access Granted Indicator
* Access Denied Indicator
* Fast Card Detection
* Secure Access Control
* Beginner-Friendly Design

---

## Components Required

| Component         | Quantity  |
| ----------------- | --------- |
| ESP32 DevKit V1   | 1         |
| RC522 RFID Reader | 1         |
| Servo Motor SG90  | 1         |
| Green LED         | 1         |
| Red LED           | 1         |
| 220Ω Resistors    | 2         |
| Breadboard        | 1         |
| Jumper Wires      | As Needed |

---

## Circuit Connections

### RC522 → ESP32

SDA → GPIO 5

SCK → GPIO 18

MOSI → GPIO 23

MISO → GPIO 19

RST → GPIO 22

3.3V → 3.3V

GND → GND

### Servo

Signal → GPIO 13

VCC → 5V

GND → GND

### LEDs

Green LED → GPIO 25

Red LED → GPIO 26

---

## Libraries Required

Install the following libraries:

* MFRC522
* SPI
* ESP32Servo

---

## How It Works

1. ESP32 initializes the RC522 RFID reader.
2. RFID card is scanned.
3. UID is compared with authorized UIDs.
4. If UID matches:

   * Green LED turns ON.
   * Servo unlocks the door.
5. If UID does not match:

   * Red LED turns ON.
   * Access is denied.
6. System waits for the next card.

---

## Applications

* Smart Home Security
* RFID Attendance Systems
* Access Control Projects
* Office Security
* College Mini Projects
* IoT Security Systems

---

## Future Improvements

* OLED Display Support
* WiFi Notifications
* Mobile App Control
* Fingerprint Integration
* Cloud Logging
* Multiple User Profiles

---

## Author

Created by M

Subscribe for more ESP32, Arduino, Robotics, AI, Raspberry Pi, and Electronics Projects.
# SDL5102 - Smart RFID Door Lock Using ESP32

## Overview

This project implements a Smart Door Lock System using an ESP32, RC522 RFID Reader, Servo Motor, and Status LEDs.

Authorized RFID cards can unlock the door, while unauthorized cards are denied access. The system provides visual feedback using LEDs and physical locking using a servo motor.

---

## Features

* RFID Authentication
* Servo-Based Door Lock
* Access Granted Indicator
* Access Denied Indicator
* Fast Card Detection
* Secure Access Control
* Beginner-Friendly Design

---

## Components Required

| Component         | Quantity  |
| ----------------- | --------- |
| ESP32 DevKit V1   | 1         |
| RC522 RFID Reader | 1         |
| Servo Motor SG90  | 1         |
| Green LED         | 1         |
| Red LED           | 1         |
| 220Ω Resistors    | 2         |
| Breadboard        | 1         |
| Jumper Wires      | As Needed |

---

## Circuit Connections

### RC522 → ESP32

SDA → GPIO 5

SCK → GPIO 18

MOSI → GPIO 23

MISO → GPIO 19

RST → GPIO 22

3.3V → 3.3V

GND → GND

### Servo

Signal → GPIO 13

VCC → 5V

GND → GND

### LEDs

Green LED → GPIO 25

Red LED → GPIO 26

---

## Libraries Required

Install the following libraries:

* MFRC522
* SPI
* ESP32Servo

---

## How It Works

1. ESP32 initializes the RC522 RFID reader.
2. RFID card is scanned.
3. UID is compared with authorized UIDs.
4. If UID matches:

   * Green LED turns ON.
   * Servo unlocks the door.
5. If UID does not match:

   * Red LED turns ON.
   * Access is denied.
6. System waits for the next card.

---

## Applications

* Smart Home Security
* RFID Attendance Systems
* Access Control Projects
* Office Security
* College Mini Projects
* IoT Security Systems

---

## Future Improvements

* OLED Display Support
* WiFi Notifications
* Mobile App Control
* Fingerprint Integration
* Cloud Logging
* Multiple User Profiles

---

## Author

Created by M

Subscribe for more ESP32, Arduino, Robotics, AI, Raspberry Pi, and Electronics Projects.
# SDL5102 - Smart RFID Door Lock Using ESP32

## Overview

This project implements a Smart Door Lock System using an ESP32, RC522 RFID Reader, Servo Motor, and Status LEDs.

Authorized RFID cards can unlock the door, while unauthorized cards are denied access. The system provides visual feedback using LEDs and physical locking using a servo motor.

---

## Features

* RFID Authentication
* Servo-Based Door Lock
* Access Granted Indicator
* Access Denied Indicator
* Fast Card Detection
* Secure Access Control
* Beginner-Friendly Design

---

## Components Required

| Component         | Quantity  |
| ----------------- | --------- |
| ESP32 DevKit V1   | 1         |
| RC522 RFID Reader | 1         |
| Servo Motor SG90  | 1         |
| Green LED         | 1         |
| Red LED           | 1         |
| 220Ω Resistors    | 2         |
| Breadboard        | 1         |
| Jumper Wires      | As Needed |

---

## Circuit Connections

### RC522 → ESP32

SDA → GPIO 5

SCK → GPIO 18

MOSI → GPIO 23

MISO → GPIO 19

RST → GPIO 22

3.3V → 3.3V

GND → GND

### Servo

Signal → GPIO 13

VCC → 5V

GND → GND

### LEDs

Green LED → GPIO 25

Red LED → GPIO 26

---

## Libraries Required

Install the following libraries:

* MFRC522
* SPI
* ESP32Servo

---

## How It Works

1. ESP32 initializes the RC522 RFID reader.
2. RFID card is scanned.
3. UID is compared with authorized UIDs.
4. If UID matches:

   * Green LED turns ON.
   * Servo unlocks the door.
5. If UID does not match:

   * Red LED turns ON.
   * Access is denied.
6. System waits for the next card.

---

## Applications

* Smart Home Security
* RFID Attendance Systems
* Access Control Projects
* Office Security
* College Mini Projects
* IoT Security Systems

---

## Future Improvements

* OLED Display Support
* WiFi Notifications
* Mobile App Control
* Fingerprint Integration
* Cloud Logging
* Multiple User Profiles

---

## Author

Created by M

Subscribe for more ESP32, Arduino, Robotics, AI, Raspberry Pi, and Electronics Projects.
# SDL5102 - Smart RFID Door Lock Using ESP32

## Overview

This project implements a Smart Door Lock System using an ESP32, RC522 RFID Reader, Servo Motor, and Status LEDs.

Authorized RFID cards can unlock the door, while unauthorized cards are denied access. The system provides visual feedback using LEDs and physical locking using a servo motor.

---

## Features

* RFID Authentication
* Servo-Based Door Lock
* Access Granted Indicator
* Access Denied Indicator
* Fast Card Detection
* Secure Access Control
* Beginner-Friendly Design

---

## Components Required

| Component         | Quantity  |
| ----------------- | --------- |
| ESP32 DevKit V1   | 1         |
| RC522 RFID Reader | 1         |
| Servo Motor SG90  | 1         |
| Green LED         | 1         |
| Red LED           | 1         |
| 220Ω Resistors    | 2         |
| Breadboard        | 1         |
| Jumper Wires      | As Needed |

---

## Circuit Connections

### RC522 → ESP32

SDA → GPIO 5

SCK → GPIO 18

MOSI → GPIO 23

MISO → GPIO 19

RST → GPIO 22

3.3V → 3.3V

GND → GND

### Servo

Signal → GPIO 13

VCC → 5V

GND → GND

### LEDs

Green LED → GPIO 25

Red LED → GPIO 26

---

## Libraries Required

Install the following libraries:

* MFRC522
* SPI
* ESP32Servo

---

## How It Works

1. ESP32 initializes the RC522 RFID reader.
2. RFID card is scanned.
3. UID is compared with authorized UIDs.
4. If UID matches:

   * Green LED turns ON.
   * Servo unlocks the door.
5. If UID does not match:

   * Red LED turns ON.
   * Access is denied.
6. System waits for the next card.

---

## Applications

* Smart Home Security
* RFID Attendance Systems
* Access Control Projects
* Office Security
* College Mini Projects
* IoT Security Systems

---

## Future Improvements

* OLED Display Support
* WiFi Notifications
* Mobile App Control
* Fingerprint Integration
* Cloud Logging
* Multiple User Profiles

---

## Author

Created by M

Subscribe for more ESP32, Arduino, Robotics, AI, Raspberry Pi, and Electronics Projects.
