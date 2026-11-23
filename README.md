# Marcel  Malaeb

**Communication & Electronics Engineering (CCE) Student @ Beirut Arab University (BAU)**  
*Low-Level Systems • Binary Reverse Engineering • Firmware & Embedded Security • RF Engineering*

```text
  _  _  ____  ____  ___   __   _  _  __  
 ( \/ )(  _ \(  _ \/ __) /  \ ( \/ )/  \ 
 / \/ \ ) _ ( )   /\__ \(  O ) )  (  )(  
 \_)(_/(____/(__\_)(___/ \__/ (_/\_)(__)  [mars0x1]
```

---

### 🔍 Focus & Areas of Expertise
- **Binary Reverse Engineering & SMT Modeling:** Static/dynamic analysis of obfuscated binaries with Ghidra, GDB, angr, and constraint satisfaction with Z3.
- **Firmware Security & Vulnerability Research:** Architecture triage (MIPS, ARM, x86), memory corruption, reverse-engineering embedded web daemons, and developing proof-of-concept exploits.
- **RF & Hardware Systems:** VHF/UHF transmitter design (Colpitts oscillators, varactor modulation), SDR-based signal interception (RTL-SDR / GNU Radio), and KiCad PCB layout.

---

### 🏆 Featured Projects & Security Research

#### 🥇 [SemSec National CTF — 1st Place Champion](https://github.com/mars0x1/SemSec-CTF-1st-Place)
*First-place finish in a national cybersecurity competition ($15,000 grand prize).*
- Led reverse-engineering on high-value challenge binaries:
  - **Verdict (500 pts):** Defeated an MT19937 PRNG image-tile shuffling algorithm combined with diagonal matrix bitwise mutations; discovered and compensated for a 130×130 padding anomaly to restore a corrupted QR code.
  - **False Witness (500 pts):** Bypassed a 64MB bloatware binary and custom obfuscated virtual machine by parsing ELF headers, dumping the `.text` entry point, and reversing an early 24-byte XOR constraint check.
  - **Mixer:** Modeled forward and backward cumulative sum routines in Z3 SMT solver, preventing state explosion that crashed symbolic execution engines.

#### 🛡️ [Netis WF2409E — Unauthenticated Root Telnet Backdoor Advisory & PoC](https://github.com/mars0x1/Netis-WF2409E-Backdoor)
*Full-spectrum firmware vulnerability advisory and weaponized PoC (MITRE CAN-2026-2040024).*
- Reverse-engineered Realtek RTL8197F MIPS router firmware (`/bin/boa` web server).
- Documented unauthenticated backdoor handler (`FUN_0040ea60`) parsing hidden magic URI endpoints.
- Authored automated Python exploit script establishing root socket access via weaponized Telnet payload delivery (CWE-306, CWE-912).

#### 📡 [Colpitts FM Transmitter & VHF Communications Link](https://github.com/mars0x1/Colpitts-FM-Transmitter)
*Selected for presentation at Lebanese Electromagnetics Day @ BAU.*
- Engineered an 88–108 MHz FM transmitter using a discrete 2N3904 BJT tank circuit with varactor-based direct frequency modulation.
- Built a digital DSP reception and audio demodulation pipeline using RTL-SDR and GNU Radio.

---

### 🛠️ Technical Toolchain

| Category | Tools & Technologies |
| :--- | :--- |
| **Reverse Engineering** | Ghidra, GDB, IDA Pro, Radare2, Z3 SMT Solver, angr, Unicorn Engine |
| **Architectures** | x86 / x86-64, MIPS (32-bit Big/Little Endian), ARM, RISC-V |
| **Firmware & Embedded** | Binwalk, QEMU user/system emulation, Squashtool, UART/SPI dumping |
| **Hardware & RF** | KiCad (schematics & 2-layer PCBs), RTL-SDR, GNU Radio, Oscilloscopes |
| **Languages** | C, C++, Python, MIPS Assembly, x86-64 Assembly, Bash |

---

### 📬 Get in Touch
- **Email:** [malaeb501@gmail.com](mailto:malaeb501@gmail.com)
- **Academic:** Faculty of Engineering, Beirut Arab University (BAU), Lebanon
- Open to remote/international security engineering internships, vulnerability research, and compiler/tooling development.
