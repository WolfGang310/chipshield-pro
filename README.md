# 🗫️ ChipShield Pro v4.0

## Semiconductor Supply Chain Intelligence Platform

Real-time monitoring and analysis of the global chip supply chain with live news, risk analysis, and interactive timeline visualization.

---

## ✨ Features

### 📊 Dashboard
- Real-time risk monitoring with animated gauges
- Live news feed with AI-powered search
- Company watchlist with star/favorite functionality
- Quick stats carousel with key metrics
- Risk factor breakdown with visual indicators

### 📅 Interactive Timeline
- 20 major events from 2018-2025
- Auto-play mode for presentations
- Filter by category and year
- Detailed event modals with impact analysis

### 🔍 Command Palette Search (⌘K / Ctrl+K)
- Search events, companies, and glossary terms
- Keyboard navigation
- Quick access to any data

### 📈 Company Comparison
- Side-by-side company analysis
- Risk history sparklines
- Key metrics comparison

### 🎯 What-If Scenario Simulator
- Explore hypothetical scenarios
- See impact on different industries
- Visual risk projections

### 📚 Learn Section
- Beginner-friendly explanations
- Glossary of key terms
- Risk scenario education

---

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ installed
- npm or yarn

### Installation

1. **Extract the project**
   ```bash
   unzip chipshield-pro.zip
   cd chipshield-pro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 📁 Project Structure

```
chipshield-pro/
├── public/
│   └── index.html      # HTML template with Tailwind CDN
├── src/
│   ├── index.js        # React entry point
│   └── App.js          # Main application component
├── package.json        # Dependencies and scripts
└── README.md           # This file
```

---

## 🎨 Design System

### Colors
- **Critical/High Risk**: Red (#ef4444)
- **Elevated Risk**: Orange (#f97316)
- **Moderate Risk**: Yellow (#eab308)
- **Low Risk/Positive**: Green (#22c55e)
- **Interactive**: Blue (#3b82f6)

---

## ⌘️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘K` / `Ctrl+K` | Open search |
| `ESC` | Close modals/search |

---

## 📊 Data Included

- **8 major semiconductor companies** (TSMC, Samsung, Intel, SK Hynix, ASML, Nvidia, SMIC, Micron)
- **20 historical events** (2018-2025)
- **6 event categories** (Policy, Military, Production, Technology, Trade, Financial)
- **4 risk scenarios** (Taiwan invasion, ASML disaster, etc.)

---

## 🔧 Customization

Edit `src/App.js` to customize:
- `timelineEvents` - Add/modify events
- `suppliers` - Update company data
- `scenarios` - Add what-if scenarios
- `glossary` - Expand terminology

---

## 📝 License

MIT License - Feel free to use and modify.

---

Made with ❤️ for understanding the chip supply chain
