# PA–EMA Spread (Smoothed) v2

**TradingView Pine Script v6** indicator that measures the spread between **price** and a baseline **EMA**, helping traders spot **overextended moves** and potential **reversals**.

![Screenshot](https://github.com/Sianap8/tradingview-pa-ema-spread/blob/main/pa-ema-spread-example.PNG)

---

## 🎯 Purpose
This tool highlights when price deviates too far from its baseline EMA.  
- Large positive spreads → possible **overbought** / exhaustion signals.  
- Large negative spreads → possible **oversold** / mean-reversion opportunities.  

---

## ✨ Features
- Spread calculation in **Percent** or **Points**  
- **Absolute value** mode (ignore sign)  
- 4 smoothing options: **EMA, RMA, SMA, WMA**  
- Configurable **upper/lower thresholds** with shaded band  
- Optional **raw spread** (dotted line) + colored smoothed plot  
- **Alerts** when spread crosses thresholds  

---

## ⚙️ Inputs
- **Baseline EMA Length** (default: 50)  
- **Spread Mode:** Percent / Points  
- **Absolute Value:** On/Off  
- **Smoothing Type & Length**  
- **Upper/Lower Thresholds** (mode-aware)  

---

## 📈 How to Use
1. Open TradingView → **Pine Editor**.  
2. Paste code from `src/PA-EMA-Spread-v2.pine`.  
3. Click **Add to chart**.  
4. Select **Percent** for regime/relative stretch, or **Points** for absolute dislocation.  
5. Tune thresholds based on volatility of your asset.  
6. Enable alerts to get notified when price becomes **overextended**.  

---

## 🔔 Alerts
- **Spread crossed ABOVE upper** → price extended far above EMA  
- **Spread crossed BELOW lower** → price extended far below EMA  



