# 🛰️ LUMIA TEAM // NASA SPACE APPS CHALLENGE 2026

<div align="center">

[![NASA Space Apps Challenge 2026](https://img.shields.io/badge/NASA%20Space%20Apps-Challenge%202026-orange?style=for-the-badge&logo=nasa)](https://www.spaceappschallenge.org/)
[![Mission Status](https://img.shields.io/badge/Mission%20Status-Operational-brightgreen?style=for-the-badge)](https://marsview.vercel.app)
[![Production URL](https://img.shields.io/badge/Live%20App-marsview.vercel.app-blue?style=for-the-badge&logo=vercel)](https://marsview.vercel.app)
[![Pitch Video](https://img.shields.io/badge/Pitch%20Video-Full%20HD%20(29s)-red?style=for-the-badge&logo=youtube)](https://marsview.vercel.app/video/marsview-pitch.mp4)

```text
========================================================================================
 MISSION STATUS : DEPLOYED & OPERATIONAL // READY FOR EVALUATION
 CHALLENGE      : NASA INTERNATIONAL SPACE APPS CHALLENGE 2026
 LOCATION       : UBERLÂNDIA, MG — BRAZIL
 REPOSITORIES   : OPEN ACCESS FOR JUDGING
========================================================================================
```

</div>

---

## 🌌 Flagship Project: MarsView

**MarsView** is Team Lumia's official submission for the NASA Space Apps Challenge 2026. An interactive planetary cartography, surface telemetry, and rover navigation suite built directly on top of real scientific datasets from NASA, ESA, and Freie Universität Berlin.

### 🔗 Quick Access & Deliverables

- 🌐 **Live Web Application:** [https://marsview.vercel.app](https://marsview.vercel.app)
- 🚀 **3D Jezero Exploration Dashboard:** [https://marsview.vercel.app/dashboard/](https://marsview.vercel.app/dashboard/)
- 🎬 **Official Pitch Video (29s Full HD):** [https://marsview.vercel.app/video/marsview-pitch.mp4](https://marsview.vercel.app/video/marsview-pitch.mp4)

---

## 🔭 Core Mission Architecture

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                       LUMIA NASA ECOSYSTEM                                      │
│                                                                                                 │
│   ┌────────────────────────────────┐                 ┌──────────────────────────────────────┐   │
│   │    MarsView (Main Platform)    │                 │       aresnav-mars (Core Engine)     │   │
│   │   github.com/Lumia-NASA/MarsView │                 │   github.com/Lumia-NASA/aresnav-mars │   │
│   │                                │                 │                                      │   │
│   │  • React 19 + Three.js Globe   │                 │  • Fastify REST Microservice         │   │
│   │  • CesiumJS 3D Jezero Crater   │───────────────> │  • Planetary Routing Algorithms      │   │
│   │  • Helmet HUD (Solo Navcam M20)│                 │  • MOLA/HRSC Altimetry Service       │   │
│   │  • ARES Neural Voice (Edge TTS)│                 │  • EvidenceGate Verification         │   │
│   │  • Remotion Pitch Production   │                 │  • 99/99 Unit & E2E Test Suite       │   │
│   └────────────────────────────────┘                 └──────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## 🛰️ Planetary Science Datasets & Provenance

We strictly operate on verified observational data with zero hallucinated figures:

- **MOLA DEM (NASA/JPL):** Global topographic elevation model at 463 meters/pixel.
- **HRSC + MOLA (ESA/DLR/FU Berlin):** Regional 3D terrain elevation model at 200 meters/pixel.
- **HRSC True-Color Mosaic (Freie Universität Berlin):** Scientifically accurate natural Martian surface coloring (CC BY-SA 3.0 IGO).
- **HiRISE & CTX (NASA/JPL/University of Arizona):** High-resolution orbital imaging up to 25 cm/pixel.
- **Perseverance Navcam (NASA/JPL-Caltech):** Authentic raw ground-level surface mosaics for the Helmet HUD.
- **Curiosity / REMS (NASA/CAB):** Daily Martian atmospheric readings (air/ground temperature, pressure, solar cycles).

---

## 👥 Team Lumia

Multidisciplinary engineering, software development, and aerospace design:

- **Lucas Mauril** — *Systems Architecture, Core Logic & Infrastructure* ([@LucasMauril](https://github.com/LucasMauril))
- **Thiago Alves** — *Frontend Engineering & Interactive 3D Cartography* ([@thiagoalves0707](https://github.com/thiagoalves0707))
- **Naldrin** — *Motion Design, Helmet HUD & Pitch Production* ([@Naldrin123](https://github.com/Naldrin123))
- **Gabriel Franzói** — *UI/UX Design, CSS Architecture & Theming*
- **Rafael Manzan** — *Telemetry Integrations & Scientific Data Pipelines*

---

<div align="center">

<sub>TEAM LUMIA // NASA INTERNATIONAL SPACE APPS CHALLENGE 2026 // ALL SYSTEMS NOMINAL</sub>

</div>
