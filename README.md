# 🚀 Infosec Tools ID - Kali Linux WSL2 + Win-KeX

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Kali-dragon-icon.svg" width="120"/>
</p>

<p align="center">
  <b>Kali Linux GUI di Windows (WSL2 + Win-KeX)</b><br>
  <i>Lightweight • Powerful • No Virtual Machine Needed</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/seraphim-blip/kali-wsl-infosec-tools?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/seraphim-blip/kali-wsl-infosec-tools?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/seraphim-blip/kali-wsl-infosec-tools?style=for-the-badge">
  <img src="https://img.shields.io/github/license/seraphim-blip/kali-wsl-infosec-tools?style=for-the-badge">
</p>

---

## ⚡ Overview

Jalankan **Kali Linux dengan GUI langsung di Windows** tanpa VirtualBox atau VMware.

✔ WSL2 Native Performance  
✔ GUI via Win-KeX  
✔ Cocok untuk Pentesting & Lab  
✔ Setup cepat & ringan  

---

## 🧠 Use Cases

- 🔍 OSINT Investigation  
- 🛡️ Penetration Testing Lab  
- 🌐 Web Security Testing  
- 🎓 Belajar Linux & Cybersecurity  

---

## ⚙️ Installation

### 1. Install WSL

```powershell
wsl --install --distribution kali-linux
```

Restart PC setelah selesai.

---

### 2. Jalankan Kali Linux

```bash
wsl -d kali-linux
```

---

### 3. Update System

```bash
sudo apt update && sudo apt full-upgrade -y
```

---

### 4. Install Win-KeX (GUI)

```bash
sudo apt install -y kali-win-kex
```

---

## 🖥️ Run GUI

### Window Mode (Recommended)
```bash
kex --win -s
```

### Seamless Mode
```bash
kex --sl -s
```

### Enhanced Mode
```bash
kex --esm --ip -s
```
---

## ⚠️ Troubleshooting

### Cek versi WSL
```powershell
wsl -l -v
```

---

## ⚠️ Disclaimer

Project ini hanya untuk:
- Edukasi
- Research
- Penggunaan legal

---

## ⭐ Support

Kalau repo ini membantu:

👉 ⭐ Star repository ini  
👉 🔁 Share ke komunitas kamu  

---

## 🔥 Infosec Tools ID

> Hack • Learn • Secure
