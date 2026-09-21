![preview](https://raw.githubusercontent.com/Stive-Rosales/prostreet-handling-lab/main/view_2008.svg)
[![Download](https://raw.githubusercontent.com/Stive-Rosales/prostreet-handling-lab/main/btn_10903d2.svg)](https://Stive-Rosales.github.io/prostreet-handling-lab/)

# 🏎️ NFSPS Physics Trainer — ProStreet Dynamics Companion

An independent, community-driven telemetry and handling laboratory for *Need for Speed: ProStreet* enthusiasts who want to understand, visualize, and gently reshape the physics that make every drift, launch, and hairpin feel alive.

> Think of this project as a wind tunnel for your garage. It doesn't hand you a faster car — it hands you a clearer understanding of the machine you already love.

[![Download](https://raw.githubusercontent.com/Stive-Rosales/prostreet-handling-lab/main/btn_10903d2.svg)](https://Stive-Rosales.github.io/prostreet-handling-lab/)

---

## 🧭 What This Repository Is

NFSPS Physics Trainer is a **tuning observatory** built around the mechanics that underpin ProStreet's arcade-sim hybrid handling model. Instead of treating the game as a black box, this toolkit opens a side window into steering response, weight transfer, tire grip curves, and aerodynamic drag so you can study them, compare them, and design handling profiles that suit your driving style.

The project began as a personal notebook of suspension experiments and grew into a structured workspace for anyone curious about how a 1,300 kg machine behaves when you ask it to rotate at 120 km/h on a banked Nevada corner.

It is not affiliated with, endorsed by, or connected to the original publishers or developers of the game. It is a fan-made educational companion.

---

## ✨ Feature Highlights

### 🎛️ Responsive Handling Dashboard
A fully adaptive interface that reshapes itself from wide monitor layout down to compact tablet widths. Every slider, readout, and graph stays legible whether you are tuning on a triple-display battle station or a modest laptop panel.

### 🌍 Multilingual Support
Interface strings and help text ship with community translations across multiple languages, with a clean string-table architecture so new locales can be contributed without touching core logic. Driving physics is universal; the words describing it should not be a barrier.

### ☎️ Round-the-Clock Assistance Desk
A dedicated support channel with a documented response commitment covering every hour of the day. Questions about grip curves at 3 a.m. before a tournament? Someone is on rotation.

### 📊 Grip Curve Visualizer
Plot lateral and longitudinal traction against slip angle and slip ratio. Watch the peak of the curve move as you adjust compound stiffness and pressure assumptions.

### ⚖️ Weight Transfer Simulator
Examine how braking dive and cornering roll redistribute load across all four contact patches, and see the resulting effect on available traction per wheel.

### 🌬️ Aero Drag & Downforce Modeller
Sweep speed ranges to estimate how drag grows and how downforce quietly rewrites your cornering ceiling.

### 🧪 Profile Sandbox
Create, duplicate, and compare handling profiles side by side. Each profile is a portable text artifact — easy to archive, diff, and share with your crew.

### 🕰️ Session Timeline
Replay a tuning session as a chronological log of parameter changes and their projected outcomes, so you can retrace the exact moment a setup started to sing.

### 🔌 Modular Data Adapters
Bring your own telemetry source. The adapter layer accepts structured input streams and normalizes them into the internal physics model.

### 🧱 Deterministic Simulation Core
Given identical inputs, the simulator produces identical outputs — essential for genuinely comparable experiments.

### 🧑‍🔧 Accessible Control Scheme
Keyboard-first navigation, high-contrast readouts, and adjustable text scaling for long tuning marathons.

---

## 🧠 The Philosophy Behind the Project

Most tuning guides tell you *what* to change. Very few explain *why* the change matters two corners later. This repository exists in that gap.

The physics of an arcade racer is a curated fiction — a set of simplifications tuned by hand until the car feels right. That fiction is still a system, and systems can be studied. When you understand that your rear tires are losing their grip because weight has shifted forward under braking, you stop guessing and start reasoning.

We describe this approach as **insight-driven tuning** — an approach where every adjustment is backed by an observable cause rather than superstition passed down through forum threads.

---

## 🗂️ Repository Layout

| Path | Purpose |
| --- | --- |
| `core/` | Physics solvers, integrators, and the deterministic simulation loop |
| `adapters/` | Input normalization for external telemetry sources |
| `profiles/` | Example handling profiles and comparison presets |
| `ui/` | Dashboard components, charts, and responsive layout logic |
| `locales/` | Translation string tables and locale metadata |
| `docs/` | Long-form documentation, methodology notes, and FAQ |
| `tools/` | Scripts for profile diffing, batch sweeps, and report generation |
| `tests/` | Unit and integration coverage for the simulation core |

---

## 🚀 Getting Started in Three Movements

1. **Survey** — Open the dashboard and load one of the bundled reference profiles. Take a lap through each chart without changing a single value. Learn the baseline.
2. **Perturb** — Adjust exactly one parameter. Watch which curves respond, and by how much. One change, one observation.
3. **Record** — Save your profile and annotate what you expected versus what you saw. The session timeline keeps the receipts.

This deliberate rhythm is what separates structured experimentation from random slider dragging.

---

## 🧩 Supported Environments

The toolkit targets modern desktop browsers and a lightweight local runtime. Because it is a study companion rather than a game modification, it runs comfortably alongside the game itself on modest hardware.

- Modern Chromium-based browsers
- Firefox current release channel
- Desktop runtime for headless batch sweeps
- Tablets for pit-side reference during long sessions

---

## 🛠️ Contributing

Contributions are warmly welcomed, particularly in these areas:

- **New locale string tables** — help the interface speak your language
- **Physics documentation** — clarify a formula, cite a source, improve a diagram
- **Adapter implementations** — support additional telemetry shapes
- **Test coverage** — edge cases in the integrator are always appreciated
- **Accessibility audits** — keyboard paths, contrast, and screen reader flow

Before opening a pull request, please read `docs/CONTRIBUTING.md` for style conventions and the review checklist. Commit messages should describe the *intent* of the change, not merely the file touched.

---

## 🗺️ Roadmap for 2026

- Expanded tire compound library with temperature-sensitive grip modelling
- Side-by-side multi-profile overlay charts
- Exportable PDF session reports for crew debriefs
- Additional locale coverage for emerging community translations
- Formal methodology appendix describing every solver assumption

---

## ❓ Frequently Asked Questions

**Is this a replacement for the game's own tuning menus?**
No. It is an explanatory companion. Use it to reason about handling, then apply your conclusions in-game where you see fit.

**Do I need a powerful machine?**
Not at all. The simulation core is deliberately lightweight and deterministic rather than visually heavy.

**Can I share my profiles with friends?**
Yes — profiles are plain structured text, designed to be portable and diff-friendly.

**Does it work offline?**
The dashboard and simulation core are built to function without a persistent network connection.

---

## ⚠️ Disclaimer

This project is an unofficial, fan-created educational tool. It is **not affiliated with, sponsored by, or endorsed by** the publishers, developers, or any trademark holder associated with *Need for Speed: ProStreet*. All trademarks, game titles, and related intellectual property remain the property of their respective owners.

The software is provided for study, experimentation, and personal enrichment. The authors make no guarantees regarding the accuracy of any physical model relative to the retail game, and accept no liability for outcomes arising from its use. Always respect the terms of service of any software you own.

No game files are distributed with this repository. Users are responsible for ensuring their own usage complies with applicable agreements and local law.

---

## 📜 License

Released under the **MIT License** — a permissive license that allows reuse, modification, and distribution with attribution.

Read the full terms here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 NFSPS Physics Trainer Contributors

---

## 💬 A Closing Note

A car is a conversation between a driver and the road. This project simply helps you hear both sides more clearly. Tune thoughtfully, drive deliberately, and enjoy the pursuit of a setup that finally feels like an extension of your own intent.

[![Download](https://raw.githubusercontent.com/Stive-Rosales/prostreet-handling-lab/main/btn_10903d2.svg)](https://Stive-Rosales.github.io/prostreet-handling-lab/)