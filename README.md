
# 📊 BIST AI Terminal

> Amazon Chronos + Google Gemini ile Bloomberg Terminal benzeri AI analiz aracı

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red)
![Chronos](https://img.shields.io/badge/Amazon-Chronos-orange)
![Gemini](https://img.shields.io/badge/Google-Gemini%202.5-green)

## 🎯 Ne Yapıyor?

- 📈 **10 BIST hissesi + BTC/ETH** için gerçek zamanlı analiz
- 🔮 **Chronos ile 5 günlük probabilistic forecast** (güven bandı dahil)
- 🚨 **Anomaly Detection** — beklenen bandın dışına çıkan hareketleri tespit eder
- 🤖 **Gemini 2.5 Flash** ile otomatik Türkçe analiz
- 📊 Candlestick + Bollinger Bands + RSI + MACD dashboard

## 🏗️ Mimari

```
Data Layer  →  yfinance + pandas-ta
                      ↓
Analysis    →  Amazon Chronos (forecast + anomaly)
            →  Google Gemini  (narrative)
                      ↓
UI          →  Streamlit (Bloomberg-style dark theme)
```



## ⚠️ Önemli Not

Bu araç **yatırım tavsiyesi değildir**. Chronos'un borsa tahmin performansı
akademik olarak tartışmalıdır. Anomaly detection ve volatilite analizi için
daha güvenilir sonuçlar verir.


*Built with ❤️ using Amazon Chronos + Google Gemini*
