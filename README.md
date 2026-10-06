# SurplusLink — Civic Food Recovery Network

A pixel-perfect, static **HTML5 & CSS3** web application built directly from Figma design specifications for **SurplusLink**, a civic food redistribution and surplus management platform connecting verified food businesses, shelters, community pantries, and volunteer food rescue coordinators.

---

## 🌟 Technical Highlights

* **Zero External Dependencies**: Strictly **100% Native HTML5 and CSS3** (no JavaScript, no React/Vue/Angular, no Node.js/backends, no Tailwind CSS or Bootstrap).
* **Pure CSS Interactivity**:
  * Segmented Role Switchers (`Recipient / Collector` vs `Provider / Donor`) on Sign In and Create Account pages using `:checked + label` logic.
  * Interactive Toggle Switches (with animated slider thumbs) on Account Preferences & Safety Notifications.
  * Interactive Dietary & Storage Pill Selectors and Radio Cards on Listing Creation.
  * Real-time Multi-Tag Filter Checkboxes on the Browse Feed.
  * Interactive Date Range and Department Breakdowns on Analytics.
  * Status Filter Tabs (All vs Unread) on Notifications.
  * Interactive Rating Radios and Feedback Tags on Confirmation Receipts.
* **Design Token System**: Unified CSS Custom Properties (`:root`) for colors, typography, elevations, spacing scales, and rounded borders.
* **Responsive Architecture**: Fluid desktop, tablet, and mobile layouts with persistent mobile navigation bars.

---

## 🎨 Design System & Color Palette

* **Primary Navy**: `#0F172A` / `#1E293B` (Used for primary actions, dark banners, headers, and strong brand contrast).
* **Rescue Emerald / Mint Accent**: `#065F46` / `#059669` / `#10B981` / `#A7F3D0` / `#E8F5EF` / `#F4FBF8` (Used for verified badges, fresh food highlights, environmental impact metrics, and sustainability signals).
* **Urgency & Status Colors**:
  * **Critical / Urgent**: `#DC2626` / `#FEE2E2` / `#FECACA` (Expiring soon / <2 hours).
  * **Warning**: `#D97706` / `#FEF3C7` / `#FDE68A` (Expiring today / 4–8 hours).
  * **Success / Available**: `#059669` / `#E8F5EF` / `#A7F3D0`.
* **Typography**: Clean, readable sans-serif font stack (`-apple-system`, `BlinkMacSystemFont`, `"Segoe UI"`, `Roboto`, `"Helvetica Neue"`, `sans-serif`) with font-smoothing.

---

## 📄 Page Directory

| Page | File | Description |
| :--- | :--- | :--- |
| **Explore Food (Feed)** | [`index.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/index.html) | Browse surplus listings with live search, interactive filter tags, countdown urgency badges, and portion counters. |
| **Listing Details** | [`listing-details.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/listing-details.html) | Detailed view with food specifications, allergens, pickup time window, safe storage instructions, donor credibility score, and reservation CTA. |
| **Create Listing** | [`create-listing.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/create-listing.html) | Donor flow to share surplus with portion/weight units, dietary pills, storage conditions, and live preview card. |
| **Recipient Verification** | [`verification.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/verification.html) | Verification step for non-profit shelters and community pantries before claiming surplus. |
| **Active Reservation** | [`reservation.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/reservation.html) | Live pickup coordination hub with QR code security token, timer countdown, donor contact, and map directions. |
| **Pickup Confirmation** | [`pickup-confirmation.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/pickup-confirmation.html) | Completed handoff receipt with lifecycle timeline, environmental impact metrics, interactive rating, and feedback tags. |
| **Impact Analytics** | [`analytics.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/analytics.html) | Sustainability dashboard tracking meals rescued, CO₂e prevented, landfill diversion, and department breakdown. |
| **Notifications** | [`notifications.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/notifications.html) | Real-time alert center for reservation confirmations, urgent expiry warnings, and volunteer assignments. |
| **User Profile & Settings** | [`profile.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/profile.html) | Account settings, organization credentials, interactive preference toggle switches, and secure logout. |
| **Sign In** | [`signin.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/signin.html) | Authentication page featuring interactive Recipient vs Provider role switcher and quick badge scan options. |
| **Create Account / Sign Up** | [`create-account.html`](file:///c:/Users/lenovo/Desktop/codeINIT/PixelRush-Team_codeINIT_SU/create-account.html) | Registration portal with selectable role cards, organization registration fields, and food rescue spotlight banner. |

---

## 🚀 How to Run Locally

Because SurplusLink is built entirely with static HTML and CSS:

1. Open any HTML file directly in any modern web browser (e.g. double-click `index.html`), or
2. Run a simple local static server:
   ```bash
   npx serve .
   # or
   python -m http.server 3000
   ```
3. Navigate to `http://localhost:3000` in your web browser.

---

## 🏛 Architecture & File Structure

```
├── index.html                 # Explore surplus feed & search
├── listing-details.html       # Single listing view & claim action
├── create-listing.html        # Surplus listing creation form
├── verification.html          # Recipient organization verification
├── reservation.html           # Active pickup ticket & QR pass
├── pickup-confirmation.html   # Final receipt & impact logger
├── analytics.html             # Environmental impact metrics & analytics
├── notifications.html         # Alerts & reservation updates
├── profile.html               # User profile & interactive toggles
├── signin.html                # Login with pure CSS role switcher
├── create-account.html        # Registration with selectable role cards
├── signup.html                # Alias to create-account
├── style.css                  # Master stylesheet (tokens, layout, controls)
├── README.md                  # Comprehensive project documentation
└── assets/
    └── images/                # Extracted food photography & icons
```

---

*Designed and implemented with precision for high-efficiency civic food rescue.*