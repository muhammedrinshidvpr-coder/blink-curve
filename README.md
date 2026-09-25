# BlindSight

**Real-time vehicle awareness for blind curves on mountain roads — warning drivers about oncoming traffic before they enter a hairpin bend.**

🔗 **Live:** [blink-curve.vercel.app](https://blink-curve.vercel.app)

---

## The problem

Kerala's ghat roads (Vagamon, Idukki, Munnar, Wayanad) are full of hairpin bends with zero sightline. Narrow single-lane roads shared by trucks, buses and motorcycles, plus fog, make head-on collisions common, and convex mirrors and signboards don't tell a driver whether a vehicle is *actually* coming.

## The solution

BlindSight detects vehicles approaching a curve from the other side and signals drivers in real time. This repository is the **software-first MVP**: the product website and an interactive mobile-app concept used to validate the idea with drivers, investors and road-safety authorities.

**What's in the MVP**
- Landing page — problem, solution, comparison with existing measures, FAQ, waitlist
- **Interactive mobile app mockup** — home, hazard map, live curve alert, navigation and settings screens
- Pages: How it works · Vision · Demo · About · Contact
- Full product docs: [PRD](./docs/PRD.md), [TRD](./docs/TRD.md), [Architecture](./docs/ARCHITECTURE.md), [Design system](./docs/DESIGN_SYSTEM.md), [User personas](./docs/USER_PERSONAS.md), [Competitor analysis](./docs/COMPETITOR_ANALYSIS.md)

## Tech stack

Next.js 15 (App Router) · React 19 · TypeScript · Tailwind CSS · shadcn/ui (Radix) · Framer Motion · Vercel

## Run locally

```bash
npm install
npm run dev      # http://localhost:3000
npm run build
```

> On networks with TLS inspection, `npm run build` uses `NODE_OPTIONS=--use-system-ca` so Next.js can fetch Google Fonts.

## Roadmap

1. ✅ Software MVP (website + app concept)
2. ⏳ Curve-side sensor hardware prototype
3. ⏳ Pilot on a ghat-road curve with local authorities

## Author

Built by [Muhammed Rinshid V P](https://github.com/muhammedrinshidvpr-coder)

## License

[MIT](./LICENSE)
