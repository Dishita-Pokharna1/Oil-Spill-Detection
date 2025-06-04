# 🌊 Oil Spill Detection System — Spot. Alert. Act.
![Home Page 1](./Screenshot%202025-06-05%20014811.png)

![Home Page 2](./Screenshot%202025-06-05%20014817.png)



> Real-time oil spill detection from satellite images using image processing + ML for a cleaner planet 🌍  
> 🚨 One pixel at a time, we're fighting the mess before it spreads.


---

## 🔍 Overview

Oil spills are one of the most destructive marine disasters — harming ecosystems, threatening wildlife, and costing millions.  
Traditional detection methods are often **delayed, expensive, or inefficient**.

**Our Solution?**  
A real-time web platform that detects oil spills from satellite imagery using RGB-based analysis and Machine Learning. The system immediately **alerts authorities**, visualizes affected areas, and integrates environmental forecasting for next-level decision-making.
![Dashboard](./Screenshot%202025-06-05%20014827.png)
![Vessels Page](./Screenshot%202025-06-05%20014835.png)

---

## 🌐 Live Demo

🎯 Check it out here → [Oil Spill Detection Platform](https://kzmo9ire5sbeaberct9w.lite.vusercontent.net/)  
*(P.S. Works best on desktop)*

---

## 💡 Features

- 🛰️ **Satellite Image Analysis**  
  Analyze 16×16 satellite images for oil-like anomalies using RGB difference thresholds.

- 🤖 **ML-Based Anomaly Detection**  
  Improve accuracy using machine learning models trained on image data.

- 📡 **Real-Time Alerts**  
  Instant alerts sent out if a spill is detected — no delays.

- 📊 **Interactive Dashboard**  
  See affected zones, logs, and stats in a sleek interface.

- 🌦️ **Weather & Impact Prediction**  
  Combines weather APIs to assess spread potential.

- 📚 **Historical Data Comparison**  
  Track recurring regions and compare historical spill patterns.
  
![Spill Incidents](./Screenshot%202025-06-05%20014842.png)
![Alerts Page](./Screenshot%202025-06-05%20014855.png)

---

## ⚙️ Tech Stack

| Layer     | Tools                            |
|-----------|----------------------------------|
| Frontend  | React.js, Tailwind CSS           |
| Backend   | Node.js, Express.js              |
| ML/Detection | Python, OpenCV, scikit-learn  |
| Hosting   | Firebase (demo), AWS/GCP ready   |
| APIs      | OpenWeatherMap, Custom REST APIs |

---

## 🧠 How It Works!
![Final Section](./Screenshot%202025-06-05%20015420.png)






Detection Logic
Compares image’s pixel data using RGB difference threshold.

Threshold: ΔRGB > 1 ➝ potential anomaly.

ML model trained on small annotated image samples fine-tunes the accuracy.


## 🚀 Installation & Setup


### Backend
```bash
cd backend
npm install
npm start
```


###Frontend
```bash

cd frontend
npm install
npm run dev
```

Then open your browser at http://localhost:3000 — or even better, use the live hosted link if available.

🖼️ Sample Input
Upload a 16×16 satellite image.

📈 Future Scope:

->🌍 Full-scale map integration with spill zones

->📲 Mobile alerts for field teams

->🧠 Deep learning models for improved precision

->📡 Real-time satellite feed ingestion

->🪪 Blockchain for tamper-proof spill records


📜 License
MIT License — use it, remix it, improve it.


![Support Page](./Screenshot%202025-06-05%20014905.png)



