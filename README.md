# Load-Tracker-Changelog

# 🚚 Load Tracker (PWA)

**Load Tracker** is an internal-use Progressive Web App designed for managing vehicle payloads in underground mining and logistics environments. It operates fully offline and is optimized for tablet devices used in the field.

---

## ✨ Features

- 🔧 **Vehicle Setup**
  - Manual entry of vehicle capacity (persisted per vehicle)
  - Predefined defaults for common models (Ranger, LandCruiser, Isuzu)
  - Setup includes vehicle name, make, model, and optional accessories

- 🛠️ **Accessory Management**
  - Rod Rack tracking (500 kg max capacity)
  - Jack and Fire Suppression (visual indicators only – no longer affect payload)

- 🛒 **Product Tracking**
  - Add tray and rack items separately
  - Supports custom weight and quantity per item
  - Trial items can be marked with comments and visual flags
  - Rack vs. Tray totals tracked independently

- ⛽ **Fuel Level Input**
  - Visual 1/8 to full gauge
  - Dynamically adjusts usable capacity
  - Included in logs and summaries

- 📈 **Capacity Summary**
  - Real-time tray/rack/total weight display
  - Capacity used shown as % with progress bar
  - Overload warnings built in

- 💾 **Offline Storage**
  - LocalStorage used for all data persistence
  - Per-vehicle tracking
  - Backup and restore functionality via JSON file

- 📤 **Log Export**
  - Generates detailed plain-text logs
  - Includes vehicle config, capacity, fuel level, and full load breakdown
  - Opens user email client for quick submission

- ♻️ **Recycling Mode**
  - 10% auto deduction on product weights
  - Simplified interface with Home button and no menu

---

## 📋 Change Log

All changes are tracked publicly in the following repository:  
📄 **[modicum-au/changelog](https://github.com/modicum-au/changelog)**

---

## 🔐 Privacy Notice

This tool does not transmit any user data over the internet.  
All operations are done client-side. No cloud storage is used.

---

## 🧠 Internal Use Only

This application is developed and maintained by **Modicum**.  
Unauthorized redistribution is prohibited.

For support or feature requests, contact:  
📧 `info@modicum.au`

---