<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,12,0&height=180&section=header&text=Cartly&fontSize=64&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Full-Featured%20E-Commerce%20Marketplace&descAlignY=58&descSize=18" width="100%"/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-cartly--mu.vercel.app-ff4500?style=for-the-badge&logo=vercel&logoColor=white)](https://cartly-mu.vercel.app)
[![Built By](https://img.shields.io/badge/Built_by-CodeWithK-0ea5e9?style=for-the-badge)](https://codewithkweb.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](.)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](.)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](.)
[![EmailJS](https://img.shields.io/badge/EmailJS-FF6B35?style=for-the-badge)](.)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://cartly-mu.vercel.app)

**A complete shopping experience with live cart, checkout flow, coupon codes, wishlist and real email integration — zero frameworks, pure JavaScript.**

</div>

---

## 📌 Overview

Cartly is a production-quality e-commerce marketplace built as a **CodeWithK** freelance demo. It demonstrates a complete shopping flow — browse → filter → cart → coupon → checkout — using only vanilla HTML, CSS, and JavaScript. No React, no Vue, no frameworks.

> 💡 **Try it live:** Add items → apply coupon `CARTLY10` → checkout at [cartly-mu.vercel.app](https://cartly-mu.vercel.app)

---

## ✨ Features

| # | Feature | Description |
|:---:|---|---|
| 🛒 | **Live Cart System** | Add, remove, qty controls — real-time price updates |
| 🏷️ | **Coupon Codes** | `CARTLY10` applies 10% discount instantly |
| 🚚 | **Smart Delivery** | Free delivery auto-applied above ₹499 |
| ✅ | **Order Confirmation** | Unique order ID modal on checkout |
| ⚡ | **Flash Deals** | 4 time-limited deal cards with live countdown |
| ❤️ | **Wishlist Toggle** | Save/unsave any product |
| 🔍 | **Live Search** | Real-time product filtering as you type |
| 🗂️ | **Category Filters** | Electronics · Fashion · Home · Beauty · Sports |
| 📊 | **Sort Controls** | Price low→high, high→low, top rated |
| 📬 | **Contact Form** | EmailJS — real email delivery, no backend needed |
| 📱 | **Fully Responsive** | Desktop, tablet, mobile optimised |

---

## 🛠️ Tech Stack

```
Frontend     →   HTML5, CSS3, Vanilla JavaScript (ES6+)
State Mgmt   →   Pure JS DOM — no React/Vue/Angular
Email        →   EmailJS SDK (real delivery to Gmail)
Fonts        →   Google Fonts — Syne + Manrope
Icons        →   Inline SVG — no icon library dependencies  
Hosting      →   Vercel (auto-deploy from GitHub)
```

---

## 🛒 Cart Logic

```javascript
// Core cart operations — pure vanilla JS
addToCart(id, btn)         // Adds to cart, bumps badge, shows toast
addDeal(id, name, price)   // Adds flash deal item to cart
changeQty(id, delta)       // +1 / -1 with live price recalc
removeItem(id)             // Removes with animation
applyCoupon('CARTLY10')    // Validates & applies 10% discount
calcTotals()               // Subtotal + discount + delivery = total
checkout()                 // Clears cart, shows order confirmation modal
```

---

## 📦 Product Catalogue

12 realistic products across 6 categories:

| Product | Category | Price | Discount |
|---|---|---|---|
| iPhone 15 Pro Max 256GB | Electronics | ₹1,34,900 | -16% |
| Sony WH-1000XM5 Headphones | Electronics | ₹24,990 | Hot |
| MacBook Air M3 256GB | Electronics | ₹1,04,900 | -22% |
| Nike Air Max 270 React | Fashion | ₹8,995 | -31% |
| boAt Rockerz 450 | Electronics | ₹1,299 | -48% |
| Levi's 511 Slim Jeans | Fashion | ₹2,499 | -38% |
| Leather Crossbody Bag | Fashion | ₹2,399 | -40% |
| Instant Pot Duo 7-in-1 | Home | ₹8,999 | Best |
| The Ordinary Serum | Beauty | ₹790 | Best |
| Puma Training Shorts | Sports | ₹999 | -44% |
| + 4 Flash Deals | Watches/Gaming/Fitness | — | Limited |

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| Background | `#0c0c0c` | Dark base |
| Accent | `#ff4500` | Orange-red — CTA, badges |
| Off-white | `#f7f7f5` | Section backgrounds |
| Font Display | Syne 800 | Headings |
| Font Body | Manrope 400/600 | Body text |

---

## 📁 Project Structure

```
cartly/
└── index.html        ← Complete single-file app (HTML + CSS + JS)
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/karthikeyanetha1/cartly.git

# Open directly in browser
open index.html
# or just double-click index.html — no build step needed
```

---

## 📬 Contact Form Setup

The contact form uses **EmailJS** — already configured:

```javascript
emailjs.init("3tdUNyiRYlYZmRys7");    // Public key
emailjs.send("service_pwkfbys", "template_clvsbvr", { ... });
```

Submissions go directly to `karthikeyanetha7@gmail.com` — no backend required.

---

## 👨‍💻 Developer

<div align="center">

**Karthik Gurram — CodeWithK**

[![Portfolio](https://img.shields.io/badge/Portfolio-codewithkweb.com-0ea5e9?style=flat-square)](https://codewithkweb.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Hire_Me-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/918688496208)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/karthikeya-gurram-59209726a)
[![Email](https://img.shields.io/badge/Email-karthikeyanetha7@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:karthikeyanetha7@gmail.com)

*Need a custom e-commerce site? [Let's build it together →](https://wa.me/918688496208)*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,12,0&height=80&section=footer" width="100%"/>

</div>
