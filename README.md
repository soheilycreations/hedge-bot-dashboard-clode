# 🤖 Dual-Barrier Hedge Bot Dashboard

Live trading dashboard for Deriv Volatility 100 (1s) Index.

## 🚀 Deploy on Vercel

1. Upload this folder to GitHub
2. Go to vercel.com → Import Project
3. Select your GitHub repo
4. Click Deploy

## 🔌 How to Use

1. Open the deployed URL
2. Get API Token from: app.deriv.com → Security & Safety → API Token
3. Enable **Trade** scope
4. Paste token in dashboard → Click Connect
5. Click ▶ Start Bot

## ⚙️ Strategy

- Asset: Volatility 100 (1s)
- Filter: Bollinger Bands (20, 2)
- Dual contracts: Higher (+0.6) + Lower (-0.6)
- Stake: $0.50/side | Martingale: 2.1x
- Stop Loss: $4.00 | Take Profit: $2.00
