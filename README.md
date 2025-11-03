# VinayakTrader — Live API version

This version includes server-side API routes to proxy Yahoo Finance and NSE endpoints. Deploy on Vercel (upload zip) or run locally.

Run locally:

```
npm install
npm run dev
```

Notes: NSE endpoints may block requests; the server proxy attempts to set browser-like headers. Replace or add paid data sources for robust production use.
