
# Mobile Stationery and Accessories Website

## 📁 Project Structure
- `/frontend` - Contains all HTML, CSS, JS, and images.
- `/backend` - Node.js + Express backend for login/signup, OTP, orders.
- `.env.example` - Template for your private config.
- `README.md` - You are here.

## ✍️ How to Edit
- Update your product info in `/frontend/products.json` or `/frontend/index.html`
- Add your QR code in `/frontend/images/qr.png`
- Secure your backend in `/backend/config/payment.js`
- Add real credentials in `.env` file (copy `.env.example` to `.env`)

## 💳 Payment Methods Supported
- UPI
- QR code (editable image)
- Debit/Credit Cards (Stripe/Razorpay test ID)
- Wallets, COD, Bank Transfer, Crypto (demo)
- BNPL (placeholder)

## 🚀 Deployment
### Option 1: [Render](https://render.com)
- Login > New Web Service > Connect GitHub
- Use backend folder as root for Node.js
- Use frontend folder as static site

### Option 2: [Vercel + Render]
- Frontend → Vercel (Static)
- Backend → Render (Node.js API)

### Option 3: Free Domain
1. Visit [freenom.com](https://freenom.com) → register free `.tk`
2. Point DNS to Render/Vercel site (via Cloudflare if needed)

Enjoy editing and launching your site!
