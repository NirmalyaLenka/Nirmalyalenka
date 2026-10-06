<p align="center">
  <img src="./assets/header.gif" alt="Nirmalya Lenka — Embedded Systems, IoT, Robotics, Automation, Software" width="100%">
</p>

<h1 align="center">NIRMALYA LENKA</h1>

<p align="center">
  <b>Engineering Student</b><br>
  Embedded Systems &nbsp;|&nbsp; IoT &nbsp;|&nbsp; Robotics &nbsp;|&nbsp; Software
</p>

<p align="center">
  Engineering student building embedded systems, connected devices, robotics prototypes and practical software that interacts with the physical world.
</p>

<p align="center">
  Most of my projects start with a sensor and end with something a person can read or control: an OLED page, a web dashboard, a phone app link. In between sit ESP32 firmware, wireless links (ESP-NOW, BLE, Wi-Fi) and a lot of debugging.
</p>

```text
┌──────────────────────────────────────────────────┐
│ NIRMALYA@ENGINEERING-LAB                         │
├──────────────────────────────────────────────────┤
│ OS        : Linux / Windows                      │
│ MCU       : ESP32 / Arduino                      │
│ Wireless  : Wi-Fi / BLE / ESP-NOW                │
│ Sensors   : I2C / SPI / UART                     │
│ Robotics  : Motors / IR / ToF / Encoders         │
│ Backend   : Python / JavaScript                  │
│ Status    : BUILDING                             │
└──────────────────────────────────────────────────┘
```

---

## > WHAT I BUILD

<table>
<tr>
<td width="46%" align="center">
  <img src="./assets/embedded.gif" alt="Animated signal flow between sensors, an ESP32, motors, an OLED and a wireless link" width="100%">
</td>
<td>

**Sensor nodes and monitors**<br>
ESP32 boards reading voltage, current, temperature, light and motion, shown on OLEDs and web dashboards.

**Wireless links**<br>
ESP-NOW between boards, BLE to phones and browsers, Wi-Fi dashboards with JSON endpoints.

**Automation**<br>
Irrigation zones, alerts and thresholds that run on the device itself.

**Robotics**<br>
Competition-oriented builds, starting with a line-following robot.

</td>
</tr>
</table>

---

## FEATURED BUILDS

<table>
<tr>
<td align="center"><a href="https://github.com/NirmalyaLenka/AccidentGuard"><img src="./assets/cards/accidentguard.svg" width="400" alt="AccidentGuard project card"></a></td>
<td align="center"><a href="https://github.com/NirmalyaLenka/-SolarGuard-Pro-Wireless-Solar-Farm-Monitor"><img src="./assets/cards/solarguard.svg" width="400" alt="SolarGuard Pro project card"></a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/NirmalyaLenka/GreenHouse-IQ-Smart-Irrigation-System"><img src="./assets/cards/greenhouse.svg" width="400" alt="GreenHouse IQ project card"></a></td>
<td align="center"><a href="https://github.com/NirmalyaLenka/ESP32-OTA-Power-Monitor"><img src="./assets/cards/powermonitor.svg" width="400" alt="ESP32 Power Monitor project card"></a></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/NirmalyaLenka/air-conditioned-kesar-farming-usind-addaptive-ai"><img src="./assets/cards/kesar.svg" width="400" alt="Controlled Kesar Farming project card"></a></td>
<td align="center"><a href="https://github.com/NirmalyaLenka/LINE-FOLLOWING-ROBOT-FOR-BPUT-ROBO-COMP"><img src="./assets/cards/robot.svg" width="400" alt="Line Following Robot project card"></a></td>
</tr>
</table>

### BUILD PREVIEWS

<table>
<tr>
<td align="center"><a href="https://github.com/NirmalyaLenka/AccidentGuard"><img src="./assets/projects/accidentguard.gif" width="400" alt="AccidentGuard animated preview"></a><br><sub><b>AccidentGuard</b> · illustrative animation</sub></td>
<td align="center"><a href="https://github.com/NirmalyaLenka/-SolarGuard-Pro-Wireless-Solar-Farm-Monitor"><img src="./assets/projects/solarguard.gif" width="400" alt="SolarGuard Pro animated preview"></a><br><sub><b>SolarGuard Pro</b> · illustrative animation</sub></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/NirmalyaLenka/GreenHouse-IQ-Smart-Irrigation-System"><img src="./assets/projects/greenhouse.gif" width="400" alt="GreenHouse IQ animated preview"></a><br><sub><b>GreenHouse IQ</b> · illustrative animation</sub></td>
<td align="center"><a href="https://github.com/NirmalyaLenka/LINE-FOLLOWING-ROBOT-FOR-BPUT-ROBO-COMP"><img src="./assets/projects/robot.gif" width="400" alt="Line Following Robot animated preview"></a><br><sub><b>Line Following Robot</b> · illustrative animation</sub></td>
</tr>
</table>

<sub>The animations are drawn illustrations of each system's structure, not recordings of the hardware or live sensor data.</sub>

---

## SYSTEMS I WORK WITH

```text
   ┌─────────────────────────────────────────────┐
   │  SENSORS                                    │
   │  accelerometer · GPS · temperature · light  │
   │  current / voltage · soil moisture · ToF    │
   └──────────────────────┬──────────────────────┘
                          │
                          ▼
   ┌─────────────────────────────────────────────┐
   │  ESP32 / MCU                                │
   └──────────────────────┬──────────────────────┘
                          │
        ┌─────────┬───────┼───────┬─────────┐
        │         │       │       │         │
       I2C       UART    BLE    Wi-Fi    ESP-NOW
                          │
                          ▼
   ┌─────────────────────────────────────────────┐
   │  CONTROL / PROCESSING                       │
   │  ├── embedded firmware                      │
   │  ├── automation logic                       │
   │  ├── robotics                               │
   │  └── data processing                        │
   └──────────────────────┬──────────────────────┘
                          │
                          ▼
   ┌─────────────────────────────────────────────┐
   │  DASHBOARD / INTERFACE                      │
   │  OLED · web dashboard · PWA over BLE · JSON │
   └─────────────────────────────────────────────┘
```

