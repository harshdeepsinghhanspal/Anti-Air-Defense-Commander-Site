# SKYSTRIKER-BRAVO
### High-Mobility Area Air Defense System

---

## Overview

SKYSTRIKER-BRAVO is a simulated air defense command panel. It provides a real-time operator interface for early warning, target acquisition, altitude elevation tracking, and missile fire control, all within a single unified display.

---

## Screens

**EWR - Early Warning Radar**
Wide-area surveillance radar. Sweeps 360° continuously and paints all airborne contacts. Identifies them by IFF tag: HOSTILE (▲) or FRIENDLY (●). City overlays can be toggled via the MODE button below the screen.

**TAR - Target Acquisition Radar**
Narrow-focus radar for precise azimuth and elevation tracking. Use WASD to steer the beam. Once locked onto a target, the crosshair detaches from center and tracks the contact live across the screen.

**AER - Altitude Elevation Radar**
Vertical slice display showing all contacts by altitude. Use `8` / `2` to raise and lower the elevation beam. The mini graph below shows the current beam angle as a rotating arm.

---

## Controls

| Key | Action |
|-----|--------|
| `W` / `S` | TAR beam up / down |
| `A` / `D` | TAR beam left / right |
| `8` / `2` | AER elevation up / down |
| `X` | Lock / unlock target |
| `N` | Fire missile at locked target |

Switches for EWR, TAR, and AER can also be toggled by clicking their respective panels. Beam mode (NARROW / STANDARD) affects FOV on both TAR and AER.

---

## Missile System - AGNIBAAN

8-round loadout displayed as individual cells. Rounds are consumed on each firing. Click **REARM** to reload all 8. Individual cells can be toggled manually.

To fire:
1. Power on EWR and TAR
2. Align TAR beam and AER elevation on the same contact
3. Press `X` to lock
4. Press `N` or click FIRE to launch

---

## IFF and Contacts

- **HOSTILE (▲)** - military-type contacts, faster, higher altitude
- **FRIENDLY (●)** - civilian-type contacts, slower, lower altitude

Contacts spawn from outside radar range and transit through. Up to 6 contacts are active at any time. Destroyed contacts are removed from all displays immediately.

---

## Display Notes

- The **MODE** button below EWR toggles city name overlays on the radar
- The **VAJRAPRAHAAR** text in the top-right cycles through operational phrases on load and can be clicked to step through them manually
- The mini elevation graph below AER shows beam angle as a fixed-length rotating arm; flat means low elevation, steep means high

---

*SKYSTRIKER-BRAVO S/N:322A1 - Operator use only*
