# 📈 SmartTrendRider v2.0  
**Ride the Trend. Enter on Pullback. Control the Risk.**

> Indikator MetaTrader 5 berbasis *trend-following pullback strategy* dengan konfirmasi multi-layer dan manajemen risiko terstruktur.

---

## 🔍 Overview

**SmartTrendRider v2.0** adalah indikator **MT5 (MQL5)** yang dirancang untuk menangkap **entry presisi pada pullback** di market yang sedang *strong trending*.

Indikator ini menggabungkan:
- **Multi-EMA trend structure**
- **Higher Timeframe bias**
- **ADX momentum filter**
- **Fibonacci + EMA pullback zone**
- **Reversal candlestick confirmation**
- **RSI & Volume validation**
- **Projected TP/SL berbasis risk–reward**

Semua dikemas dalam **dashboard profesional real-time** untuk keputusan trading yang objektif dan disiplin.

---

## 🧠 Trading Philosophy

> **“Ride the Trend, Enter on Pullback, with Tight Risk Management.”**

SmartTrendRider **tidak mengejar breakout** dan **tidak scalping**.  
Fokus utama adalah:
- Trading **searah trend utama**
- Masuk saat **retracement sehat**
- Exit terukur dengan **risk yang terkontrol**

---

## ✨ Key Features

### 🔥 Trend Detection (Multi-Layer)
- **EMA 20 / 50** → Trading Trend
- **EMA 200 Higher Timeframe (default H4)** → Primary Trend
- **ADX Filter** → Validasi kekuatan trend

---

### 🎯 Smart Pullback Zone
- EMA Pullback Zone (EMA 20–50)
- Fibonacci Retracement:
  - 38.2%
  - 50.0%
  - 61.8%
- Swing High / Low otomatis
- Status pullback:
  - Starting
  - In Progress
  - At Zone

---

### 📌 Entry Confirmation System
Sinyal hanya muncul jika memenuhi konfluensi berikut:

✔ Primary Trend searah  
✔ Trading Trend valid + ADX > threshold  
✔ Harga berada di Pullback Zone  
✔ Reversal Candlestick (Hammer, Engulfing, Pin Bar, Strong Bar)  
✔ RSI valid (40 / 60 logic)  
✔ Volume spike (≥ % dari rata-rata)

---

### 📊 Signal Quality Engine
Setiap sinyal diberi **rating kualitas**:
- ★ Low
- ★★ Medium
- ★★★ High

Berdasarkan jumlah konfluensi (maks. 6).

---

### 🛡️ Risk Management Built-In
- Auto Stop Loss:
  - Swing High / Low
  - Pullback Zone + buffer
- Multi Target TP:
  - TP1 (1R)
  - TP2 (2R)
  - TP3 (3R)
- SL & TP divisualisasikan di chart
- Cocok untuk discretionary + execution manual / EA

---

### 🖥️ Advanced Trading Dashboard
Dashboard real-time menampilkan:
- Market Status (Trend, ADX, Momentum)
- Pullback Monitor
- RSI & Volume state
- Confirmation checklist
- Trade readiness status
- Projected Entry, SL, TP
- Estimated signal quality

---

## ⚙️ Input Parameters Overview

### Trend Settings
- EMA Fast / Medium / Slow
- ADX period & threshold
- Higher Timeframe bias

### Pullback Settings
- EMA Pullback
- Fibonacci Retracement
- Swing lookback control

### Entry Triggers
- RSI confirmation
- Volume threshold
- Reversal candle requirement

### Risk Management
- Auto TP / SL
- Risk–Reward ratio (TP1–TP3)
- SL buffer (pips)

### Display & Alerts
- Dashboard toggle
- Pullback zones
- Trend background
- Alert, Push, Email

---

## 🧪 Recommended Usage

- **Timeframe:** M15 – H1 (optimal), H4 untuk swing
- **Market:** Forex, XAUUSD, Indices
- **Market Type:** Trending market
- **Style:** Trend-following pullback strategy

> ⚠️ Tidak disarankan untuk market ranging / low volatility.

---

## 📌 Installation

1. Copy `SmartTrendRider.mq5`
2. Paste ke folder:MQL5/Indicators/
3. Restart MetaTrader 5
4. Attach ke chart
5. Sesuaikan parameter sesuai gaya trading

---

## 🛡️ Disclaimer

Indikator ini adalah **alat bantu analisis**, bukan jaminan profit.  
Gunakan manajemen risiko yang disiplin dan lakukan backtest sebelum live trading.

---

## 👨‍💻 Author & Credits

**M4DI~UciH4**  
🔗 GitHub: https://github.com/RizkyEvory  

© 2025 — All Rights Reserved

---

## ⭐ Support & Contribution

Jika indikator ini membantu Anda:
- ⭐ Star repository ini
- 🍴 Fork untuk pengembangan lanjutan
- 💬 Kirim feedback & improvement ideas

---

**Trade with the trend.  
Wait for the pullback.  
Execute with confidence.**
