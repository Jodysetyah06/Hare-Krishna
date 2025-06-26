# 🔒 HARE KRISHNA - Anonymizer Tool v1.1

![banner](https://img.shields.io/badge/Bash-Anonymizer-blue.svg) ![license](https://img.shields.io/badge/License-MIT-green.svg)

> ⚔️ **By CYBER-MRINAL**  
> Advanced Linux-based MAC/IP randomizer + Tor anonymizer  
> Protect your identity. Defend your network. Stay hidden like a ghost. 🛡️

---

```
'##::::'##::::'###::::'########::'########::::'##:::'##:'########::'####::'######::'##::::'##:'##::: ##::::'###::::
 ##:::: ##:::'## ##::: ##.... ##: ##.....::::: ##::'##:: ##.... ##:. ##::'##... ##: ##:::: ##: ###:: ##:::'## ##:::
 ##:::: ##::'##:. ##:: ##:::: ##: ##:::::::::: ##:'##::: ##:::: ##:: ##:: ##:::..:: ##:::: ##: ####: ##::'##:. ##::
 #########:'##:::. ##: ########:: ######:::::: #####:::: ########::: ##::. ######:: #########: ## ## ##:'##:::. ##:
 ##.... ##: #########: ##.. ##::: ##...::::::: ##. ##::: ##.. ##:::: ##:::..... ##: ##.... ##: ##. ####: #########:
 ##:::: ##: ##.... ##: ##::. ##:: ##:::::::::: ##:. ##:: ##::. ##::: ##::'##::: ##: ##:::: ##: ##:. ###: ##.... ##:
 ##:::: ##: ##:::: ##: ##:::. ##: ########:::: ##::. ##: ##:::. ##:'####:. ######:: ##:::: ##: ##::. ##: ##:::: ##:
..:::::..::..:::::..::..:::::..::........:::::..::::..::..:::::..::....:::......:::..:::::..::..::::..::..:::::..::

                                🛕 Ancient name. ⚔️ Modern defense. 🔒
```

---

## 🎯 Purpose

`HARE-KRISHNA` is a terminal-based anonymization tool for Linux systems.  
It combines **MAC address spoofing**, **IP obfuscation**, and **Tor-based routing** to make your device harder to track and fingerprint.

---

## ⚙️ Features

✅ MAC Address randomizer  
✅ IP change via Tor (`socks5h`)  
✅ Start/Stop anonymization sessions  
✅ System-wide proxy with Tor  
✅ Built-in log viewer  
✅ Update checker (`--update`)  
✅ Works on Kali, Parrot, Arch, Ubuntu, Debian, and more  
✅ Failsafe rollback on update failure  
✅ Clean CLI interface with banner, help, and status report

---

## 📥 Installation

### 🔧 Using `setup.py` (Recommended)

```bash
git clone https://github.com/CYBER-MRINAL/Hare-Krishna.git
cd Hare-Krishna
chmod +x setup.sh
sudo ./setup.sh
```

➡️ After setup, run the tool via:

```bash
sudo hare-krishna -h 
```
(To show arguments/help funciton)
---

## 💻 Usage

```bash
sudo ./hare-krishna.sh -st           # Start anonymization
sudo ./hare-krishna.sh -sp           # Stop and restore original state
sudo ./hare-krishna.sh -cmc -m XX:XX:XX:XX:XX:XX   # Change MAC manually
sudo ./hare-krishna.sh -cip          # Change IP via Tor
sudo ./hare-krishna.sh -s            # Show anonymization status
sudo ./hare-krishna.sh --cti         # To show your tor ip address 
sudo ./hare-krishna.sh --logs        # View logs
sudo ./hare-krishna.sh --update      # Update tool from GitHub
sudo ./hare-krishna.sh --version     # Show tool version
```

---

## 🧩 Command Reference

| Flag       | Description                             |
|------------|-----------------------------------------|
| `-st`      | Start anonymization                     |
| `-sp`      | Stop and restore                        |
| `-cmc -m`  | Change MAC to custom address            |
| `-cip`     | Change IP (restart Tor)                 |
| `-s`       | Show status                             |
| `--logs`   | View log history                        |
| `--cti`    | To see tor ip address                   |
| `--update` | Check and apply updates (via Git)       |
| `--version`| Show current version                    |
| `--debug`  | Enable debug output                     |
| `-h`       | Help / usage guide                      |

---

## 🔐 Security Considerations

⚠️ This tool **modifies your network interfaces**, routes traffic via **Tor**, and makes low-level system changes.  
Always run as **root or with sudo**, and make sure to:

- Trust the Tor network  
- Understand your legal responsibilities  
- Use in a **controlled or ethical** environment

---

## 🛠️ Troubleshooting

| Issue                        | Solution |
|-----------------------------|----------|
| `Tor failed to start`       | `sudo systemctl restart tor` |
| `MAC not changing`          | Ensure interface is down during change |
| `No internet after start`   | Check DNS leaks or firewall rules |
| `Update fails`              | Use `git pull` or re-clone manually |
| `proxy-setting`             | Make sure you fix your browser and system proxy setting to use it. |

---

## 🧠 Contributions

Pull requests, improvements, and suggestions are always welcome.

📧 Author: CYBER-MRINAL  
🔗 GitHub: [CYBER-MRINAL](https://github.com/CYBER-MRINAL)  
🛕 Inspired by ancient wisdom, coded for modern defense.
For more query and issue go to my [telegram](https://t.me/cybermrinalgroup/3) and ask me.

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to modify, share, and use with credit.

---

> “Hare Krishna Hare Krishna, Krishna Krishna Hare Hare  
>  Hare Rama Hare Rama, Rama Rama Hare Hare.”  
>  — Chant for liberation, now protecting your packets.