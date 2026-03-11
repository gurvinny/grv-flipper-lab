<div align="center">

  <h2>🧪 Project Index — Flipper Lab</h2>

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Active-1F2937?style=flat-square&logoColor=60A5FA" alt="Status" />
    <img src="https://img.shields.io/badge/Device-Flipper%20Zero-1F2937?style=flat-square&logo=flipperdevices&logoColor=60A5FA" alt="Device" />
    <img src="https://img.shields.io/badge/Documentation-Index-1F2937?style=flat-square&logoColor=60A5FA" alt="Docs" />
  </p>
</div>

---

This document serves as the **📋 Master Index** for all Flipper Zero research and engineering projects contained within this lab ecosystem.

Each project repository follows a standardized structure and documentation format to ensure clarity, reproducibility, and professional engineering practices tailored for **Cybersecurity & Penetration Testing**.

---

## 📡 Active Projects

| Project | Focus Area | Description | Repository |
|----------|-------------|--------------|-------------|
| **IR Automation System** | ![Infrared (IR)](https://img.shields.io/badge/Infrared_(IR)-1F2937?style=flat-square&logoColor=60A5FA) | Reverse engineering IR protocols and building room automation workflows | [flipper-ir-automation](https://github.com/gurvinny/flipper-ir-automation) |

---

## 🛠 Planned Cybersecurity & Pen-Testing Projects

*(Projects below will be added as research continues.)*

### ⌨️ USB HID Automation (BadUSB)
![Payloads](https://img.shields.io/badge/Payloads-1F2937?style=flat-square&logoColor=60A5FA) ![Keystroke Injection](https://img.shields.io/badge/Keystroke_Injection-1F2937?style=flat-square&logoColor=60A5FA)

**Focus:** Deploying specialized keystroke injection scripts for automated execution across various operating systems (Windows, macOS, Linux).
**Proposed Experiments:**
- **Reconnaissance Payloads:** Automate rapid system enumeration, network topology mapping, and configuration extraction.
- **Privilege Escalation & Persistence:** Explore methods to execute local privilege escalation (LPE) techniques and establish persistence mechanisms (e.g., reverse shells, scheduled tasks) using Rubber Ducky script syntax.
- **Defense & Mitigation:** Analyze how EDR (Endpoint Detection and Response) and antivirus solutions respond to HID attacks, and develop mitigation strategies (e.g., USB port blocking, execution policy enforcement).

### 📻 Sub-GHz RF Signals
![Sub--GHz RF](https://img.shields.io/badge/Sub--GHz_RF-1F2937?style=flat-square&logoColor=60A5FA) ![Protocol Analysis](https://img.shields.io/badge/Protocol_Analysis-1F2937?style=flat-square&logoColor=60A5FA)

**Focus:** Capturing, decoding, and analyzing radio frequency transmissions on physical access systems (e.g., gates, garage doors, IoT devices).
**Proposed Experiments:**
- **Static vs. Rolling Codes:** Investigate the security differences between static codes (which are vulnerable to simple capture-and-replay) and dynamic rolling codes (e.g., KeeLoq).
- **Signal Replay Attacks:** Audit legacy physical access controls by demonstrating replay attack vulnerabilities and highlighting the need for modernized security protocols.
- **Custom Protocol Parsing:** Develop parsers or leverage existing tools (like URH - Universal Radio Hacker) to visualize and manipulate sub-GHz waveforms.

### 💳 RFID / NFC Analysis
![RFID / NFC](https://img.shields.io/badge/RFID_/_NFC-1F2937?style=flat-square&logoColor=60A5FA) ![Access Control](https://img.shields.io/badge/Access_Control-1F2937?style=flat-square&logoColor=60A5FA)

**Focus:** Reading, emulating, and cloning low-frequency (125 kHz) and high-frequency (13.56 MHz) physical access cards and tags.
**Proposed Experiments:**
- **Access Control Auditing:** Clone standard access badges (e.g., HID Prox, MIFARE Classic) to test building perimeter security controls.
- **Emulation vs. Cloning:** Evaluate the differences between emulating a badge directly from the Flipper Zero versus writing the captured data to a blank physical tag.
- **Vulnerability Assessment:** Identify misconfigurations in physical security systems, such as relying on unencrypted UID checks instead of secure sector authentication.

### 📶 Wi-Fi Auditing
![Wireless Sec](https://img.shields.io/badge/Wireless_Sec-1F2937?style=flat-square&logoColor=60A5FA) ![Network Auditing](https://img.shields.io/badge/Network_Auditing-1F2937?style=flat-square&logoColor=60A5FA)

**Focus:** Utilizing compatible devboards (e.g., ESP8266, ESP32) attached to the Flipper Zero to analyze and audit wireless network defenses.
**Proposed Experiments:**
- **Deauthentication Attacks:** Simulate deauth attacks (802.11w management frame vulnerability) to force client disconnections and capture subsequent WPA/WPA2 handshakes.
- **Handshake Analysis:** Extract captured PMKID or 4-way handshakes and attempt offline dictionary or brute-force attacks to evaluate password strength.
- **Rogue AP & Evil Twin:** Deploy localized rogue access points to observe client probe requests and demonstrate the risks of connecting to untrusted networks.

---

## ⚠️ Ethics & Authorization

All projects, experiments, and tooling documented in this repository are subject to strict ethical boundaries.

👉 **[Read the Full Security Policy (SECURITY.md)](SECURITY.md)**

<div align="center">
  <i>This repository is intended strictly for educational, research, and engineering demonstration purposes.</i>
</div>
