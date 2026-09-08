# Mr. IPO Releases

Every IPO. Everything about IPO.

This repository contains public Android development and production testing builds of Mr.IPO and the Mr.IPO Admin Console.

---

## 📱 Latest Production Release: v1.0.4

### 📦 Download APKs
- **[Mr.IPO User App (v1.0.4)](https://github.com/mripoofficial/MrIPO-Releases/releases/download/v1.0.4/MrIPO-UserApp-v1.0.4.apk)**
- **[Mr.IPO Admin App (v1.0.0)](https://github.com/mripoofficial/MrIPO-Releases/releases/download/v1.0.4/MrIPO-AdminApp-v1.0.0.apk)**

---

### 🚀 Highlights & Changelog (v1.0.4)
- **Centralized Server-Side Upstox Data Pipeline**: Normal users never connect individual broker accounts; authoritative data is synchronized from Upstox to Supabase.
- **Admin Console Upstox Pipeline & On-Demand Sync**: Admin can login with Upstox and trigger on-demand sync anytime with live UI feedback.
- **Conditional PAN Allotment Checker**: Action button and bottom sticky bar are strictly conditioned to appear ONLY on `Allotted` and `Listed` IPOs.
- **Lifecycle & Tab Categorization Engine**: Accurate mapping across Open, Upcoming, Awaiting Allotment, and Allotted stages.
- **Live Scraped GMP & Admin Overrides**: Automatic live scraping with explicit manual override precedence.