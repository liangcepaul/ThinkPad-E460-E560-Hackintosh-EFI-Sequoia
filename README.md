# Lenovo Thinkpad E460/E560 OpenCore 1.0.1 macOS Sequoia

This repo contains the files and scripts to install macOS on the Lenovo E460/E560 family.
 
## Hardware 💻

| Type           | Spec                                | Status|
|----------------|-------------------------------------|-------|
| Computer       | Lenovo ThinkPad E460                |   ✅  |
| BIOS Version   | LENOVO v1.40                        |   ✅  |
| CPU            | Intel i5 6200U 2300 MHz             |   ✅  |
| Display        | 14 inch 16:9, 1366 x 768. pixel.    |   ✅  |
| Ethernet       | Intel I219V Gigabit Ethernet        |   ✅  |
| Memory         | 8192 MB DDR3L-1600 MHz / PC3L-12800 |   ✅  |
| Graphics       | Intel HD Graphics 520               |   ✅  |
| Audio          | Conexant HD Audio CX20753/4         |   ✅  |
| Touchpad       | Elan Touchpad                       |   ✅  |
| USB Ports      | 3 x USB 3.0                         |   ✅  |
| Storage        | Crucial SSD 2TB                     |   ✅  |
| Wifi           | Intel AC 3165                       |   ✅  |
| HDMI Port      | Full HD 60hz                        |   ✅  |
| Card Reader    | 10/15 MB/s                          |   ✅  |

## Bios settings 💾

| Menu     |                   |                                 | Setting     |
|----------|-------------------|---------------------------------|-------------|
| Config   | USB               | UEFI BIOS Support               | `Enable `   |
|          | Power             | Intel SpeedStep Technology      | `Enable `   |
|          |                   | CPU Power Management            | `Enable `   |
|          | CPU               | Hyper-Threading Technology      | `Enable `   |
| Security | Security Chip     |                                 | `Disable `  |
|          | Memory Protection | Execution Prevention            | `Enable `   |
|          | Virtualization    | Intel Virtualization Technology | `Enable `   |
|          |                   | Intel VT-d Feature              | `Enable `   |
|          | Anti-Theft        | Computrace                      | `Disable `  |
|          | Secure Boot       |                                 | `Disable `  |
|          | Intel SGX         |                                 | `Disable `  |
|          | Device Guard      |                                 | `Disable `  |
| Startup  | UEFI/Legacy Boot  |                                 | `Both`      |
|          | CSM Support       |                                 | `Yes`       |
|          | Boot Mode         |                                 | `Quick`     |

## What's not working ⚠️

- [ ] Fingerprint Reader
- [ ] WI-FI with OpenCore Legacy Patcher 1.6
