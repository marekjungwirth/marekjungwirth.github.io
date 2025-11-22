---
layout: page
title: My Projects
permalink: /projects/
---

## 🚀 My Projects

### 🤖 Coinmate DCA Bot

A Python-based automation tool that executes a Dollar Cost Averaging (DCA) strategy on the Czech crypto exchange Coinmate.

* **Problem:** Manual DCA is tedious and prone to emotional errors.
* **Solution:** A script that periodically buys a fixed amount of Bitcoin (or other assets) regardless of the price.
* **Key Features:**
    * Secure API key management via environment variables.
    * Configurable buying parameters (amount, pair).
    * Error handling and logging.

**Tech Stack:**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Coinmate_API-orange?style=flat" alt="Coinmate API">
  <img src="https://img.shields.io/badge/Automation-green?style=flat" alt="Automation">
</p>

[**View Source Code on GitHub**](https://github.com/marekjungwirth/coinmate-dca-bot)

---

### 🌉 X -> Nostr Bridge

A cross-posting tool that automatically bridges content between the traditional social media platform X (formerly Twitter) and the decentralized protocol Nostr.

* **Problem:** Fragmented audience across centralized and decentralized networks makes content distribution tedious.
* **Solution:** A bridge script that listens for new posts on one platform and seamlessly mirrors them to the other, maintaining consistent presence on both.
* **Key Features:**
    * Bidirectional or unidirectional syncing support.
    * Handling of media attachments and links.
    * Secure key management for both Nostr (nsec) and X API.

**Tech Stack:**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Nostr_Protocol-purple?style=flat" alt="Nostr">
  <img src="https://img.shields.io/badge/X_API-black?style=flat&logo=x&logoColor=white" alt="X API">
</p>

[**View Source Code on GitHub**](https://github.com/marekjungwirth/nostr-x-bridge)

---

### ☀️ Nostr Slunce Bot

An automated bot that publishes daily solar and astronomical data (sunrise, sunset, day length) to the Nostr network.

* **Problem:** Accessing specific environmental data directly within a decentralized social feed without leaving the app.
* **Solution:** A standalone script that fetches or calculates daily solar data and broadcasts it as a formatted Nostr note.
* **Key Features:**
    * **Automated Scheduling:** Runs daily to provide fresh data every morning.
    * **Nostr Integration:** Signs and publishes events directly to defined relays using NIP-01.
    * **Data Fetching:** Integration with external weather/astronomical APIs.

**Tech Stack:**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Nostr_Protocol-purple?style=flat" alt="Nostr">
  <img src="https://img.shields.io/badge/APIs-grey?style=flat" alt="APIs">
</p>

[**View Source Code on GitHub**](https://github.com/marekjungwirth/nostr-slunce-bot)

---

### 💰 Crypto Tracker (Electron)

A lightweight desktop application built with Electron for tracking Bitcoin exchange rates and Coinmate balances in real-time, designed specifically for macOS.

* **Problem:** Logging into exchange websites just to check a balance is slow, insecure in public, and doesn't account for cold storage funds.
* **Solution:** A native desktop app that sits quietly in the background, aggregates balances from both the exchange and hardware wallets, and respects user privacy.
* **Key Features:**
    * **Privacy Mode:** Blurs sensitive financial data until hovered over (ideal for co-working spaces).
    * **Secure Architecture:** API keys are stored locally in the OS-secure storage, never exposed.
    * **Portfolio Trend:** Visualizes percentage changes over 24h, 7d, or 30d.
    * **Hardware Wallet Support:** Manually track cold storage (Trezor) alongside hot wallet funds.

**Tech Stack:**
<p align="left">
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white" alt="Electron">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white" alt="macOS">
</p>

[**View Source Code on GitHub**](https://github.com/marekjungwirth/coinmate-crypto-tracker)

---
