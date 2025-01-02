# 🎯 Location.js

A fun project that tries to locate you by measuring network latencies! 🌍

> ⚠️ The UI is completely bonkers with missiles and explosions (yes, really...), but the interesting part is the latency-based geolocation code that can be reused for more serious projects!

## 🚀 Technical Concept

The script measures latency times to various French servers with known locations (OVH, Orange, Free, etc.). Using these measurements and smart weighting, it can roughly triangulate your position.

It's not perfect, but it's an interesting approach that can be improved! 🤓

## 🎮 Features

- 📍 Network latency-based location detection (the interesting part)
- 🗺️ Display on Leaflet map
- 💾 Data storage in Supabase
- 🎬 Absolutely crazy UI with explosions (don't judge...)

## 🛠️ For Serious Devs

If you want to grab just the useful part, check out the `sendLocation()` function which includes:

- Latency measurement to reference points
- Triangulation weighting system
- Timeout and error handling
- Approximate position calculation

You can totally ignore the rest of the UI and reuse this logic for your own projects!

## 🔧 Installation

1. Clone this madness:

```bash
git clone https://github.com/votre-username/Location.js.git
```

2. Open `index.html` and embrace the chaos 🎆

## 📁 Structure

```
Location.js/
├── index.html          # The main chaos
├── assets/            # Exploding stuff
│   ├── explosion.png  # 💥
│   ├── missile.png    # 🚀
│   ├── meme.mp4       # 😅
│   └── song.mp3       # 🎵
└── README.md          # You are here!
```

## 🔧 Tech Stack

- HTML/CSS/JS (the classics)
- Leaflet.js for mapping
- Supabase for database
- A lot of WTF for the UI

## 💡 Contributing

If you want to improve the geolocation part, your PRs are welcome!
For the UI... well... do whatever you want 😅

## 🌟 Why This Exists

This started as a fun experiment to see if we could locate users without using the Geolocation API. The UI went completely off the rails, but the core concept is actually interesting for:

- Network latency analysis
- Approximate user location without permissions
- Understanding triangulation concepts

## 📜 License

MIT (do whatever you want with it, but don't blame me for the UI)

## 🤔 Known Issues

- Accuracy varies wildly depending on network conditions
- The UI might make your colleagues question your sanity
- Some people might actually like the explosions
