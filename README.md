
# Android ADB Hacking Toolkit

**_The ultimate weapon for Android device command and control_**

by Akhila Thomas

## Overview

This powerful Python-based ADB toolkit is designed for hackers, pentesters, security researchers, and curious minds aiming to **take full control of Android devices effortlessly**. Whether wired or wireless, this tool grants you command-line mastery over connected Android devices via ADB.

**Note:** Requires physical access or network-level access with debugging enabled on the target Android device. Handle with care and only on devices you own or have permission to test!

## Features

- **Wirelessly hijack** Android devices on the same network using ADB TCP connection
- Full device control including **screen mirroring** (scrcpy integration)
- Extract sensitive info: battery stats, running activities, system properties
- Perform stealthy file transfers (upload/download)
- Toggle WiFi to cripple or enable network access remotely
- Execute arbitrary shell commands on the device
- Type remotely or send key events to manipulate the device
- Open URLs silently on target devices
- Easily add custom attack modules and commands
- Sleek ANSI-colored ASCII banner for ultimate hacker swag


## Requirements

- Python 3.x installed on attack machine
- ADB binary installed and accessible from your PATH
- `scrcpy` installed for screen control (optional but recommended)
- Target device with Developer Options enabled and USB debugging turned on
- Physical USB connection or wireless access via TCP ADB (same LAN)


## Warning

**Use responsibly.** This toolkit is meant for authorized penetration testing and educational research only. Unauthorized access to devices is illegal and punishable by law.

## Install

```bash
git clone https://github.com/akhilathomas06/bloody_dragon
cd bloody_dragon
bash requirements.sh
```

Make sure `adb` and `scrcpy` run correctly from your shell.

## Usage

Launch the tool:

```bash
python3 bloody_dragon.py
```

Follow the badass colored menu to:

- Connect to devices **wired or wireless**
- Get shell access and control remotely
- Spy on network and battery status
- Inject keypresses and commands silently
- Upload or download files stealthily
- Add your own personal exploits and commands


## Example Menu

```
[1] Wired Connection - Plug and pwn
[2] Wireless Connection - Hack over WiFi like a boss
[3] Screen Control - See everything on the victim’s device
[4] Battery Info - Monitor device power stats
[5] Netstat - See open connections on the target
[6] Shell - Command-line control
[7] Upload/Download files - Get in, get out
[8] Keycode Injection - Simulate input remotely
[9] Add New Tool - Customize your hacker arsenal
[0] Exit - Or get busted
```


## Credits

- **Script by:** Akhila Thomas



## Disclaimer

This toolkit is a **proof-of-concept** and intended for authorized assessments only. The authors are **NOT responsible** for illegal use, damages, or data loss. **Always obtain explicit permission** before testing devices.

## Star the repo if you’re ready to hack like a pro!

Happy hacking. Stay stealthy.

**Remember:** With great power comes great responsibility. Use this tool wisely!

If you want me to customize further or add dark mode output themes or more “elite hacker” slang, just ask!
