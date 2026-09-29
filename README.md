# 🏁 Druglane — Pit Lane Dealer

> **The high-stakes motorsport trading & racing strategy game.**  
> Blending the addictive buy-low / sell-high arbitrage economics of *Drug Wars* with the engineering, setup, and race management of *Motorsport Manager*.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / Vanilla JS](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-blue)](index.html)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](#)

---

## 🎮 Play Online / Quick Start

No installation or build steps required. The entire game is a self-contained, high-performance single-page web app.

- **Option 1**: Open [`index.html`](index.html) or [`pit_lane_dealer/index.html`](pit_lane_dealer/index.html) directly in any modern browser.
- **Option 2 (Local Server)**:
  ```bash
  # Python 3
  python -m http.server 8000
  # Or Node.js
  npx serve .
  ```
  Visit `http://localhost:8000`

---

## 🏎️ Gameplay Overview

In **Druglane**, you are an independent racing syndicate manager navigating the cutthroat international paddock. You travel across global motorsport hubs, exploiting local supply gluts and component shortages, outfitting your prototype race machines, entering cutthroat racing events, managing team finances, and dodging shady loan sharks and FIA compliance raids.

### Core Loops

1. **Global Parts Arbitrage (Drug Wars Mechanics)**:
   - Travel between **16 international racing hubs** across Europe, Asia, the Americas, and Australasia.
   - Buy engine blocks, turbochargers, aero kits, telemetry rigs, and race compounds cheap where factories have oversupply.
   - Transport them to venues facing acute shortages or pre-race demand spikes to pocket massive arbitrage margins.
   - Dynamic market events: supplier strikes, regulation changes, factory fires, and rival team bankruptcies.

2. **Race Craft & Engineering (Motorsport Manager Mechanics)**:
   - Assemble and tune your car across 8 component categories: **Engine, Aero, Suspension, Brakes, Electronics, Tyres, Fuel Systems, and Gearboxes**.
   - Balance **Speed**, **Reliability**, and **Aero Efficiency** stats.
   - Enter **32 high-octane races** spanning Formula, 24H Endurance, Desert & Forest Rallies, GT Cups, Touring, and Drag events.
   - Reliability matters: pushing worn parts risks devastating DNF (Did Not Finish) retirements and chassis damage!

3. **High-Risk Finance & Black Markets**:
   - Manage cash flow and weekly action points (5 AP / week).
   - Leverage capital from 3 loan tiers:
     - **Sport Finance Corp**: Low interest, institutional safety.
     - **Angel Syndicate**: Mid interest, equity expectations.
     - **The Consortium**: High-roller loan sharks. Fall 2 payments behind and they'll raid your paddock warehouse.
   - **Grey Market Access**: Win your first race to unlock contraband prototype parts with game-changing stats—if you can dodge FIA scrutineering checks!

---

## 🌍 World Hubs & Specialities

| City | Country | Market Speciality & Hub Profile |
|---|---|---|
| **Portimão** | 🇵🇹 Portugal | WRC Suspensions & Rally Tyres discounted (starting hub) |
| **Nürburgring** | 🇩🇪 Germany | Precision Engines & Endurance Gearboxes cheap; home of the 24H Enduro |
| **Silverstone** | 🏴󠁧󠁢󠁥󠁮󠁧󠁿 England | High-Downforce Aero, Carbon Tubs & Electronics Hub |
| **Sydney / Bathurst** | 🇦🇺 Australia | V8 Supercar Gearboxes, Cooling & Heavy-Duty Components |
| **Monaco** | 🇲🇨 Monaco | Ultra-luxury paddock, highest sale prices in the world |
| **Monza** | 🇮🇹 Italy | Temple of Speed: High-flow V10s and Low-drag wings |
| **Suzuka** | 🇯🇵 Japan | Advanced Hybrid Turbos and ECU telemetry |
| **Spa-Francorchamps**| 🇧🇪 Belgium | Wet compound tyres and dynamic suspensions |
| **Le Mans** | 🇫🇷 France | Hypercar hybrid battery packs and endurance lighting |
| **Indianapolis** | 🇺🇸 USA | Turbo oval kits and sequential gearboxes |
| **Interlagos** | 🇧🇷 Brazil | Atmospheric engines and mechanical grip packages |
| **Bahrain** | 🇧🇭 Bahrain | Sand-filtration cooling systems and brake ducts |
| **Singapore** | 🇸🇬 Singapore | High-downforce street aero and night telemetry |
| **Austin** | 🇺🇸 USA | Carbon diffusers and telemetry telemetry rigs |
| **Montreal** | 🇨🇦 Canada | Hard-braking pads and heavy-cooling radiators |
| **Melbourne** | 🇦🇺 Australia | Opening round specs and test spares |

---

## 🛠️ Tech Stack

- **Pure Vanilla HTML5 / CSS3 / JavaScript (ES6+)**
- **Modern Responsive UI**: Dark glassmorphic design, responsive layouts, micro-animations, and dynamic data tickers.
- **Audio & SFX Synthesizer**: Built-in Web Audio API synthesizers for race revs, market ticks, and UI feedback without external audio assets.
- **Zero Build Tools**: No npm install, no bundlers, zero external npm bloat.

---

## 📜 License

MIT License. Open source for motorsport and strategy gaming fans worldwide!
