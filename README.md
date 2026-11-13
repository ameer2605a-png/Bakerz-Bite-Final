# Bakerz Bite — Artisanal Bakery & Café SPA (v3)

> **Motto:** *"Where smiles are served daily."*  
> **Brand Ethos:** Premium quality, 100% real European butter (82%+ butterfat), farm-fresh cream, stone-ground unbleached flour, zero harmful additives.  
> **Currency:** Pakistani Rupees (PKR / Rs.)

---

## 🥐 Project Overview

**Bakerz Bite** is a production-ready, fully responsive Single-Page Application (SPA) designed with a warm, appetizing artisan color palette featuring:
- **Warm Cream** (`#FFFDD0`)
- **Rich Cocoa Brown** (`#3E2723`)
- **Bright Red Accents** (`#D32F2F`)
- **Soft Golden-Amber Highlights** (`#FFB300`)

---

## ✨ Features & Architecture

### 1. Exact Logo Integration & Ultra-Thin Navbar
- **Exact Logo Asset:** Real `./logo.png` file rendered in the navbar (40px fixed height) and footer — no generated/SVG placeholder.
- **Ultra-Thin Sticky Navbar (60px / 54px scrolled):** Kababjees-style compact header with glassmorphism, faint border + shadow on scroll, scrollspy pill highlight on all 7 sections (`#home`, `#menu`, `#offers`, `#gallery`, `#merchandise`, `#about`, `#contact`), live visitor counter, dark/light toggle, bold red **Order Now** CTA, and a smooth right side-drawer hamburger menu on ≤1024px.
- **Brand Palette:** Warm Cream (`#FFFDD0`), Rich Cocoa (`#3E2723`), Bright Red Accents (`#D32F2F`), and Golden Amber (`#FFB300`).

### 2. Currency & Pricing Update (PKR / Rs.)
- All prices, special offers, deals, order totals, and checkout amounts converted to Pakistani Rupees (PKR / Rs.).
- Standard format: `Rs. 450`, `Rs. 1,200`, `Rs. 3,850`, etc.
- Standard Reduced GST: 5% sales tax calculation.
- Courier delivery: Rs. 250 (100% Free on orders over Rs. 3,000).

### 3. Navigation Bar Fixes & State Transitions
- Seamless internal smooth scrolling to all 7 section IDs:
  - `#home` — Hero & Brand Ethos
  - `#menu` — Fresh Daily Menu (Cakes, Pastries, Cookies, Pies, Merch)
  - `#offers` — Sweet Savings & Daily Deals
  - `#gallery` — Photo Gallery & Lightbox
  - `#merchandise` — Branded Goods & Living Collection
  - `#about` — Our Backstory & Slow-Baking Craft
  - `#contact` — Flagship Boutique Location & Custom Cake Inquiry Form
- Hover states with bright red accent tint and active visual highlights with smooth fade-in/fade-out transitions.
- IntersectionObserver scrollspy ensuring active link indicators dynamically update.

### 4. Sleek & Compact Footer
- Compact height and padding design.
- Quick navigation links: **Site Map**, **Gallery**, **About Us**, **FAQ**, and **Contact Us**.
- Interactive **FAQ Modal** addressing ingredient purity, flour standards, PKR payment methods, and custom cake lead times.
- Interactive **Site Map Directory Modal** for instant jump to any section.
- Direct WhatsApp ordering shortcut pill.

### 5. Continuous Geolocation & Live Clock Ticker
- Fixed at the very bottom with live date, ticking clock (1s resolution), and continuous marquee loop.
- HTML5 Geolocation API with reverse geocoding detecting user city & country, with clean Pakistani fallback.

### 6. Bakery Preloader & Theme Switcher
- **Bakery-Themed Preloader:** Animated mixing bowl with spinning whisk and rising golden batter, smoothly fading out on page load.
- **Dark / Light Mode Toggle:** Smooth CSS custom property transitions, saving preferences to `localStorage`.

### 7. AI Chatbot Concierge ("BiteBot")
- Floating assistant in the bottom-right corner with pulse indicator ring.
- Real-time conversational bakery assistance answering queries on ingredients, unbleached flour, PKR prices, JazzCash/EasyPaisa payments, store hours, and coupon codes.

### 8. Multi-Option Checkout & Payment Modal
- Product "Order Now" buttons trigger instant checkout.
- Three payment options:
  1. **Credit / Debit Card:** Visa, Mastercard, PayPak, UnionPay.
  2. **JazzCash & EasyPaisa (PKR Local Payments):** Mobile wallet account number, MPIN prompt, instant OTP simulation, and QR code option.
  3. **Apple Pay / Google Pay:** Biometric 1-click authorization.
  4. **Cash on Delivery (COD):** Pay the delivery rider in cash on arrival.
- Digital order receipt with unique order ID (`#BB-PK-XXXXXX`), fulfillment countdown, itemized bill, and printable receipt.

### 9. Core Menu & Merchandise Features
- Categorized menu: Cakes, Pastries, Cookies, Pies, and Merchandise (Mugs, Bags, Glasses, Trays).
- Dedicated product cards in `#merchandise` section.
- Product modal with comprehensive ingredient lists highlighting **100% Real Butter**, **Fresh Farm Cream**, and **Stone-Ground Unbleached Flour**.
- Live keyword search, dietary filter pills, and sorting dropdown.
- Customer reviews stream with 1-5 star rating picker and instant submission.

---

## 🚀 How to Run

Open `index.html` directly in your browser or run a local static server:

```powershell
# Using Python
python -m http.server 8080

# Using Node.js npx
npx serve .
```

Then visit [http://localhost:8080](http://localhost:8080).
