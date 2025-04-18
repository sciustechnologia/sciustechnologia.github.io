---
layout: default
title: My Work experience
description: QA testing and technical writing
---

## my work experience as QA Engineer. 

> discussing the devices and software tested. 

*  AR/VR/MR,
*  Pixel 5G power performance [21-36]
*  Google Assistant [4-20]
*  Bluetooth (on Google Assistant, Infotainment system, IoT), and
*  ADB.

---

### Testing AR/VR/MR
- [Framework/application testing](./testing/xr_01.html)
- [Performance and stress testing](./testing/xr_02.html)
- [Test coverage and test process/methods](./testing/xr_03.html)
- [ADB](./testing/xr_adb.html)
- [Automation using Python](./testing/xr_04.html)

---

## Testing Power
> once my home lab is ready, I will give this a try as well.
  - [Battery chemistry](./power/batterychemistry.html)
  - [hardware](./power/hardware.html)
- [Power testing](./power/pwr.html)

---

## Testing Audio
- [Audio testing](./audio/audio.html)

### [Chip-level audio testing](./audio/chip-level_audio_testing.html)
- [I2S_SPI_I2C](./audio/buses_I2S_SPI_I2C.html)
- [SoX & install](./audio/audio_sox.html)
- [SoX & Cmds](./audio/audio_SoX_cmds.html)
- [TCL](./audio/audio_tcl.html)
- [venv](./audio/venv.html)

>  might be worth to create my own testing lab for this; I am still non-conclusive on this.

***

### Bluetooth [testing](./testing/bt.html)
- [Bluetooth testing profiles](./testing/bt_profiles.html)
- [BT test scenario: Classic Bluetooth - continuous data streaming](./testing/bt_scenario_ClassicBluetooth.html)
- [BT test scenario: BLE - Data exchange](./testing/bt_scenario_BLE.html)
- [BT test scenario: Bluetooth Mesh - for nodes and messaging](./testing/bt_scenario_mesh.html)
- [BT test scenario: Bluetooth 4.x](./testing/bt_scenario_Bluetooth4.html)
- [BT test scenario: Bluetooth audio](./testing/bt_scenario_audio.html)
- [Bluetooth testing tools](./testing/btt.html)
- [Bluetooth testing tools Sniffer](./testing/btt_sniffers.html)
- [Bluetooth testing tools Picolo](./testing/btt_picolo.html)
- [Bluetooth bugs](./testing/bt_protocolerrors.html)
- [Bluetooth logs](./testing/bt_logs.html)
  
***

In the works:
### Testing AI
* testing a generator - I will leave that for the end.

***

## ADB cmds [still updating]

- [basics](./testing/flashing.html)

***

## Data Analysis

