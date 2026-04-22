# 🧃 VBL JuicePOS

**Vital Blend Juices — Point of Sale System**

A professional mobile-first POS system for Vital Blend Juices, built as a Progressive Web App (PWA) with Firebase cloud sync.

---

## ✅ Features

- **Point of Sale** — Search products, add to cart, apply discounts, checkout
- **Bulk / Event Sales** — Flexible pricing for ceremonies and wholesale orders
- **Payment Methods** — Cash (with change calc), Wave Mobile Money, Bank Transfer
- **Receipt Images** — Canvas-rendered receipts shareable via WhatsApp
- **Inventory Management** — Track stock, restock with cost logging
- **Sales History** — Full transaction history, cashier tracking
- **Banking** — Multiple bank accounts, opening balances, deposit tracking
- **Finance / Accounting** — Expenses, cash outs, P&L dashboard
- **User Management** — Admin + Cashier roles with passwords
- **Firebase Cloud Sync** — All data stored in the cloud, works on any device
- **Offline Support** — Falls back to localStorage if offline, syncs when back online
- **PWA** — Installable on Android and iPhone home screen

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create GitHub Repository
1. Go to [github.com](https://github.com) → Sign in
2. Click **New repository**
3. Name it: `vbl-juicepos` (or any name)
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload Files
1. Click **Add file → Upload files**
2. Upload these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source** → select **main** branch → **/ (root)** folder
4. Click **Save**
5. Wait ~2 minutes → your app will be live at:
   `https://YOUR-USERNAME.github.io/vbl-juicepos/`

---

## 📱 Install as App

### Android
1. Open the GitHub Pages URL in **Chrome**
2. Tap the **⋮ menu → Add to Home Screen**
3. Tap **Add** — done! Opens like a native app

### iPhone
1. Open the URL in **Safari** (must be Safari)
2. Tap the **Share button (□↑) → Add to Home Screen**
3. Tap **Add** — done!

---

## 🔑 Default Login

After setup, use whatever credentials you created.

**If you forget your password:**
On the login screen, tap **"Forgot password? Reset to admin/admin"**

---

## 🔥 Firebase

Data is stored in **Firebase Firestore** (project: `vbl-juicebar`).
- Free tier: 1GB storage — enough for ~28 years of sales
- Works across all devices simultaneously
- Falls back to localStorage if internet is unavailable

---

## 📞 Support

Built for Vital Blend Juices, The Gambia 🇬🇲
