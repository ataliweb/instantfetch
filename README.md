# ⚡ InstantFetch Pro

**The Ultimate Prefetch & Prerender Library**

Zero configuration. Maximum performance. Works everywhere.

A modern, ultra-lightweight navigation acceleration library that intelligently prefetches and prerenders pages before users click — making your website feel instant.

> Drop-in upgrade for `instant.page` — with significantly more control, intelligence, and performance.

---

## 🚀 Why InstantFetch Pro?

Traditional prefetching is **static and naive**.

InstantFetch Pro is **predictive, adaptive, and lifecycle-aware**.

It leverages modern browser APIs to:
- Predict user intent
- Optimize network usage
- Upgrade prefetch → prerender dynamically
- Respect user conditions (data saver, slow networks)

---

## ✨ Features

### 🧠 Smart Prediction Engine
- Mouse velocity tracking
- Hover intent detection
- Touch interaction prediction
- Viewport-based prefetch (Intersection Observer)

### ⚡ Speculation Rules API (Chrome 121+)
- Native browser prerendering
- CSS selector-based document rules
- Automatic batching & optimization

### 🔄 Adaptive Fetch Strategy
- Layered **Prefetch → Prerender upgrade**
- Dynamic eagerness levels:
  - `immediate`
  - `eager`
  - `moderate`
  - `conservative`

### 🌐 Network Awareness
- Uses Network Information API:
  - `saveData`
  - `effectiveType`
  - `downlink`
  - `rtt`
- Automatically reduces aggressiveness on slow connections

### 🔁 Lifecycle & Cache Awareness
- BFCache support (`pageshow` / `pagehide`)
- Page Lifecycle API:
  - `visibilitychange`
  - `freeze` / `resume`
- Navigation Timing feedback loop

### 📦 Performance Optimization
- Request queue with rate limiting
- Priority Hints (`fetchpriority`)
- Speculation rules batching
- No-Vary-Search support

### 🔌 Extensibility
- Optional Service Worker integration
- Cross-origin prefetch (safe mode)

### 🛡️ Privacy & Safety
- No tracking
- GDPR-friendly
- Analytics-safe (`document.prerendering` aware)

### 🧩 Compatibility
- Works in all modern browsers
- Graceful fallback for older browsers
- Zero dependencies
- ~4KB gzipped

---

## 📦 Installation

### Option 1 — CDN
```html
<script src="https://cdn.jsdelivr.net/gh/ataliweb/instantfetch@main/instantfetch.min.js"></script>
