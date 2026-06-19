<div align="center">

# 🌐 Ping Test Tools

<p>
 <img src="https://img.shields.io/badge/Network-Testing-00ADD8?style=for-the-badge&logo=network&logoColor=white"/> &nbsp;
 <img src="https://img.shields.io/badge/Layer4-00599C?style=for-the-badge&logo=c&logoColor=white"/> &nbsp;
 <img src="https://img.shields.io/badge/Layer7-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/> &nbsp;
 <img src="https://img.shields.io/badge/Platform-Linux-E8E8E8?style=for-the-badge&logo=linux&logoColor=black"/> &nbsp;
</p>

### 🔍 Check your server/network stability & response time

<p>
A comprehensive collection of network testing tools for analyzing server performance, latency, and bandwidth handling capacity.
</p>

---

<img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/> 
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/> 
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/> 
<img src="https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white"/> 
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>

</div>

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔹 **Layer 7 Testing** | HTTP-RAW, HTTP-SOCKET, HTTP-RAND, HTTP-STORM, OVERFLOW, CRASH, HYPER, TLSFLOOD, HTTP1 |
| 🔹 **Layer 4 Testing** | UDP, TCP, STD, FLUX, SLOWLORIS, GOD, DESTROY, UDP-BYPASS, NFO-KILLER |
| 🔹 **Amplification Tests** | OVH-AMP, LDAP, NTP, DNS |
| 🔹 **Bypass Methods** | Cloudflare, OVH, UAM, DDosGuard, Sucuri, StormWall, PipeGuard, BlazingFast |
| 🔹 **AMP / Games** | MINECRAFT, SAMP |
| 🔹 **Auto Installer** | Go auto-installs on non-root systems |
| 🔹 **Proxy Support** | HTTP, SOCKS4, SOCKS5 proxies included |

## 📦 Installation

```sh
# Clone the repository
git clone https://github.com/Yousuf323215/ping.git
cd ping

# Install Python dependencies
pip3 install -r requirements.txt

# Install Node.js dependencies
npm install

# Set limits
ulimit -n 999999

# Give execute permissions
chmod +x *

# Run
python3 c2.py
```

## 🚀 Quick Start

### Interactive Mode
```sh
python3 c2.py
```

### Direct Test
```sh
# Test with GET method (auto-installs Go if missing)
python3 c2.py https://example.com/

# Test with POST method
python3 c2.py https://example.com/ POST
```

## 🛠️ Available Tools

<details>
<summary><b>📋 Layer 7 Methods</b></summary>

| Method | Description |
|--------|-------------|
| `crash` | HTTP stress test (GET/POST) |
| `http-raw` | Raw HTTP request test |
| `http-socket` | Socket-based HTTP test |
| `http-rand` | Randomized HTTP flood |
| `http-storm` | High-volume HTTP test |
| `httpflood` | Multi-threaded HTTP flood |
| `overflow` | Buffer overflow test |
| `hyper` | Hyper HTTP stress test |
| `http1` | HTTP/1.1 protocol test |
| `tlsflood` | TLS handshake flood |
| `cf-bypass` | Cloudflare bypass test |
| `uambypass` | UAM bypass test |
| `cf-pro` | Advanced CF bypass |
| `https-spoof` | HTTPS spoof test |
| `slow` | Slow HTTP attack |
</details>

<details>
<summary><b>📋 Layer 4 Methods</b></summary>

| Method | Usage |
|--------|-------|
| `udp` | `udp <ip> <port>` |
| `tcp` | `tcp <ip> <port>` |
| `std` | `stdv2 <ip> <port>` |
| `flux` | `flux <ip> <port> <threads>` |
| `slowloris` | `slowloris <ip> <port>` |
| `god` | `god <ip> <port> <time>` |
| `destroy` | `destroy <ip> <port> <time>` |
| `udpbypass` | `udpbypass <ip> <port>` |
| `nfo-killer` | NFO protection test |
</details>

<details>
<summary><b>📋 Amplification Methods</b></summary>

| Method | Description |
|--------|-------------|
| `ovh-amp` | OVH amplification test |
| `ldap` | LDAP amplification |
| `ntp` | NTP amplification |
| `minecraft` | Minecraft server test |
| `samp` | SA-MP server test |
</details>

<details>
<summary><b>📋 Bypass Modules</b></summary>

| Module | Target |
|--------|--------|
| Cloudflare | CF protection bypass |
| OVH | OVH firewall bypass |
| DDosGuard | DDosGuard bypass |
| Sucuri | Sucuri WAF bypass |
| StormWall | StormWall bypass |
| PipeGuard | PipeGuard bypass |
| BlazingFast | BlazingFast bypass |
| PrivacyPass | Privacy Pass bypass |
</details>

## 📸 Screenshots

![Main Menu](https://i.ibb.co/LNkqyPR/bandicam-2022-04-12-22-11-34-101.jpg)

## ⚙️ Requirements

- **OS:** Debian / Ubuntu (20.04+ recommended)
- **Python:** 3.8+
- **Node.js:** 16+
- **Go:** 1.18+ (auto-installed if missing)
- **Perl:** 5.0+
- **Root:** Not required (auto-installs Go to `~/.local/go`)

## ⚠️ Disclaimer

> **For educational and authorized testing purposes only.**
> 
> Do not use against government (.gov/.gob), educational (.edu), or military (.mil) infrastructure.
> The creator is not responsible for any misuse. Always obtain proper authorization before testing any network or server.

---

<div align="center">

**Made by [Yousuf323215](https://github.com/Yousuf323215)**

⭐ Star this repo if you find it useful!

</div>
