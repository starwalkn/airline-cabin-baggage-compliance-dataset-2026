# Airline Cabin Baggage Compliance & Sizer Cage Dataset (2026 Edition)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Web Simulator](https://img.shields.io/badge/Interactive_3D_Tool-FlightBag_3D-blue.svg)](https://novafortixlab.com/flightbag/)
[![Status](https://img.shields.io/badge/Updated-2026_Rules-brightgreen.svg)]()

A clean, open-source JSON and Markdown database tracking carry-on luggage dimensions, personal item limits, sizer box dimensions, weight thresholds, and airport gate fees across 40+ international airlines.

👉 **Interactive Online 3D Sizer Simulator**: [novafortixlab.com/flightbag/](https://novafortixlab.com/flightbag/)

---

## 📊 Global Airline Compliance Matrix

| Airline | Personal Item (Underseat) | Carry-On Dimensions (Wheels included) | Max Weight | Gate Fee Risk | Sizer Strictness |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Ryanair** | 40 x 20 x 25 cm | `55 x 40 x 20 cm` | 10 kg | €70.00 | Extreme |
| **easyJet** | 45 x 36 x 20 cm | `56 x 45 x 25 cm` | 15 kg | £48.00 | High |
| **Scoot** | 40 x 30 x 10 cm | `54 x 38 x 23 cm` | 10 kg (Combined) | $50.00 | High |
| **AirAsia** | 40 x 30 x 10 cm | `56 x 36 x 23 cm` | 7 kg (Combined) | RM 200 | Extreme |
| **Delta Air Lines** | Fit under seat | `56 x 35 x 23 cm` | No weight limit | $0 (Free gate check) | Moderate |
| **United Airlines** | 43 x 25 x 22 cm | `56 x 35 x 22 cm` | No weight limit | $25.00 + bag fee | Moderate |
| **American Airlines** | 45 x 35 x 20 cm | `56 x 36 x 23 cm` | No weight limit | $0 (Free gate check) | Moderate |
| **Southwest Airlines** | 41 x 34 x 20 cm | `61 x 41 x 28 cm` | No limit | None (2 Free Bags) | Low |
| **Emirates** | Briefcase/Handbag | `55 x 38 x 20 cm` | 7 kg | Varies | Moderate |
| **Singapore Airlines** | 40 x 30 x 10 cm | `55 x 40 x 20 cm` | 7 kg | Varies | Moderate |
| **EVA Air (長榮航空)** | 40 x 30 x 10 cm | `56 x 36 x 23 cm` | 7 kg | Varies | Moderate |
| **China Airlines (中華航空)** | 40 x 30 x 10 cm | `56 x 36 x 23 cm` | 7 kg | Varies | Moderate |
| **ANA (全日空)** | Small personal bag | `55 x 40 x 25 cm` | 10 kg | Varies | Moderate |
| **Japan Airlines (JAL)** | Small bag | `55 x 40 x 25 cm` | 10 kg | Varies | Moderate |
| **Peach Aviation** | Combined | `50 x 40 x 25 cm` | 7 kg (Combined) | ¥3,800 | High |

---

## 🧳 Recommended Verified Compliant Hardware (Amazon)

Tested to slide into major European and Asian budget airline sizer cages without wheel snags:

- [**Samsonite Omni 20" Hardside Spinner Luggage**](https://www.amazon.com/s?k=carry+on+luggage+20+inch+airline+approved+samsonite&tag=novafortix-20) ($119.99, -20% Off): Official 55x40x20cm profile with 360° recessed spinner wheels.
- [**Etekcity Digital Hanging Luggage Scale**](https://www.amazon.com/s?k=digital+hanging+luggage+scale+travel&tag=novafortix-20) ($10.99): Accurate to 0.1 lb / 50g to avoid 7kg budget carrier excess weight penalties.

---

## 💻 Programmatic Usage

```javascript
const airlines = require('./data/airlines.json');
const ryanair = airlines.find(a => a.name === "Ryanair");
console.log(ryanair.carryOn); // "55 x 40 x 20 cm"
```

## 📄 License
MIT License. Maintained by NovaFortix Lab.
