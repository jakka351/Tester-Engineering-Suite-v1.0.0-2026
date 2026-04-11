
<img width="1800" height="600" alt="tester_engineering_suite_logo" src="https://github.com/user-attachments/assets/d07f12f1-7f2f-44e4-acc3-cb61014444eb" />

OBD2 Datalogger, ISO14229 Diagnostics, PassThru Control

###

This repository has been created as a forum where users of Tester Engineering Suite, can raise issues and discuss with other users the use of the software. Feature requests and issues can be raised in the issues tab.
There is an initial readme for the first release of the software available here: https://testerpresent.com.au/TesterEngineeringSuite/   

For enquiries regarding licensing visit https://testerpresent.com.au or email contact@testerpresent.com.au  


###
<img width="1920" height="1044" alt="image" src="https://github.com/user-attachments/assets/4475c913-c766-465a-a562-cf8a9dda2697" />

# Tester Engineering Suite v1.0.2-2026

Developed by Tester Present Specialist Automotive Solutions

#### Professional Automotive Diagnostic & ECU Flash Programming Platform

Multi-Protocol | Multi-Manufacturer | J2534 PassThru Compatible

## 20+

Manufacturers

## 100+

ECU Variants

## 13

Protocols

## 40+

Security Algos

##### The Complete Diagnostic & Flash Programming Solution

Tester Engineering Suite is a professional-grade automotive diagnostic and ECU flash programming platform built for performance tuners, independent workshops, and automotive engineers. Covering 20+ vehicle manufacturers, 100+ ECU variants, and 13 communication protocols, it delivers everything you need in a single, unified application from live OBD2 data monitoring to full ECU reflashing with advanced security bypass capabilities.

Built on the industry-standard J2534 PassThru API, Tester Engineering Suite works with any compatible hardware adapter (Tactrix OpenPort, AVDI, Drew Technologies, and more), giving you hardware vendor independence and future-proof connectivity. Tester Engineering Suite also includes a remote reprogramming system that tunnels J2534 PassThru commands over WebSocket via a cloud relay server, enabling technicians to perform full ECU diagnostics and flash programming on vehicles at any location with an internet connection.

- • Single Platform — Replace multiple OEM tools with one unified application
- • Multi-Protocol — CAN, K-Line, UDS, KWP2000, VPW, SSM2, and more
- • J2534 Compatible — Works with any PassThru hardware adapter
- • Professional Flash — Full ECU read/write with checksum auto-correction


- • Security Bypass — 40+ security algorithms for seed/key authentication
- • Live Data — Real-time graphs, gauges, logging, and analysis
- • File Support — FRF, VBF, BIN, ODX, RWD, Intel HEX, and more
- • Remote Reprogramming — Cloud-relayed J2534 tunnel for off-site ECU flash and diagnostics


testerpresent.com.au | github.com/jakka351 | Tester Present Specialist Automotive Solutions | Australia

Copyright 2026 Benjamin Jack Leighton. All rights reserved.

TESTER ENGINEERING SUITE v1.0.2-2026 testerpresent.com.au

##### Core Features

|Live Data & Monitoring<br><br>• 100+ standard OBD2 PIDs with continuous polling<br>• 1000+ OEM PIDs across 8 manufacturer databases<br>• Custom PID definitions with formula editor<br>• Real-time multi-PID graphing with zoom/pan<br>• Professional analog gauge dashboard (RPM, speed, temps, etc.)<br>• Peak hold recording (min/max/avg/std-dev)<br>• Histogram distribution analysis<br>• Configurable polling rates (50-5000 ms)<br>• Data logging with auto-save and CSV export<br>• Variable-speed data playback (0.5x-4x) with timeline seek<br>|ECU Flash Programming<br><br>• Multi-manufacturer flash support (VW, Ford, BMW, Honda, etc.)<br>• 20+ flash platform implementations<br>• Pre-flash checksum verification and auto-correction<br>• Block-level or full-flash programming modes<br>• Calibration-only flashing for quick tune updates<br>• Post-flash verification and dependency checks<br>• Progress tracking with real-time transfer speed<br>• Battery voltage monitoring during flash<br>• RSA signature recalculation (BMW)<br>• Safe abort with status recovery guidance<br>|
|---|---|


