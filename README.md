# QR & NFC Review Assistance System (Zero Recurring Cost)

A high-conversion, 100% client-side web application designed to help restaurants and hotels collect genuine, detailed 5-star Google reviews using table standees, NFC tags, and QR codes.

---

## 🚀 Key Highlights
- **Zero Recurring Cost (₹0/mo forever):** 100% static web application (HTML5/CSS3/Vanilla JS). No backend server, no database fees, no API subscriptions.
- **2,100+ Authentic Pre-written Reviews:** 1,050 for Restaurants across 15 themes + 1,050 for Hotels across 15 themes. Every single review has 100% unique phrasing.
- **60-Day Per-Restaurant Smart Cooldown:** When a review is copied, it is locked for 60 days for that specific restaurant on that device, ensuring guests always see fresh suggestions.
- **Stationary Mobile Card Experience:** Clean, fixed-position review card where only tags and text smoothly transition on swipe or tap.
- **Print-Ready 300 DPI Standee Generator:** Produces pixel-perfect 4" × 6" (105 × 152 mm) print-ready acrylic table standee artwork in 3 luxury editions.
- **Admin Directory & Dashboard:** Search, filter, edit, and onboard clients with persistent browser storage and one-click JSON backup export/import.
- **100% Google Review Policy Compliant:** Neutral invitation wording, writing assistance framing, zero review gating, zero deceptive incentives.

---

## 📁 Repository Structure
```
├── index.html           # Customer-facing mobile review assistance page (with 2,100 reviews inlined)
├── standee.html         # 4" x 6" Acrylic table standee template & 300 DPI print-ready PNG exporter
├── admin.html           # Business onboarding dashboard, directory, & QR/NFC generator
├── styles.css           # Desktop fallback styling
├── assets/
│   └── qrcode.js        # Offline QR code generator engine
└── data/
    ├── reviews.json     # Full database of 2,100 categorized reviews (JSON)
    ├── reviews.js       # Global JS bundle with 2,100 reviews
    ├── restaurants.json # Sample restaurant profiles
    ├── hotels.json      # Sample hotel profiles
    └── businesses.json  # Onboarded business directory backup
```

---

## 🌐 Live URLs on GitHub Pages
Once deployed to GitHub Pages:
- **Customer Mobile App:** `https://<your-username>.github.io/<repo-name>/`
- **Admin Dashboard:** `https://<your-username>.github.io/<repo-name>/admin.html`
- **Table Standee Exporter:** `https://<your-username>.github.io/<repo-name>/standee.html`
