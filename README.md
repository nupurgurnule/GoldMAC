<p align="center">
  <img src="assets/logo.png" alt="GoldMAC Logo" width="300">
</p>

<h1 align="center">GoldMAC – MAC Address Spoofing Tool</h1>

<p align="center">
  <i>Anonymous MAC address rotation utility built for Linux pentesting and OPSEC</i>
</p>

<p align="center">
  <a href="https://github.com/GoldSkull-777/GoldMAC/stargazers">
    <img src="https://img.shields.io/github/stars/GoldSkull-777/GoldMAC?style=flat-square" />
  </a>
  <a href="https://github.com/GoldSkull-777/GoldMAC/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/GoldSkull-777/GoldMAC?style=flat-square" />
  </a>
</p>

---

## 📽️ Demo

![GoldMAC Demo](assets/demo.gif)

---

## ⚙️ Features

- 🔄 Automatic MAC address rotation
- 🎲 Fully random MAC spoofing
- 🏷️ Vendor OUI spoofing (Apple, Samsung, Intel, etc.)
- ⏱️ Time-based MAC rotation
- 📡 Live interface selection
- 🛑 Automatic MAC restoration on exit
- 🖥️ Rich terminal UI using `rich`
- 🧠 OPSEC-focused workflow

---

## 📦 Requirements

- ✅ Linux (Kali Linux / Debian / Ubuntu recommended)
- ✅ Python 3.x
- ✅ `macchanger`
- ✅ `iproute2`
- ✅ Root privileges

---

## 🚀 Usage

- Run **GoldMAC** as root
- Select the network interface
- Choose spoofing mode:
  - Random MAC
  - Vendor OUI MAC
- Set MAC rotation interval
- MAC address rotates automatically
- Press **CTRL+C** to safely restore the original MAC

---

## 🛡️ OPSEC Notes

- MAC spoofing protects **Layer-2 identity only**
- It does **NOT** provide full anonymity
- RF monitoring, traffic analysis, and behavior profiling still apply

For stronger OPSEC, combine with:
- VPN
- Controlled traffic exposure
- Short assessment windows
- Physical awareness

---

## 👤 Author

**GoldSkull-777**  
GitHub: [@GoldSkull-777](https://github.com/GoldSkull-777)

---

## ⚠️ Disclaimer

> This tool is intended for **educational and authorized penetration testing** only.  
> Do **not** use it on networks you do **not own** or do **not have explicit permission** to test.  
> Unauthorized use may be illegal and unethical.  
> The author is **not responsible** for any misuse or damage caused by this tool.

---

## 🚀 Installation

```bash
git clone https://github.com/GoldSkull-777/GoldMAC.git
cd GoldMAC
chmod +x GoldMAC.py
sudo ./GoldMAC.py
