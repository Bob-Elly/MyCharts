# MyCharts

A minimalist, high-performance web-based charting platform and TradingView alternative built for PC and mobile.

![MyCharts Logo](logo.svg)

- **Multi-Exchange Data Engine**:
  - **Gate.io (Default)**: Global, unrestricted crypto feeds (REST + WebSocket) that work reliably worldwide without DNS or ISP blocks.
  - **Binance**: Full spot crypto feeds with automatic failover to Gate.io if Binance is restricted by your local network.
  - **Twelve Data**: Forex & international markets (works in demo mode for `EUR/USD`, or add your free key in ⚙ Settings).
- **Live Streaming**: Real-time candle updates over WebSockets with automatic reconnection.
- **Bar Replay**: Replay historical price action candle-by-candle at configurable speeds.
- **Fair Value Gaps (FVG)**: Detection and visualization of bullish/bearish imbalances with mitigation tracking.
- **Drawing Tools**: Trend lines, horizontal lines, vertical lines, rectangles, polylines, and long/short risk-reward calculators with touch hitboxes.
- **Watchlists & Custom Timeframes**: Save multiple watchlists with 24h ticker updates and custom timeframe support (e.g. `7m`, `3h`, `2d`).
- **PWA (Progressive Web App)**: Installable on iOS Safari and Android Chrome as a full-screen, standalone app.

## Live Access (GitHub Pages)

**[https://bob-elly.github.io/MyCharts/](https://bob-elly.github.io/MyCharts/)**

### Mobile Installation (PWA)
1. Open the GitHub Pages link on your mobile browser (Safari on iOS or Chrome on Android).
2. Tap **Share** (iOS) or the three-dot menu (Android).
3. Select **"Add to Home Screen"** or **"Install App"**.

### Running Locally on PC
Simply open `index.html` or `mycharts.html` directly in any modern web browser.
