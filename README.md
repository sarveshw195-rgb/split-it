<div align="center">

# SplitIt Pro

**Split bills with friends without the spreadsheet — point your camera at the receipt, add a couple of taps, share the exact split on WhatsApp or SMS.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live_Demo-OPEN_IT_NOW-f0e040?style=flat&logo=github)](https://sarveshw195-rgb.github.io/split-it/)
[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)]()
[![No account needed](https://img.shields.io/badge/account-none-green.svg)]()
[![Runs on device](https://img.shields.io/badge/data-never_leaves_your_phone-4ade80.svg)]()

![SplitIt Pro banner](assets/banner.jpg)

</div>

## 💸 OPEN IT LIVE — no install, no signup

<div align="center">

### [**OPEN SPLITIT PRO → https://sarveshw195-rgb.github.io/split-it/**](https://sarveshw195-rgb.github.io/split-it/)

*One HTML file. Zero installs. No login. Everything runs on your device.*

</div>

## ✨ Features

| | | |
|:---:|:---|:---|
| 📷 **Receipt scan** | Point your camera at the bill — live camera view, grab items straight off the plate. Works with any restaurant receipt. | |
| 🎙️ **Voice input** | Say the items out loud — the Web Speech API writes them down for you. Hands are full when you're eating, not when you're splitting. | |
| 👥 **Your squad** | Add people once, save profiles on the device, tap to include them in the next bill. | |
| 🍽️ **Assign items** | Drop each dish on the people who ate it — shared items go to everyone automatically. | |
| 🧮 **Smart totals** | Tax and tip computed per person, in proportion. Everyone sees their exact share: `owes ₹347.20 (+₹41.50 tax/tip)`. | |
| 💱 **7 currencies** | `$` `€` `£` `¥` `₹` `₦` `R` — one tap to switch on the onboarding screen, remembered across sessions. | |
| 📨 **Share the split** | One tap builds a clean WhatsApp / SMS message with every person's share — paste it in the group and you're done. | |
| 🔒 **Private by design** | No account, no ads, no analytics, no backend. Everything is `localStorage` on your device. | |

## 📱 Screenshots

<div align="center">

![Live app](assets/demo.jpg)

*The live app: squad on the left, items on the right, per-person shares at the bottom.*

</div>

## 🚀 Getting started

1. **The easy way** — open the live demo: [https://sarveshw195-rgb.github.io/split-it/](https://sarveshw195-rgb.github.io/split-it/)
2. **Run locally** — clone or download this repo, then open `index.html` in your browser (or serve it):

```bash
npx serve .
```

3. **Android app** — a wrapped APK (WebIntoApp, package `com.quantumtech.splitit`) is attached to the [releases](../../releases). Install it, or build your own from this repo if you prefer.

## 🧭 How it works

- **Camera scan** uses `getUserMedia` to show a live view of the bill — copy item names and amounts across, no OCR servers involved.
- **Voice input** uses the browser's Web Speech API — recognition runs on-device (Chrome/Edge on desktop and Android support it).
- **The split math**: each item is divided among its assigned people, tax and tip are added proportionally, and the grand total is cross-checked against the sum everyone owes.
- **Profiles and currency** live in `localStorage` (`splitit_v2`) — clear your browser storage and everything is gone, by design.

## 🗺️ Roadmap

- [ ] Receipt OCR in-browser (canvas + WASM, still no servers)
- [ ] Export split as PDF / image for proof
- [ ] Dark/light theme toggle
- [ ] WhatsApp share via URL scheme with phone numbers prefilled
- [ ] PWA install banner (add-to-homescreen)

## 🤝 Contributing

PRs and issues are very welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). The golden rule: keep the no-backend, on-device promise intact.

## 🔐 Privacy

SplitIt Pro never sends your data anywhere. There is no server, no analytics, no ads. Camera and microphone only run when you use the scan/voice tools, in your own browser, and nothing is recorded or stored beyond your own device.

## 📜 License

Released under the [MIT License](LICENSE) — © 2026 sarveshw195-rgb.

---

⭐ If SplitIt Pro saves your friendships at the table, star the repo — it genuinely helps others find it.