|Diagnostic Trouble Codes<br><br>• OBD2 Stored, Pending, and Permanent DTCs<br>• UDS ReadDTCInformation with full status masks<br>• KWP2000 legacy DTC support<br>• Freeze frame snapshot data<br>• DTC severity categorization and colour coding<br>• Ford DTC database (2+ million entries)<br>• Fault detection counter (FDC) history<br>• Clear DTCs with confirmation<br>|Security & Authentication<br><br>• SA2 bytecode interpreter (VW/Audi/Skoda/SEAT)<br>• GGDS seed/key algorithm (Ford)<br>• PcmHammer integration (GM)<br>• LFSR key generation (Mazda)<br>• VKeyGen DLL integration (Daimler/Mercedes)<br>• PIN brute-force (PSA Group)<br>• JLR pre-calculated key tables<br>• UnlockECU Library — 40+ additional algorithms<br>• Honda pre-calculated keys (1000+ keys)<br>• Subaru Denso encryption (300+ keys)<br>• Ford CAN Generic KeyGenMkI (300+ module keys)<br>• Hyundai SMARTRA PIN calculator<br>• Saab XOR ByteCoder + CRC<br>• Volvo LFSR security (24/64-bit)<br>• EdDSA elliptic curve (experimental)<br>|
|---|---|


|CAN Bus Analysis<br><br>• Real-time CAN sniffer (dump + unique ID modes)<br>• Frame filtering (include/exclude by CAN ID)<br>• Custom CAN frame transmission<br>• Standard (11-bit) and extended (29-bit) support<br>• Dual-channel operation (CAN + K-Line simultaneously)<br>• Frame statistics and FPS monitoring<br>• Raw PassThru multi-protocol access<br>|Emissions & Readiness<br><br>• Complete readiness flag monitoring<br>• Drive cycle completion verification<br>• Mode 05 & 06 detailed test results<br>• Monitor-by-MID diagnostics<br>• Mode 08 on-board test execution<br>• MIL (check engine light) status display<br>|
|---|---|


|Data Logging & Analysis<br><br>• CSV export with metadata headers and millisecond timestamps<br>• Auto-save at configurable intervals (1-120 minutes)<br>• 50MB file rotation with optional GZip compression<br>• Full log playback with play/pause/stop and timeline seek<br>• Variable playback speed (0.5x, 1x, 2x, 4x)<br>• Histogram analysis with statistical summary<br>|Remote Reprogramming<br><br>• Cloud-hosted WebSocket relay server (Azure) with session pairing<br>• Transparent J2534 PassThru tunneling over JSON-RPC 2.0<br>• Slave agent on-site with local J2534 device and vehicle access<br>• Master console for remote technician control and monitoring<br>• Chunked file transfer (65KB) with SHA256 hash verification<br>• Real-time flash progress, ECU identification, and DTC access<br>|
|---|---|


###### Tester Present Specialist Automotive Solutions | ABN Registered | Australia Page 2

TESTER ENGINEERING SUITE v1.0.2-2026 testerpresent.com.au

### Remote Diagnostic & Programming

###### Technology

Tester Engineering Suite's proprietary remote reprogramming system is an industry-first solution that tunnels the complete J2534 PassThru API over the internet via a secure cloud relay. This enables automotive technicians to perform full ECU diagnostics, flash programming, and fault code management on vehicles at any location worldwide — as if they were physically connected to the vehicle's OBD2 port.

###### Three-Tier Cloud Architecture

###### Master Console

WebSocket / WSS

Technician Workstation Remote Location

JSON-RPC 2.0

###### Cloud Relay Server

###### Slave Agent

WebSocket / WSS

Azure WebSocket Relay JSON-RPC 2.0 Router

On-Site J2534 Device Connected to Vehicle

JSON-RPC 2.0

###### Secure Session Pairing

Cryptographically random 6-character session codes (32-char alphabet, excludes ambiguous I/1/O/0)

Time-limited codes: 10-minute expiry, extended to 60 minutes upon successful pairing

HMAC-SHA256 response signing prevents man-in-the-middle attacks

Automatic stale client detection and disconnection (5-min inactivity timeout)

30-second heartbeat keep-alive mechanism

WSS/HTTPS transport-layer encryption

###### Full J2534 PassThru Tunneling

Complete J2534 API tunneled transparently over JSON-RPC 2.0 protocol

Remote device enumeration and connection (PassThru DLLs + ELM327 serial adapters)

All 13 protocols supported remotely: CAN, UDS, KWP2000, K-Line, VPW, SSM2, and more

Raw CAN frame send/receive with configurable filtering Dual-channel operation (CAN + K-Line simultaneously) Battery voltage monitoring via remote ReadVoltage()

ELM327 shim layer for non-native J2534 hardware

###### Remote Flash Programming

###### Complete Remote Diagnostics

Chunked firmware transfer (65KB blocks) with dual-layer hash verification

