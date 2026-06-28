# Globle-phone
# One Smartphone, See Through the Global Supply Chain

An interactive H5 page that reveals the global industrial chain behind a single smartphone — from mineral mining to final assembly, spanning 30–35 countries across the world.

**Live Demo:** [https://tina236.github.io/Globle-phone/global-supply-chain.html](https://tina236.github.io/Globle-phone/global-supply-chain.html)

---

## Pages

| Page | Content |
|------|---------|
| Cover | Opening scene with animated smartphone |
| Phone Teardown | Tap parts (chip / rare earth / screen / camera / body) to explore origins |
| Global Supply Chain Map | Visualizes manufacturing centers across China, Vietnam, India |
| Production Timeline | Step through the full value chain: R&D → Components → Assembly → Global Sales |
| Closing | Key insights on global division of labor |

## Tech

- Pure HTML/CSS/JS, single-file (~1.3MB, SVG embedded as Base64)
- No framework, no build step
- Mobile-first, scroll-snap based navigation

## Data Sources

Counterpoint, IDC, Digitimes, CAICT, UN Comtrade, and public supply chain disclosures by Apple, Samsung and other enterprises.

## Local Dev

Open `global-supply-chain.html` directly in a browser. No server required.

```bash
# Or with a simple server
npx serve .
```
