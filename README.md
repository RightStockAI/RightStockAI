# RightStockAI

AI-powered stock market analysis and prediction platform for Indian stock markets (NSE, BSE, NIFTY 50, and SENSEX).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-15-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)

🟢 **Live App:** [www.rightstockai.com](https://www.rightstockai.com)

---

## 📖 About

RightStockAI is a comprehensive stock market analysis platform designed specifically for Indian investors and traders. It combines advanced AI/ML models with traditional technical and fundamental analysis to provide accurate stock predictions, portfolio insights, and real-time market data.

### Why RightStockAI?

- 🇮🇳 **India-focused:** Specialized for NSE, BSE, NIFTY 50, and SENSEX
- 🤖 **AI-powered predictions:** Machine learning models trained on historical market data
- 📊 **Comprehensive analysis:** Technical indicators, fundamental ratios, and sentiment analysis
- 💼 **Portfolio management:** Track and analyze your investment portfolio
- ⚡ **Real-time data:** Live stock prices, news, and market updates
- 📱 **Responsive design:** Works seamlessly on desktop, tablet, and mobile

---

## ✨ Features

### 🎯 Stock Analysis
- **Traditional Analysis:** 100+ technical indicators including RSI, MACD, Bollinger Bands, Moving Averages
- **AI Predictions:** Machine learning models for price prediction and trend forecasting
- **Fundamental Analysis:** P/E ratio, EPS, ROE, debt-to-equity, and more
- **Risk Metrics:** Sharpe ratio, volatility, maximum drawdown analysis
- **Sector Analysis:** Compare stocks within industry sectors
- **Historical Data:** Access years of historical price data

### 💼 Portfolio Management
- **Multi-portfolio support:** Create and manage multiple investment portfolios
- **Performance tracking:** Real-time portfolio value and P&L calculations
- **Holdings import:** Upload holdings from CSV or Excel files
- **Portfolio analytics:** Risk assessment, diversification metrics, sector allocation
- **Benchmark comparison:** Compare portfolio performance against NIFTY 50 and SENSEX

### 📈 Market Data
- **Real-time quotes:** Live stock prices from NSE and BSE
- **Intraday charts:** Minute-by-minute price movements
- **Market screener:** Filter stocks based on custom criteria
- **Top gainers/losers:** Daily market movers and trending stocks
- **Sector performance:** Track sector-wise market movements
- **Market indices:** NIFTY 50, NIFTY Bank, SENSEX, and more

### 🔔 Alerts & Notifications
- **Price alerts:** Get notified when stocks hit target prices
- **Portfolio alerts:** Updates on significant portfolio changes
- **News alerts:** Breaking news affecting your watchlist
- **Email notifications:** Daily market summaries and analysis reports

---

## 🛠️ Tech Stack

### Frontend
- **Framework:** Next.js 15 with React Server Components
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Charts:** Recharts, TradingView widgets
- **State Management:** React Context + hooks
- **Authentication:** Better-Auth

### Backend & Infrastructure
- **Backend:** Modern Python-based REST API
- **Database:** PostgreSQL with Redis caching
- **Real-time Processing:** Async task queue for heavy analysis
- **Data Sources:** Multiple financial APIs (NSE, BSE, Yahoo Finance)
- **Hosting:** Vercel (frontend), Cloud VPS (backend)

### AI/ML
- **Analysis Libraries:** Advanced statistical and ML models
- **Data Processing:** Python-based financial data pipelines
- **Prediction Models:** Ensemble learning algorithms

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm
- A modern web browser

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/rightstockai.git
cd rightstockai

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the app.

### Environment Variables

```bash
# App
NEXT_PUBLIC_APP_URL=http://localhost:3000
NEXT_PUBLIC_API_URL=https://api.rightstockai.com

# Authentication
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key

# Database (for local development)
DATABASE_URL=postgresql://user:password@localhost:5432/rightstockai
```

---

## 📁 Project Structure

```
rightstockai/
├── app/                       # Next.js App Router
│   ├── (auth)/               # Authentication pages
│   ├── (dashboard)/          # Main application
│   ├── api/                  # API routes (proxy layer)
│   └── layout.tsx            # Root layout
├── components/               # React components
│   ├── ui/                   # UI primitives
│   ├── charts/               # Chart components
│   ├── analysis/             # Analysis widgets
│   └── portfolio/            # Portfolio components
├── lib/                      # Utilities
├── hooks/                    # Custom hooks
├── types/                    # TypeScript types
└── public/                   # Static assets
```

---

## 📊 Performance

- ⚡ **First Contentful Paint:** < 1.2s
- 🎯 **Time to Interactive:** < 2.5s
- 📱 **Lighthouse Mobile Score:** 90+
- 🖥️ **Lighthouse Desktop Score:** 95+

---

## 🔒 Security

- 🔐 Secure authentication with JWT tokens
- 🛡️ Rate limiting on all endpoints
- ✅ Input validation and sanitization
- 🌐 CORS protection
- 🔒 HTTPS enforced in production

---

## 🤝 Contributing

This repository showcases the frontend architecture and UI implementation. Contributions are welcome for:

- UI/UX improvements
- New chart types or visualizations
- Documentation enhancements
- Bug fixes

Please open an issue first to discuss major changes.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

- 🌐 **Website:** [www.rightstockai.com](https://www.rightstockai.com)
- 📧 **Email:** hello@rightstockai.com

---

## ⚠️ Disclaimer

**Investment Risk Warning:** Stock market investments are subject to market risks. RightStockAI provides analysis and predictions for informational purposes only and should not be considered financial advice. Always conduct your own research and consult with a qualified financial advisor before making investment decisions.

**Data Accuracy:** While we strive for accuracy, market data may be delayed. Always verify critical information from official sources.

---

## 📸 Screenshots

### Dashboard
![Dashboard](./screenshots/dashboard.png)

### Stock Analysis
![Analysis](./screenshots/analysis.png)

### Portfolio Management
![Portfolio](./screenshots/portfolio.png)

---

<p align="center">
  <sub>Built with ❤️ for Indian investors and traders</sub>
</p>

<p align="center">
  <sub>This repository showcases the frontend implementation. The production application includes additional backend features and proprietary algorithms.</sub>
</p>

***