Full OBD2 Modes 01-0A: live data, freeze frames, DTCs, readiness, vehicle info

Per-chunk SHA256 validation + full-file integrity check on reassembly

UDS services: Session Control, Security Access, Read/Write DID, Memory R/W, Routine Control

12-step standardised UDS flash sequence with vendor-specific extensions

Network topology scanning — automated ECU discovery across CAN/K-Line buses

Flash routines: Ford VBF, VW Simos18, Subaru Denso, Honda, Daimler, Volvo

Remote DTC read/clear across all discovered ECUs

KWP1281 legacy protocol support for VW instrument clusters

Real-time progress notifications (state, percentage, bytes written)

ECU identification: VIN, hardware/software part numbers, calibration IDs

Remote security access — seed/key exchange tunneled through relay

Safe abort with 600-second global timeout protection

###### No VPN. No port forwarding. No direct IP connection required. The cloud relay server handles all session routing — both master and slave connect outbound, making the system firewall-friendly and deployable anywhere with an internet connection.

Tester Present Specialist Automotive Solutions | ABN Registered | Australia

##### Supported Manufacturers & ECU Types

|Manufacturer|ECU Types|Capabilities|
|---|---|---|
|Volkswagen Group (VW/Audi/Skoda/SEAT)|Simos 8, 10, 12, 12.2, 16, 18, 18.10, 18.41 DQ250 MQB, DQ381, Haldex 4Motion|FRF, BIN, ODX Full unlock + re-lock|
|Ford|EEC-VI (Spanish Oak PCM) 16 diagnostic modules (SM01-SM16) Focus, Fiesta, Mondeo, Transit, Ranger, Explorer, F-150|VBF format SBL bootloader 300+ module keys|
|BMW|MS41, MS42, MS43, MS45, MSS70, MSV70 BMS46 (ABS/Stability)|BIN format Dual-memory architecture RSA signature recalculation|
|Honda|Multiple ECU types CAN-based architecture|RWD + BIN formats Multi-mode unlock 1000+ pre-calculated keys|
|Nissan|CAN-based ECUs (SH7055/7058/7059) 350Z, GT-R, Altima, Pathfinder, Navara|BIN format Fast-hash algorithm Multiple flash sizes|
|Subaru|Denso (CAN + K-Line) Hitachi (multiple gens), M32R|BIN w/ encryption SSM2 diagnostics 300+ encryption keys|
|General Motors|PCM (Powertrain) IPC (Instrument Panel)|VPW protocol PcmHammer|
|Bosch ME7|ME7.1/ME7.5/ME7.9+ engine ECU|K-Line programming BIN format Proprietary security|
|Daimler (Mercedes)|Multi-block ECUs C/E/S-Class, GLA, GLC|VKeyGen DLL security BIN format 100+ security DLLs|
|ZF Transmissions|6HP26 (6-speed auto TCM)|Adaptation read/reset CAL + BIN Fuzzy CalID match|
|Volvo|P1, P2, P3/SPA & P80 platforms SBL bootloader|VBF + Intel HEX D2 proprietary CAN protocol LFSR security|
|Hyundai / Kia|SIM2K (Infineon) EEPROM programming|BIN format Full flash support SMARTRA PIN calculator|
|Mazda|Multiple variants RX-8 (SE3P) Denso SH7055|BIN format LFSR key generation|
|PSA (Peugeot/Citroen)|VD46, VD56, CMM, SIM82 Engine + gearbox|PIN-based security Brute-force support|
|JLR (Jaguar/Land Rover)|311 ECU module groups Multi-module ECUs|368 security constants Multi-level security Pre-calculated keys|
|Saab|Trionic T5.2/T5.5/T7/T8 Multiple generations|BIN format Checksum correction XOR ByteCoder encryption|
|Aston Martin|V8/V12 ECUs (via Ford EEC-VI platform)|VBF format Shared Ford platform security|


###### Tester Present Specialist Automotive Solutions | ABN Registered | Australia Page 3

##### Communication Protocols

