# My L2 Portfolio

AI-native full stack developer with a focus on health and wellness, and 15 years of hands-on experience in telecommunications — spanning cable installation, satellite systems, and field management. I bring an operator's mindset to software: building reliable, user-centered applications that work in the real world.

**Stack:** React · TypeScript · Tailwind CSS · Python · SQL

---

## Projects

### [CarbonLens](./carbonlens)

Solar energy producers lack a simple, auditable way to calculate and document the carbon credits their systems generate. Existing tools are either too complex, require specialized software, or lack the transparency needed for third-party verification. There's no simple, self-contained workflow for a facility to go from raw generation data to a verified, exportable carbon credit report aligned with EPA emission standards.

CarbonLens provides a step-by-step browser-based documentation tool that guides users from facility setup to a verified, exportable carbon credit report. It applies EPA eGRID 2023 emission factors to raw generation data and produces a tamper-evident PDF — all client-side with no backend required.

**Key Features**
- Step-by-step guided workflow from facility input to carbon credit report export
- EPA eGRID 2023 emission factor calculations across 27 subregions
- SHA-256 cryptographic hashing for tamper-evident audit trail
- Client-side PDF generation with no backend or data storage required
- CSV generation data import via PapaParse for bulk entry

**Tech Stack**
| Layer | Technologies |
|---|---|
| Frontend | React 18, TypeScript, Vite, Tailwind CSS |
| Libraries | jsPDF, JSZip, PapaParse, lucide-react |
| Security | Web Crypto API (SHA-256) |
| Data | EPA eGRID 2023 Rev 2 (embedded, no external API calls) |

![CarbonLens Screenshot](./assets/carbonlens/screenshot.png)

[View Sample Monitoring Report](./assets/carbonlens/monitoring_report.pdf)

---

### [Letterboxd Replica](./letterboxd-replica)

Deciding what to watch as a couple or group is a frustrating experience — scrolling through individual watchlists, negotiating preferences, and still landing on a film nobody is fully excited about. Letterboxd's existing watchlist is a solo tool with no native way to match overlapping interests between two users.

This project replicates Letterboxd's watchlist feature and extends it with a Roulette mode — a Tinder-style swipe mechanic that cross-references two watchlists and surfaces movies both users want to watch. State persists locally in the browser with no account or backend required.

**Key Features**
- Letterboxd-style watchlist grid with hover interactions (add, remove, mark watched, rate)
- Roulette mode: Tinder-style swipe mechanic to match movies across two watchlists
- TMDB API integration for real movie search and poster data
- localStorage persistence — no signup, works offline after load
- Responsive grid layout (mobile → desktop) with smooth animations

**Tech Stack**
| Layer | Technologies |
|---|---|
| Frontend | React 19, TypeScript, Vite, Tailwind CSS 4 |
| Icons | lucide-react |
| Data | TMDB API |
| Storage | localStorage |

![Watchlist Roulette](./assets/letterboxd-replica/screenshot-1.png)
![Swipe UI](./assets/letterboxd-replica/screenshot-2.png)

---

### [Too Good To Go](./toogoodtogo)
> Placeholder description for Too Good To Go.

---

### [Strava Clone](./strava-clone)
> Placeholder description for Strava Clone.

---

*More projects coming soon.*
