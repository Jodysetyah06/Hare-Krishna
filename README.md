# 🔒 HARE KRISHNA - Anonymizer Tool v1.0

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
chmod +x setup.py
sudo ./setup.py
```

➡️ After setup, run the tool via:

```bash
sudo hare-krishna --help
```

---

## 💻 Usage

```bash
sudo ./hare-krishna3.sh -st           # Start anonymization
sudo ./hare-krishna3.sh -sp           # Stop and restore original state
sudo ./hare-krishna3.sh -cmc -m XX:XX:XX:XX:XX:XX   # Change MAC manually
sudo ./hare-krishna3.sh -cip          # Change IP via Tor
sudo ./hare-krishna3.sh -s            # Show anonymization status
sudo ./hare-krishna3.sh --logs        # View logs
sudo ./hare-krishna3.sh --update      # Update tool from GitHub
sudo ./hare-krishna3.sh --version     # Show tool version
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
| `--update` | Check and apply updates (via Git)       |
| `--version`| Show current version                    |
| `-nb`      | No banner mode                          |
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

---

## 🧠 Contributions

Pull requests, improvements, and suggestions are always welcome.

📧 Author: CYBER-MRINAL  
🔗 GitHub: [CYBER-MRINAL](https://github.com/CYBER-MRINAL)  
🛕 Inspired by ancient wisdom, coded for modern defense.

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to modify, share, and use with credit.

---

> “Hare Krishna Hare Krishna, Krishna Krishna Hare Hare  
>  Hare Rama Hare Rama, Rama Rama Hare Hare.”  
>  — Chant for liberation, now protecting your packets.