|Protocol|Description & Capabilities|
|---|---|
|CAN Bus (ISO 15765)|11-bit & 29-bit addressing, multi-frame transport, raw sniffer, configurable TX/RX IDs|
|UDS (ISO 14229-1)|Full service support: Session Control, Security Access, Read/Write DID, Memory R/W, Flash Download/Upload, Routine Control, DTC Management, IO Control|
|KWP2000 (ISO 14230)|Standard/Programming/Extended sessions, seed/key auth, legacy K-Line diagnostic support|
|OBD2 (ISO 15031)|Modes 01-0A: Live data, freeze frames, DTCs, readiness, vehicle info, permanent DTCs|
|OBD-on-UDS|Seamless OBD2 data via UDS services (0x22 ReadDID, 0x19 ReadDTC)|
|K-Line (ISO 9141-2)|Physical layer for KWP2000/KWP1281, 5-baud init, fast init|
|KWP1281|VW legacy K-Line protocol for instrument cluster EEPROM programming|
|Ford-9141|Ford proprietary K-Line (ES-F7LC-12K529-FD), 10,400 baud, multi-module|
|VPW (J1850)|GM Variable Pulse-Width K-Line protocol, PcmHammer integration|
|J1850 PWM|Ford Pulse-Width Modulated protocol, 41.6 kbps|
|SSM2 (Subaru)|Subaru Select Monitor 2: parameter/switch/DTC reading, K-Line & 32-bit CAN|
|McMESS (Bosch)|9-bit K-Line calibration protocol, 10.4k/125k baud, RAM access, variable tuning|
|Volvo D2|Volvo proprietary CAN diagnostic protocol for P1/P2/P3/SPA platforms|
|J2534 PassThru API|Multi-protocol hardware abstraction: filter management, raw I/O, voltage control, timing config|
|Remote Reprogramming|J2534 PassThru tunneling via cloud WebSocket relay (JSON-RPC 2.0), session-paired master/slave architecture for off-site ECU flash programming and diagnostics|


Supported File Formats

|Format|Type|Manufacturers|Read|Write|
|---|---|---|---|---|
|BIN|Raw binary ECU dump|Honda, Nissan, Subaru, GM, BMW, ZF, ME7, etc.|Yes|Yes|
|FRF|VW encrypted firmware|VW/Continental (Simos series)|Yes|Yes|
|VBF|Ford/Volvo firmware blocks|Ford, Volvo, Aston Martin|Yes|Yes|
|RWD|Honda-specific firmware|Honda|Yes|Yes|
|ODX|Open Diagnostic Data Exchange|VW (export)|Yes|Yes|


|Format|Type|Manufacturers|Read|Write|
|---|---|---|---|---|
|CAL|Calibration data (128KB)|ZF 6HP26|Yes|Yes|
|Intel HEX|Bootloader format|Volvo P1 SBL|Yes|-|
|CSV|Data export|All (logging/export)|-|Yes|


###### Tester Present Specialist Automotive Solutions | ABN Registered | Australia Page 4

##### Advanced: VW/Simos ECU Unlock & FRF Tools

Tester Engineering Suite includes a complete implementation of the Simos write-without-erase exploit for unlocking VW/Continental engine ECUs. This enables flashing of custom (unsigned) firmware to ECUs that normally require RSA-signed binaries.

|Feature|Description|
|---|---|
|CBOOT Patching|Patches the CBOOT bootloader's is_sample_mode() function to bypass RSA signature verification. Two TriCore assembly occurrences are automatically located and patched to NOPs.|
|Write-Without-Erase|Exploits a flash controller vulnerability: erasing the CAL sector allows writing to ASW blocks without erasing them first. Uses 8-byte ECC-correct writes in patch areas and 256-byte assembly page fills.|
|FRF Decryption|Full FRF container decryption using recursive XOR cipher with 4KB key material. Extracts the embedded ZIP containing ODX/SGO XML files with hex-encoded flash data.|
|FRF Export|Export decrypted FRF data to ODX (XML) or full BIN file format for analysis, modification, or archival.|
|Custom AES Key/IV|Override the default AES-128-CBC encryption keys with custom values for research and development purposes.|
|DSG Cipher Support|Progressive substitution cipher for DQ250 MQB gearbox ECUs, with automatic key table detection.|
|Simos XOR Cipher|Trivial incrementing XOR cipher used by legacy Simos 8 and Simos 10 ECUs.|
|Multi-Mode Flash|Standard Flash, CAL Only, Unlock ECU, Full Flash (Unlocked), and Re-Lock (Stock) modes available from a single interface.|


###### Additional Advanced Features