---

## TECHNICAL STACK

<p align="center">
  <sub><b>HANDS-ON IN MY REPOSITORIES</b></sub><br>
  <img src="./assets/icons/c.svg" width="48" height="48" alt="C" title="C"> <img src="./assets/icons/cpp.svg" width="48" height="48" alt="C++" title="C++"> <img src="./assets/icons/javascript.svg" width="48" height="48" alt="JavaScript" title="JavaScript"> <img src="./assets/icons/esp32.svg" width="48" height="48" alt="ESP32 (Espressif)" title="ESP32 (Espressif)"> <img src="./assets/icons/arduino.svg" width="48" height="48" alt="Arduino" title="Arduino"> <img src="./assets/icons/bluetooth.svg" width="48" height="48" alt="Bluetooth LE" title="Bluetooth LE"> <img src="./assets/icons/git.svg" width="48" height="48" alt="Git" title="Git"> <img src="./assets/icons/github.svg" width="48" height="48" alt="GitHub" title="GitHub">
</p>

<p align="center">
  <sub><b>TOOLBOX AND LEARNING PATH</b></sub><br>
  <img src="./assets/icons/python.svg" width="48" height="48" alt="Python" title="Python"> <img src="./assets/icons/linux.svg" width="48" height="48" alt="Linux" title="Linux"> <img src="./assets/icons/raspberrypi.svg" width="48" height="48" alt="Raspberry Pi" title="Raspberry Pi"> <img src="./assets/icons/mqtt.svg" width="48" height="48" alt="MQTT" title="MQTT"> <img src="./assets/icons/react.svg" width="48" height="48" alt="React" title="React"> <img src="./assets/icons/nodejs.svg" width="48" height="48" alt="Node.js" title="Node.js"> <img src="./assets/icons/rust.svg" width="48" height="48" alt="Rust" title="Rust"> <img src="./assets/icons/go.svg" width="48" height="48" alt="Go" title="Go"> <img src="./assets/icons/mongodb.svg" width="48" height="48" alt="MongoDB" title="MongoDB"> <img src="./assets/icons/firebase.svg" width="48" height="48" alt="Firebase" title="Firebase"> <img src="./assets/icons/vscode.svg" width="48" height="48" alt="VS Code" title="VS Code">
</p>

| Area | What I use |
| :-- | :-- |
| **Embedded** | C, C++ (Arduino framework), ESP32, Arduino, PlatformIO |
| **Communication** | I2C, UART, BLE, Wi-Fi, ESP-NOW, HTTP + JSON |
| **Sensors** | ADXL345 accelerometer, NEO-6M GPS, INA226 and ACS712 current / voltage sensing, DHT22, DS18B20, BH1750, capacitive soil moisture, optical dust sensing, VL53L0X time-of-flight, rotary encoder |
| **Robotics** | Line following |
| **Software** | JavaScript, HTML, Web Bluetooth / PWA, Git |
| **Exploring** | Python, Raspberry Pi, MQTT, SPI, React, Node.js |

---

## MORE FROM THE LAB

[Smart Pressure Ulcer Prevention System](https://github.com/NirmalyaLenka/Smart-Pressure-Ulcer-Prevention-System) ·
[VL53L0X laser distance sensor tests](https://github.com/NirmalyaLenka/VL53L0X-working-and-test-code-leaser-based-distance-sensor-) ·
[ESP32 Wireless Lyrics Display](https://github.com/NirmalyaLenka/ESP32-Wireless-Lyrics-Display) ·
[RPM Meter with rotary encoder and OLED](https://github.com/NirmalyaLenka/RPM-Meter-ESP32-Rotary-Encoder-0.96-inch-OLED) ·
[Automatic Cat Food Dispenser](https://github.com/NirmalyaLenka/Automatic-Cat-Food-Dispenser) ·
[Smart AC Controller](https://github.com/NirmalyaLenka/Smart-AC-Controller---Human-Detection-Based-Automation) ·
[Smart Parking Assistant System](https://github.com/NirmalyaLenka/Smart-Parking-Assistant-System) ·
[Wireless Signal Scanner](https://github.com/NirmalyaLenka/Wireless-Signal-Scanner) ·
[PocketDeck](https://github.com/NirmalyaLenka/PocketDeck)

---

## REPOSITORY ACTIVITY

Everything I build lives on GitHub, and the list changes as projects move forward.

```text
Repositories  →  https://github.com/NirmalyaLenka?tab=repositories
Profile       →  https://github.com/NirmalyaLenka
```

---

## PROJECT TIMELINE

```text
   LEARNING
      │   circuits · C / C++ · Arduino
      ▼
   SENSOR EXPERIMENTS
      │   ToF · rotary encoder · OLED · I2C
      ▼
   ESP32 / IOT SYSTEMS
      │   Wi-Fi dashboards · BLE · ESP-NOW links
      ▼
   AUTOMATION
      │   irrigation · monitoring · alerts
      ▼
   ROBOTICS
      │   competition line follower
      ▼
   INTELLIGENT EMBEDDED SYSTEMS
          adaptive control · where the work is heading
```

---

<p align="center">
  <img src="./assets/footer.gif" alt="Build, test, debug, improve, repeat" width="100%">
</p>

<p align="center">
  <a href="https://github.com/NirmalyaLenka?tab=repositories"><b>BROWSE REPOSITORIES</b></a>
</p>

