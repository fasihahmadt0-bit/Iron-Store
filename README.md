# Iron Store (لوہا اسٹور)

**Iron Store** is a lightweight, high-performance, **100% on-device**, and **offline-first** Point of Sale (POS) and inventory management web application. Specially designed for iron, steel, hardware, and retail supply operations, it allows owners to manage storefront activities smoothly without relying on an active internet connection or expensive cloud database subscriptions.

---

## 🚀 Key Features

*   **Offline-First & On-Device Storage**: Powered by **IndexedDB** (`iron_v7`) for zero-latency data access that functions entirely offline without data ever leaving your machine.
*   **Complete Retail POS System**: Simple product matrix grid featuring instant product filtering, low-stock warnings, customizable item quantity configurations via an embedded numpad, and an active shopping cart with discount inputs.
*   **Split-Payment Options**: Supports multiple transaction tracking methods: **Cash**, complete credit (**Udhar**), or **Partial** payment splits.
*   **Automated Accounting & Ledger Sheets**: Real-time business overview dashboard featuring automatic calculations for aggregate Sales, operational Expenses, and collective Udhar accounts. Generates localized **Income Statements** displaying gross/net profit structures.
*   **Client Ledger System**: Dedicated customer directories with detailed statement logs. Features quick-actions to launch client communications via WhatsApp text triggers or direct cellular calls.
*   **Secure Infrastructure Control**: Full local data ownership backups with manual triggers for data imports/exports in JSON formats or structured spreadsheet data tables (CSV/Excel).
*   **Progressive Web App (PWA)**: Built with an explicit Service Worker script (`sw.js`) utilizing a network-first caching approach for optimal platform performance. Installs seamlessly as a standalone desktop or mobile application.

---

## 📦 Project File Structure

```text
├── index.html       # The entire single-page app interface (HTML5, CSS3, & vanilla JS)
├── manifest.json    # Progressive Web App manifest defining standalone display configurations
├── sw.js            # Offline network proxy service worker asset cache
└── icon.svg         # High-resolution application brand identity layout vector