|• DID Bruteforcer — Automated data identifier discovery with configurable range and delay<br>• Memory Read/Write — Direct RAM/ROM access with configurable address/size lengths<br>• Routine Control — Execute ECU routines with custom parameters and result logging<br>• IO Control — Actuator control by DID (relay activation, voltage control)<br>• OEM PID Databases — 8 manufacturer databases (Ford, GM, Honda, Nissan, Mazda, Subaru, PSA, Daimler)<br>• Dark Mode UI — Full dark theme support<br>|• CAN Bus Sniffer — Dual-mode traffic analysis with filtering and statistics<br>• McMESS Protocol — Bosch K-Line calibration with 9-bit parity and high-speed mode<br>• ZF Adaptation — Read/reset transmission adaptation values with fuzzy CalID matching<br>• K-Line Cluster — KWP1281 instrument cluster EEPROM programming with WSC security<br>• Ford DTC Database — 2+ million manufacturer-specific DTC entries<br>• Remote Reprogramming — Cloud-relayed J2534 tunnel with master/slave session pairing<br>|
|---|---|


- Tester Present Specialist Automotive Solutions | ABN Registered | Australia Page 5


##### System Requirements

|Component|Minimum|Recommended|
|---|---|---|
|Operating System|Windows 7|Windows 10/11|
|Runtime|.NET Framework 4.8.1|.NET Framework 4.8.1|
|RAM|512 MB|2 GB+|
|Disk Space|50 MB + log storage|200 MB+ (with logs)|
|Hardware Interface|Any J2534 PassThru device|Tactrix OpenPort 2.0 / AVDI|
|Connection|USB (J2534 adapter)|USB 2.0+ / Internet (remote reprog)|
|Display|1100x750|1920x1080+ (for dashboard)|


Why Choose Tester Engineering Suite?

|One Tool, Every Vehicle<br><br>Stop juggling multiple OEM diagnostic tools. Tester Engineering Suite covers 20+ manufacturers, 100+ ECU variants, and 40+ security algorithms in a single application, from European luxury brands to Japanese performance vehicles.|Hardware Freedom<br><br>Built on the J2534 PassThru standard, Tester Engineering Suite works with any compatible adapter. No proprietary hardware lock-in — choose the interface that fits your budget and workflow.|
|---|---|


|Professional Flash Programming<br><br>Full ECU read, write, and unlock capabilities with automatic checksum correction, block-level verification, and comprehensive safety warnings. Supports calibration-only updates for quick tune changes.|Deep Protocol Coverage<br><br>From modern CAN/UDS to legacy K-Line/KWP2000, Tester Engineering Suite speaks every language your vehicles do. Raw bus access, protocol analysis, and custom PID definitions give you complete control.|
|---|---|


|Remote Reprogramming<br><br>A cloud-hosted WebSocket relay pairs a slave agent (on-site with the vehicle and J2534 device) to a master console (technician workstation) anywhere in the world. Full J2534 PassThru commands are tunneled transparently, enabling ECU flashing, diagnostics, and DTC management on vehicles you can’t physically reach.|Built by Engineers, for Engineers<br><br>Developed by automotive engineers with real workshop experience. Every feature is designed for practical use in diagnostic and tuning workflows — no bloat, no unnecessary complexity.|
|---|---|


###### Ready to Transform Your Workshop?

###### Visit testerpresent.com.au for licensing, documentation, and support GitHub: github.com/jakka351 | Developer: Benjamin Jack Leighton

Copyright 2026 Benjamin Jack Leighton, Tester Present Specialist Automotive Solutions. All rights reserved. VW_Flash protocols ported under GPL-3.0 license from bri3d. All manufacturer names and trademarks are property of their respective owners.

###### Tester Present Specialist Automotive Solutions | ABN Registered | Australia Page 6




<img width="1920" height="1042" alt="signal-2026-03-08-10-04-14-809" src="https://github.com/user-attachments/assets/d489036e-a5b2-4b7d-b171-275cd1dcdfcc" />

<img width="2017" height="1041" alt="image" src="https://github.com/user-attachments/assets/e64abaa6-b730-4115-bd71-cb21660a7b1b" />


<img width="1919" height="1039" alt="signal-2026-03-08-10-05-12-704" src="https://github.com/user-attachments/assets/6f1e280c-9d75-499b-bed5-398e280132a8" />
<img width="1920" height="1042" alt="signal-2026-03-08-10-05-00-553" src="https://github.com/user-attachments/assets/05789260-15e0-4a9b-81aa-27b33e713733" />
<img width="1919" height="1037" alt="signal-2026-03-08-10-04-50-894" src="https://github.com/user-attachments/assets/6367c1a0-b7db-482e-aaf1-e160559a26cf" />
<img width="1920" height="1042" alt="signal-2026-03-08-10-04-41-111" src="https://github.com/user-attachments/assets/01fde62f-d51f-4bcd-b4a9-68f608fbe6fd" />

![splash_video](https://github.com/user-attachments/assets/0d4fc122-97e5-4928-b052-9911a496f61d)
