# NS Office Supplies & Printing Services — Business Management System

A single-page, offline-first business management web app built for **NS Office Supplies and Printing** (Dipolog City, Zamboanga Del Norte, Philippines). Handles sales tracking, invoicing, and day-to-day shop operations entirely in the browser — no server or database required.

## ✨ Features

- 🔐 Simple login system (local, browser-based)
- 💵 Quick Sale entry with remarks and custom date support
- 🧾 Sales Invoice generator — create, preview, print, save, and edit invoices
- 📦 Inventory tracking with automatic stock deduction on sale
- 📊 Dashboard with stat cards and sales summaries
- 🖨️ Print-ready invoice layout (browser print dialog)
- 💾 All data stored locally via `localStorage` — works fully offline

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox)
3. Log in and start using the system

No build steps, no dependencies, no installation needed.

## ⚠️ Important Notes

- **First-time setup:** On first launch, a default admin account is created. Check the source code (`ns_users` initialization) for the default credentials, and **change the password immediately** after your first login.
- **Data storage:** All data (sales, invoices, inventory, logs) is stored in your browser's `localStorage`. This means:
  - Data is tied to the specific browser/device you use
  - Clearing browser data will erase all records
  - Data does **not** sync across devices
  - Always back up important data regularly (e.g., export/print records)
- This project is intended for **single-device, small-shop use**. For multi-user or cloud-synced needs, consider a backend-powered version (e.g., using Firebase or a database).

## 🛠️ Tech Stack

- Plain HTML, CSS, and JavaScript (no frameworks)
- Google Fonts (Outfit, JetBrains Mono)
- Browser `localStorage` as the data layer

## 📄 License

This project is shared for educational and personal/business use. Feel free to fork and adapt it for your own shop.

## 🏪 About

Built for **NS Office Supplies and Printing**, FR Patangan Rd, Dipolog City, Zamboanga Del Norte, Philippines.
