# Vizify V0

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Node.js CI](https://github.com/your-org/data-viz-app-v4/actions/workflows/node.js.yml/badge.svg)](https://github.com/your-org/data-viz-app-v4/actions)
[![WASM Build](https://img.shields.io/badge/WASM-Emscripten%203.1-important)](https://emscripten.org)

An offline-first, dependency-free data visualization platform with multi-engine rendering, AI-powered insights, and military-grade security.

![App Screenshot](https://via.placeholder.com/800x400.png?text=Data+Viz+App+V4+Screenshot)

## ✨ Features

- **Multi-Engine Visualization**
  - Chart.js (Canvas), Plotly-Lite (WebGL), D3-Micro (SVG)
  - Unified theme sync across engines
- **Smart Data Processing**
  - WASM-accelerated cleaning/aggregation (1M+ rows/sec)
  - Natural Language Query (NLQ) parsing
- **Zero-Dependency Architecture**
  - Fully embedded libraries (no CDN calls)
  - <15MB initial bundle size
- **Military-Grade Security**
  - Client-side AES-256 encryption
  - Auto-PII redaction and file quarantine
- **Cross-Platform**
  - Web, Android, iOS via Capacitor.js
  - Touch-optimized mobile UI

## 🚀 Quick Start

### Prerequisites
- Node.js 18.x
- Python 3.10+ (for WASM builds)
- Git 2.35+

```bash
# 1. Clone repository
git clone https://github.com/Monem-N/data-visualization-app/
cd data-viz-app-v4

# 2. Install dependencies
npm install

# 3. Build WASM modules (requires Emscripten)
cd src/wasm
make

# 4. Start development server
npm run dev
