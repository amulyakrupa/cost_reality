# 🧭 CostReality AI — The Pre-Decision Life Simulator

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Vercel Ready](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<br/>

**"Before you sign the offer, sign the lease, or relocate — simulate your true financial reality."**

</div>

---

## 🌟 Visual Identity & Design Philosophy
CostReality AI is built to be **premium, intelligent, and cinematic**:
* **Deep Obsidian & Slate Dark Palette** (`#06080D` base with glowing cyan `#06B6D4` and emerald `#10B981` accents).
* **Dimensional 3D WebGL Decision Core** powered by Three.js with real-time interactive mouse tracking.
* **Instant Client-Side Simulations** that run 1,000 Monte Carlo stress iterations under 5ms.
* **Student-Friendly Clarity**: Translates complex quantile distributions into simple, actionable numbers in seconds.

---

## 🛡️ Non-Negotiable Core Rule
> **Numbers come from deterministic code and calibrated ML models; words come from the LLM. The AI never invents, hallucinates, or alters a financial figure.**

---

## ✨ Features

1. **♊ Life Decision Twin**: Side-by-side comparison of two futures (e.g., Staying at hometown vs. Relocating for an 8.5 LPA offer in Hyderabad).
2. **🕵️ Hidden Cost Detective**: Surfaces unlisted expenses (security deposits, brokerage fees, moving logistics, society maintenance, surge commuting) using TF-IDF matching.
3. **⚡ Monte Carlo Financial Shock Simulator**: Dynamically tests rent increases (+0–35%), medical emergencies, and income pauses across 1,000 iterations to predict the exact probability of running a monthly deficit.
4. **🎯 Reverse Affordability Solver**: Inverts the mathematical equation to tell you the maximum rent ceiling you can afford or the exact salary you need to negotiate.
5. **🌐 Multilingual Grounded Explainer**: Generates plain-language verdicts in **English, Telugu (తెలుగు), and Hindi (हिंदी)** strictly adhering to computed numbers.
6. **📊 Model Validation & DPDP Act Compliance**: Reports held-out empirical coverage (~81% within p10–p90) and collects zero Personally Identifiable Information (PII).

---

## 🚀 1-Click Deploy to Vercel

### Method 1: Deploy via Vercel Dashboard
1. Push this repository to your GitHub account (instructions below).
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Select your GitHub repository.
4. Framework Preset will be automatically detected as **Vite**.
5. Click **Deploy**! (Build takes ~20 seconds).

### Method 2: Deploy via Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 💻 Local Development

```bash
# Install dependencies
npm install

# Start local development server with hot-reload
npm run dev

# Run production build
npm run build

# Preview production build locally
npm run preview
```

---

## 📂 Project Structure

```
costreality-web/
├── src/
│   ├── components/
│   │   └── ThreeCanvas.tsx    # Dimensional 3D WebGL Decision Core (Three.js)
│   ├── lib/
│   │   └── engine.ts          # Deterministic engine, Quantile ML, Monte Carlo, TF-IDF
│   ├── App.tsx                # Cinematic dashboard with all interactive simulation tabs
│   ├── index.css              # Custom Tailwind CSS dark theme & glowing neon utilities
│   └── main.tsx               # Entry point
├── vercel.json                # Vercel zero-config routing
├── package.json
└── vite.config.ts
```

---

## 📜 Compliance & Data Sources
- **MoSPI HCES 2023–24 (Ministry of Statistics & Programme Implementation)**: Urban consumption baseline.
- **Consumer Price Index (CPI Base 2024)**: Forward inflation baseline.
- **Digital Personal Data Protection (DPDP) Act**: Zero PII collected. No login required.
