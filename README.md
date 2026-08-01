<div align="center">
  <img src="assets/app-icon.png" width="140" alt="Bowldyna Studio app icon">

  # Bowldyna Studio

  **Turn feel into logic.**  
  Physics-based bowling simulation, strike-route search, and pin-action analysis.

  [![Platform](https://img.shields.io/badge/Platforms-iOS%20%7C%20Android-2563eb)](#platforms)
  [![Privacy](https://img.shields.io/badge/Privacy-No%20tracking-0ea5e9)](privacy/)
  [![Business Model](https://img.shields.io/badge/Model-Free%20%2B%20one--time%20Pro-7c3aed)](#free--pro)
</div>

---

## About

Bowldyna Studio is a physics-based bowling simulator built to explain not only **where** a ball travels, but **why** it takes that shape.

It combines release conditions, ball specifications, PAP and layout, lane oil, oil transition, and pin physics in one analysis environment.

## Current features

- Continuous skid, hook, and roll simulation
- Speed, starting board, launch direction, rev rate, Axis Rotation, and Axis Tilt
- Coverstock, surface, RG, differential, core type, PAP, and layout controls
- House, flat, short, long, and custom lane conditions
- Breakdown and carrydown editing
- Strike-route reverse search with nearby-shot robustness testing
- Fast Legacy 2D pin physics
- Advanced 3D Beta rigid-body pin physics
- Mode-consistent pin display, pinfall, and remaining-pin scoring
- Breakpoint, pocket board, entry angle, hit pins, fallen pins, and remaining pins
- My Ball Library and Lane Library
- House Ball and My Ball modes
- 12 supported languages

## Free & Pro

### Free

- Core trajectory simulation
- Basic release controls
- Standard lane conditions
- Pin-action visualization
- Core result metrics

### Bowldyna Pro

A one-time in-app purchase unlocks advanced features such as:

- Strike-route search
- Detailed ball, PAP, and layout controls
- Custom lane and oil-transition controls
- Advanced pin physics and 3D Beta
- Ball and lane libraries

**No subscription for Bowldyna Pro. No advertising in the current release.**

## Platforms

Bowldyna Studio is being prepared and tested for:

- iPhone and iPad through the Apple App Store
- Android through Google Play

## Languages

English, Japanese, Simplified Chinese, Traditional Chinese, Korean, Spanish, Brazilian Portuguese, French, German, Italian, Thai, and Indonesian.

## Public pages

| Page | Description |
|---|---|
| [Product page](./) | Current Bowldyna Studio overview |
| [Support](support/) | iOS and Android support and purchase restoration |
| [Privacy Policy](privacy/) | Current data-handling policy |

## Privacy

- No user account required
- No behavioral tracking
- No advertising in the current release
- Simulation settings and libraries are stored locally
- Purchases are processed by Apple App Store or Google Play

See the full [Privacy Policy](privacy/).

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment

1. Open repository **Settings**
2. Select **Pages**
3. Choose **Deploy from a branch**
4. Select `main` and `/(root)`
5. Save

## Disclaimer

Simulation results are intended for analysis and learning. Real-world ball motion and pinfall can vary with lane surface, oil transition, ball condition, pin condition, release mechanics, and environmental factors.

---

<div align="center">
  <strong>Bowldyna Studio</strong><br>
  Turn feel into logic.<br>
  投球を、感覚からロジックへ。
</div>
