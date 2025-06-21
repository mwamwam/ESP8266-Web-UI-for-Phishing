# ESP8266 Captive Portal - Simulated Login Page (For Educational Use Only)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![ESP8266](https://img.shields.io/badge/Board-ESP8266-blue)
[![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)](https://github.com/mwamwam)
## Overview

This project demonstrates how an ESP8266 microcontroller can be used to create a WiFi access point with a captive portal that redirects connected users to a simulated login page. The login interface mimics that of a popular social media platform (e.g., Facebook) for the purpose of raising awareness about phishing attacks.

This is a **static simulation only** — it does not capture or store any data and should only be used in a controlled environment for learning or demonstration.

## Features

- Creates a standalone WiFi hotspot using ESP8266
- Redirects all connected devices to a fake login page
- HTML/CSS-based interface for mimicking login forms
- Ideal for educational demonstrations and awareness campaigns
- No internet required
- No actual credential capture (non-functional form)

## Purpose

The goal of this project is to:

- Educate users about the dangers of connecting to untrusted networks
- Demonstrate how phishing pages can be embedded into local networks
- Train students or learners in ethical hacking practices

## Requirements

- ESP8266 development board (e.g., NodeMCU, Wemos D1 Mini)
- Arduino IDE with ESP8266 board support installed
- USB cable for flashing the board
- Basic knowledge of Arduino and HTML/CSS

## Setup Instructions

1. Install the ESP8266 board definitions in the Arduino IDE.
2. Download or clone this repository to your local machine.
3. Open the `.ino` file in the Arduino IDE.
4. Connect your ESP8266 to your computer and select the appropriate port and board.
5. Upload the code to the board.
6. Once the upload is complete, the ESP8266 will broadcast a WiFi network (e.g., `FreeWiFi`).
7. Connect to the network using any WiFi-enabled device. The captive portal will automatically appear.

## Ethical Use Notice

This project is strictly for:

- Educational purposes
- Security awareness training
- Ethical hacking demonstrations in controlled environments
- Created by: Hanz

**Do not** use this project for unauthorized data collection or to deceive others. Any misuse may violate local laws or terms of service and may result in disciplinary, legal, or account action.

## Screenshots

![IMG_7433](https://user-images.githubusercontent.com/90843849/182632888-85cddc0d-72e5-4fdf-b7b9-577df79ae4fc.PNG)

