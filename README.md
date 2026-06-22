# ⚡ Anutung Electric

**AI-powered electricity bill tracker, simulator, and saving advisor for Thai households.**

A complete, single-file web app — no build, no server, no installation. Just open `index.html`.

🔗 **Live demo:** https://crackdiwa.github.io/anutung-electric/

---

## ✨ Features

| Feature | Details |
|---|---|
| **Landing page** | Hero with 3D scene, stats, feature grid, how-it-works |
| **Dashboard** | Metric cards + trend / risk / breakdown charts (Chart.js) |
| **Bill Analyzer** | Upload a bill photo/PDF + enter the numbers → smart diagnosis of why it's high, likely causes, comparison chart, and savings actions |
| **Appliance Manager** | Add / edit / remove appliances with live kWh + cost preview |
| **Bill Simulator** | Simulate your bill against real MEA/PEA tiered tariffs, Ft, service fee, VAT |
| **SmartVolt** | Lifestyle questionnaire + profiles + **one-click AI deep analysis** (no chatbot needed) with prioritized, baht-quantified recommendations |
| **Ecobot** | Built-in energy advisor chat |
| **Community** | Anonymous tips feed |
| **Bilingual** | Full English / Thai (ไทย) with Plus Jakarta Sans + Kanit fonts |
| **Dark mode** | Full theme toggle, persisted |
| **Responsive** | Desktop + mobile (bottom tab bar on phones) |
| **Persistent** | Saves to `localStorage` |

---

## 🚀 Run locally

No tooling required — it's one self-contained file:

```bash
# just open it
start index.html        # Windows
open index.html         # macOS

# or serve it
python -m http.server 8088   # then visit http://localhost:8088
```

---

## 🧮 How the numbers work

```
kWh   = (Watts × Hours/day × 30 × Quantity) / 1000
Bill  = tiered base rate + Ft + service fee + VAT   (MEA/PEA residential)
Annual = Monthly bill × 12
```

The "AI" analysis is a built-in rule engine — it reads your usage, tariff, appliance
mix, and lifestyle answers to produce a diagnosis and ranked savings plan entirely
in the browser. No API key, no data leaves your device.

---

## 🛠️ Built with

- **HTML5 + vanilla JavaScript** — zero frameworks, single file
- **Tailwind CSS** (CDN) — utility styling + custom navy theme
- **Chart.js 4** — trend, risk, breakdown, and comparison charts
- **Lucide** — icons
- **Spline** — 3D hero scene
- **Google Fonts** — Plus Jakarta Sans (EN) + Kanit (TH)

---

Built for a school innovation project. ⚡
