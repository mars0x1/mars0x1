# Marcel Samer Malaeb

**Communication & Electronics Engineering (CCE) Student @ Beirut Arab University (BAU)**  
*Hardware & PCB Engineering • Embedded Systems • Firmware Security • RF Circuits*

```text

·············································································
:                                                                           :
:   /$$      /$$                                /$$$$$$              /$$    :
:  | $$$    /$$$                               /$$$_  $$           /$$$$    :
:  | $$$$  /$$$$  /$$$$$$   /$$$$$$   /$$$$$$$| $$$$\ $$ /$$   /$$|_  $$    :
:  | $$ $$/$$ $$ |____  $$ /$$__  $$ /$$_____/| $$ $$ $$|  $$ /$$/  | $$    :
:  | $$  $$$| $$  /$$$$$$$| $$  \__/|  $$$$$$ | $$\ $$$$ \  $$$$/   | $$    :
:  | $$\  $ | $$ /$$__  $$| $$       \____  $$| $$ \ $$$  >$$  $$   | $$    :
:  | $$ \/  | $$|  $$$$$$$| $$       /$$$$$$$/|  $$$$$$/ /$$/\  $$ /$$$$$$  :
:  |__/     |__/ \_______/|__/      |_______/  \______/ |__/  \__/|______/  :
:                                                                           :
·············································································

```

---

### 🔍 Focus & Practical Engineering
- **Hardware & PCB Design:** 4-layer mixed-signal board layouts, high-speed routing, ground-plane isolation, and analog front-end design in KiCad.
- **Embedded & RF Systems:** Microcontroller firmware (ESP32-S3, RP2040, STM32), discrete VHF oscillator design, and digital receiver integration.
- **Firmware Auditing & Vulnerability Research:** Static and dynamic reverse engineering of embedded MIPS/ARM binaries, network protocol analysis, and ethical disclosures.

---

### 🛠️ Featured Engineering Projects

#### ⚡ [mars0x1_LAB — 4-Layer Mixed-Signal Electronics Workstation](https://github.com/mars0x1/mars0x1_LAB)
*An all-in-one laboratory instrument powered by an ESP32-S3.*
- Engineered a **4-layer PCB** ($175.59\,\text{mm} \times 134.00\,\text{mm}$) featuring:
  - **4-channel analog oscilloscope** front-end with analog signal conditioning.
  - **AD9833 12.5 MHz DDS Function Generator** producing sine, triangle, and square waveforms.
  - **Dual high-speed PWM / pulse generator** with physical rotary encoder controls.
  - **100% linear split power supply** with 220 ground-stitching vias for low-noise analog performance.

#### 📡 [Colpitts FM Transmitter & VHF Communications Link](https://github.com/mars0x1/Colpitts-FM-Transmitter)
*Selected for presentation at Lebanese Electromagnetics Day @ BAU.*
- Built an 88–108 MHz VHF transmitter using a discrete 2N3904 BJT common-base oscillator at RF.
- Modulated the carrier directly via the transistor base, using internal junction capacitance ($C_{bc}$) variation to keep the circuit discrete and low-cost without external varactor diodes.
- Integrated an autotransformer coil tap and series capacitor to eliminate antenna hand-capacitance detuning, verified via live RDA5807 digital DSP receiver demodulation.

#### 🛡️ [Netis WF2409E — Unauthenticated Root Telnet Backdoor Advisory & PoC](https://github.com/mars0x1/Netis-WF2409E-Backdoor)
*Firmware vulnerability advisory and Python proof-of-concept (CAN-2026-2040024).*
- Reverse-engineered Realtek RTL8197F MIPS router firmware in Ghidra.
- Located an undocumented backdoor handler (`FUN_0040ea60`) in `/bin/boa` listening on magic endpoints to spawn root Telnet daemons without authentication.
- Authored a Python verification script demonstrating the root shell trigger (CWE-306, CWE-912).

#### 🥇 [SemSec National CTF — 1st Place Champion](https://github.com/mars0x1/SemSec-CTF-1st-Place)
*1st Place Winner ($15,000 Grand Prize) in a national cybersecurity competition.*
- Tackled binary reverse engineering, memory analysis, and exploitation challenges as part of the winning team.
- Documented write-ups and solvers for multi-stage binary checks, PRNG state reversing, and ELF section extraction.

---

### 🛠️ Technical Skills

| Category | Tools & Technologies |
| :--- | :--- |
| **Hardware & PCB** | KiCad (4-layer stackups, mixed-signal layout, SMT BOM), Oscilloscopes, Logic Analyzers, Soldering |
| **Microcontrollers & RF** | ESP32-S3, RP2040, Arduino, RDA5807 DSP, 2.4GHz RF, Discrete BJT RF Oscillators |
| **Security & Auditing** | Ghidra, GDB, Binwalk, Wireshark, Linux/Unix, Python (exploit tooling, automation), C/C++ |

---

### 📬 Contact
- **Email:** [malaeb501@gmail.com](mailto:malaeb501@gmail.com)
- **Academic:** Faculty of Engineering, Beirut Arab University (BAU), Lebanon
