# DanVPN

A lightweight VPN / proxy client for Windows with GUI, built on top of [sing-box](https://github.com/SagerNet/sing-box).
Supports VLESS (Reality / WS / gRPC / XTLS-Vision), VMess, Trojan, Shadowsocks.
Works with subscriptions in **base64**, **sing-box JSON**, and **Clash YAML** formats.

![platform](https://img.shields.io/badge/platform-Windows-blue)
![python](https://img.shields.io/badge/python-3.10%2B-yellow)
![license](https://img.shields.io/badge/license-MIT-green)

---

## Features

- 🎨 Dark GUI (customtkinter)
- 📋 Subscriptions: base64, sing-box JSON, Clash YAML, plain links
- 🔗 Manual links: `vless://`, `vmess://`, `trojan://`, `ss://`
- ⚡ TCP ping + Real ping through the core (via Clash API)
- 🖥 Two modes: **Proxy** (SOCKS5 + HTTP on `127.0.0.1:2080`) and **VPN (TUN)**
- 🌐 One-click Windows system proxy toggle
- 📊 Live up/down traffic counter
- 🔄 Auto-update subscriptions on launch
- 📜 Built-in logs
- 💾 All data stored in `%APPDATA%\DanVPN\`