- [my progress](./data/data.html)
- [EV](./data/ev.html)
- [Happy World - Data cleaning](./data/happy.html)
- [My car's gas consumption - Cleaning data](./data/bb.html)
- [Notes from  sqltutorial.org](./data/10_00.html)
- [Notes about numpy](./data/10_01.html)
- [Notes about pandas](./data/10_03.html)
- [Notes about Matplotlib](./data/10_02.html)

## Statistical Analysis
> using python, numpy, pandas, prettytable and Matplotlib.

- [Price and range of EVs in US and Germany](./databasix/ev.html)
- [Happiness of the world - Cleaning data](./databasix/happy.html)
- [My car's gas consumption - Cleaning data](./databasix/bb.html)
    
***

| Handbook                             | status                |
|:-------------------------------------|:----------------------|
| [Link to Selenium_Java page]     | Done |
| [Link to Selenium_Python page]   | Done |

> done mostly web-automation.
> I am familiar with Appium but didn't pursuit it. If Ai will take over will this be even of interest in the future?

* <a href="https://knowledgebase4testers.github.io/" target="_blank" rel="noopener noreferrer">My Glossary</a> 
* <a href="https://trumpfheller.github.io/" target="_blank" rel="noopener noreferrer">My QA Playbook</a> 

---

> my experience in testing and technical writing.

## Some of the devices I tested as a QA Engineer:

### 1 Google Assistant (e2e) testing


| Feature        | Regression | Triage | Comparison<br>(deepDives) | Dogfood |
|:-------------|:---------------------------------|:------|:--------------------------|:------|
| `Actions` (Date Questions)           | DONE                             | DONE  | DONE                      | DONE  |
| `My Day` (DaylyBrief)                | DONE                             | DONE  | DONE                      | DONE  |
| `Actions` (Device Questions)         | DONE                             | DONE  | DONE                      | DONE  |
| `Music` (Youtube, Spotify, Pandora)           | DONE                             | DONE  | DONE                      | DONE  |
| `News` (Sports, NPR)                 | DONE                             | DONE  | DONE                      | DONE  |
| `Remote Casting` (Youtube, Netflix) | DONE                             | DONE  | DONE                      | DONE  |
| `Actions` (Misc)                    | DONE                             | DONE  | DONE                      | DONE  |
| `Radio, Podcast` (Questions)        | DONE                             | DONE  | DONE                      | DONE  |
| `Productivity Actions` (Alarm, Timer, Reminder)        | DONE                             | DONE  | DONE                      | DONE  |
| `Answers` (Nutrition. Pronounce, Spelling, Web answers)  | DONE                             | DONE  | DONE                      | DONE  |
| `Personal Answers` (Calendar. Photos, Flights, and more) | DONE                             | DONE  | DONE                      | DONE  |

```
* Contributed massively to the Google Assistant triage playbook.
* Created the handbooks for 
  * onboarding, 
  * flashing Google Assistant, 
  * writing bug reports, 
  * and so on.
```

### 2 Google Assistant with wearables (verification testing)
  - Headphones,
  - Watches,
  - Loudspeakers, and more

### 3 Alexa  (verification testing)
  - Screens,
  - Monitors,
  - Loudspeakers,
  - Headphones,
  - Watches, and more

### 4 Google Embedded infotainment system
  - GM,
  - Ford,
  - Volvo,
  - and more

### 5 Fitbit
- [update in progress]

### 6 Pixel 5G power performance testing

| Feature        | 12V device| 8V device| Triage | 
|:-------------|:------------------|:------|:------|
| AirplaneRockbottom          | DONE | DONE  | DONE  |
| Bouncy Ball                 | DONE | DONE  | DONE  |
| Chrome Browsing Wifi        | DONE | DONE  | DONE  |
| Chrome Browsing scroll      | DONE | DONE  | DONE  |
| GFX                         | DONE | DONE  | DONE  |
| Keepress OOB                | DONE | DONE  | DONE  |
| LocalYoutube Music          | DONE | DONE  | DONE  |
| Partial Wakelock            | DONE | DONE  | DONE  |
| Photos (4K60FPSH265)        | DONE | DONE  | DONE  |
| Photos (AVI)                | DONE | DONE  | DONE  |
| Photos (MFC)                | DONE | DONE  | DONE  |
| Static Display              | DONE | DONE  | DONE  |
| Youtube Wifi                | DONE | DONE  | DONE  |
| Youtube stream              | DONE | DONE  | DONE  |

- Pixel-thermal (99 degC)
- Power Stats (mWs of Cellular, Modem, CPU, etc)
    - Core >> Wake Lock
    - System > Foreground or App Wakeups
    - Hardware
        - Brightness
        - GPS (Signal Quality)
        - Audio
    - Battery
        - Plugged
        - Charging
    - Connectivity [3GPP protocol 5G/4G]
        - Phone signal
        - Mobile Radio
        - Data connection
        - Conn Change
    - Wifi
        - Wifi scan
- Data connectivity
- Cellular network type
- Cellular Rx signal strength
- Wifi Rx signal strength
- Wifi app scan
- Kernel Wakeup reasons
- CPU Usage by App
- Mobile Radio Activity per app
- App Wakeup Alarms

---


