# ⚡ Energy Consumption Insights Dashboard (2018–2024)

An interactive, no-build **data visualization project** showcasing global electricity consumption by sector and region using **Chart.js**.  
Designed with **gradient backgrounds, unusual fonts, and inline annotations**, it demonstrates creativity, data literacy, and front-end engineering skills.

---

## 🔍 Overview

This project visualizes electricity consumption data across sectors and regions in two views:

| Page | Type | Description |
|------|------|--------------|
| **[`index.html`](index.html)** | 📊 Stacked Bar + Dual Axis Line | Yearly energy consumption (Residential, Commercial, Industrial) with total trend line (2018–2024). |
| **[`sector.html`](sector.html)** | 🕸️ Radar Chart | Regional energy distribution across sectors (2024). |

Each chart features a **gradient background**, **quirky fonts (Caveat / Patrick Hand)**, **glassmorphism cards**, and **hand-drawn annotations** marking key global events.

---

## 🎨 Features

- **Stacked Bars + Line Combo** – Dual-axis chart showing total energy vs. sector breakdowns  
- **Radar Chart View** – Long-tail chart comparing regions’ sectoral mix  
- **Unusual Typography** – Handwritten-style fonts for a creative aesthetic  
- **Gradients Everywhere** – Both page and canvas use complementary gradients  
- **Inline Callout Annotations** – COVID-19 dip (2020) and energy price shock (2022)  
- **Glassmorphism UI** – Transparent panels and soft shadows  
- **Responsive Design** – Works on desktop and mobile  
- **PNG Export Buttons** – Download any chart as an image instantly  
- **Cross-page Navigation** – Easy toggle between visualizations  

---

## 📂 Folder Structure

energy-dashboard/
│
├── index.html # Stacked bar + dual-axis total (main page)
├── sector.html # Radar chart comparing regions (secondary page)
│
├── data/
│ ├── energy.csv # Sector-wise yearly energy data
│ └── sector.csv # Regional sectoral distribution (%)
│
├── assets/
│ └── logo.svg # Minimal vector icon for branding
│
└── README.md # This file


---

## 🧩 Technologies Used

- **HTML5**, **CSS3**
- **Chart.js 4.4.6**
- **Google Fonts** (Caveat, Patrick Hand, Inter)
- **Vanilla JS (ES6)** – For parsing CSV and drawing annotations
- **No frameworks or bundlers** – Just open and run

---

## 🚀 How to Run

### Option 1 — Local Preview
```bash
# In project directory
python -m http.server 8080
# Visit http://localhost:8080
