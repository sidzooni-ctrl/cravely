# 🍽️ Cravely — Crave More. Waste Less.

> **India's #1 Surplus Food Rescue & NGO Redistribution Platform** — Connecting food lovers with surplus restaurant food at **50% to 70% OFF**, backed by a 1-click **100% Zero-Waste NGO Dispatch Network** for any unsold food.

![Cravely Banner](https://images.unsplash.com/photo-1504674900247-0877df9cc836?w=1200&auto=format&fit=crop&q=80)

---

## 🌟 Key Features

### 1. 🔥 Live Surplus Food Deals & Flash Drops
- Real-time surplus listings from partner restaurants, cafes, and bakeries across Mumbai, Pune, Bengaluru, Delhi & Virar.
- **Dynamic Countdown Timers** showing real-time pickup windows for each deal.
- **Dietary & City Filters**: Filter by Pure Veg 🌱, Non-Veg 🍗, Bakery & Desserts 🍰, and Combos 🥪.

### 2. ⚡ Instant Reservation with Customer Details & UPI Checkout *(NEW)*
- **Customer Verification**: Automatically asks for customer's **Full Name**, **Mobile Number** (for SMS / OTP pickup verification), **Email**, and optional **Pickup Notes**.
- **Smart Auto-Fill**: Remembers customer info in `localStorage` for 1-tap subsequent meal rescues.
- **Pickup Time Slots**: Flexible collection windows (Next 30 Mins, Evening, Late Night).
- **Simulated Instant UPI Payment**: Google Pay, PhonePe, Paytm, and Pay-at-Counter.
- **Customized Pickup Ticket**: Generates instant unique pickup code (`CRV-XXXX`) linked with customer name, phone, item details, and pickup notes with confetti celebration.

### 3. 🤝 100% Zero-Waste NGO Redistribution Network
- **End-of-Day Surplus Connect**: If prepared food is still remaining at restaurants after discounted customer windows close, restaurants can request a volunteer pickup in 1 click.
- **Verified NGO Partnerships**: Integrated with **Robin Hood Army, Feeding India (Zomato), Mumbai Roti Bank, Akshaya Patra**, and local night shelters.
- **Instant Dispatch Tracker**: Generates live volunteer assignment tickets (`NGO-XXXX`) with volunteer ETA and location routing.
- **80G Tax Exemption & CSR Certificates**: Generates digital receipts for restaurants eligible for tax benefits and corporate social responsibility (CSR) compliance.
- **NGO Recipient Onboarding**: Dedicated registration flow for registered charities and food banks.

### 4. 🌍 Eco-Impact & Annual Money Savings Calculator
- Interactive weekly rescue slider showing real-time projected impact:
  - 💰 **Annual ₹ Saved**
  - 🌿 **Kg CO₂ Emissions Prevented**
  - 💧 **Litres of Water Footprint Conserved**
  - 🍽️ **Total Meals Rescued & Donated**

### 5. 🏪 Restaurant Partner Portal & Revenue Estimator
- Dedicated partner onboarding modal with ROI calculator and waste recovery snapshot.
- Zero listing fees with customizable takeaway and donation slots.

### 6. 🎨 Modern Glassmorphic UI & Micro-interactions
- Responsive glassmorphic aesthetic with dark mode toggle & `localStorage` persistence.
- Animated floating canvas particles and live impact stats ticker.
- Toast notification system and floating back-to-top button.

---

## 🔄 How the NGO Surplus Redistribution Works

```mermaid
graph TD
    A[Restaurant Lists Surplus Food] --> B{Sold to Customers at 50-70% OFF?}
    B -->|Yes| C[Customer Enters Name & Phone -> Instant UPI -> Pickup Ticket]
    B -->|No / Unsold at Closing| D[1-Click NGO Dispatch Triggered in Cravely App]
    D --> E[Nearest NGO Volunteer Alerted - Robin Hood Army / Feeding India]
    E --> F[Refrigerated / Rapid Collection from Restaurant Counter]
    F --> G[Direct Distribution to Night Shelters & Orphanages]
    G --> H[Restaurant Receives 80G Tax Exemption Certificate & CSR Badge]
```

---

## 🚀 Quick Start & Local Preview

No heavy frameworks or dependencies needed! Cravely is built with lightweight vanilla modern web standards.

### Option 1: Open Directly in Browser
Simply double-click `index.html` or `cravely.html` to open it in your browser.

### Option 2: Live Server (VS Code / Python / Node)
Using Python:
```bash
python -m http.server 3000
```
Then visit `http://localhost:3000` in your web browser.

---

## 📁 Project Structure

```
cravely/
├── index.html        # Main web app & GitHub Pages entry
├── cravely.html      # Cravely single-page application
└── README.md         # Project documentation & overview
```

---

## 🛠️ Built With

- **HTML5 & Semantic Markup**
- **Modern CSS3**: Glassmorphism, CSS Custom Properties, Flexbox & CSS Grid, Animations
- **Vanilla JavaScript (ES6+)**: Intersection Observer, Event Delegation, LocalStorage, Canvas API
- **Font Awesome 6 & Google Fonts (Poppins)**
- **Canvas Confetti** for reservation and NGO donation celebrations

---

## 🤝 Contributing

Contributions are always welcome! Feel free to open an issue or submit a pull request:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.