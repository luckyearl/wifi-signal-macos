# wifi-signal

> Real WiFi speed and ping — always visible in your menu bar.

<p align="center">
  <a href="https://applel0ver-lab.github.io/wifi-signal-macos/">
    <img src="https://img.shields.io/badge/Install-Open%20guide-0071e3?style=for-the-badge&logo=apple&logoColor=white" alt="Install — open installation guide" />
  </a>
</p>

---

## The problem

Your Mac shows full WiFi bars. But the page won't load. The video keeps buffering. The call keeps dropping. Those bars tell you nothing about actual speed or stability — just that you're connected to something.

## What this does

`wifi-signal` is a menu bar app that shows your real download speed, upload speed, and ping in real time. At a glance you know whether your connection is actually good — or just pretending to be.

- Live download and upload speed in menu bar
- Ping to your router and to the internet
- Signal strength in dBm, not just bars
- Connection history so you can see when it dropped

## Menu bar

```
↓ 94  ↑ 12  ms 8
```

Click to expand:

```
wifi-signal

  Download       94 Mbps   ████████░░
  Upload         12 Mbps   ███░░░░░░░
  Ping           8 ms      excellent
  Signal        -52 dBm    strong

  Network       Home WiFi
  Router        192.168.1.1
  IP            192.168.1.42

  ─────────────────────────────
  Today's drops: 0
  Slowest period: 14:00–15:00
```

## Features

**Live speed** — updates every second, no manual refresh needed.

**Ping monitor** — tracks latency to your router and to external servers separately so you know whether the problem is your router or your ISP.

**Signal strength** — real dBm value with a plain-language label: excellent, good, fair, weak.

**Drop history** — logs every time your connection went down and for how long.

**Alerts** — get notified when speed drops below a threshold you set, or when the connection is lost.

## Requirements

- macOS 13 Ventura or later
- Apple Silicon or Intel

## Privacy

All data is measured locally on your device. No network data or usage statistics are collected or transmitted.

## License

MIT
