---
title: "Driver Dash — Game Design Document"
date: 2025-01-15
draft: false
description: "Game Design Document for Driver Dash — arcade driving with cargo-based mechanics"
tags: ["design-doc", "gdd", "driver-dash", "arcade", "driving"]
categories: ["design-docs"]
---

# Driver Dash — Game Design Document

*Status: **Concept Complete** — Ready for prototyping*

---

## Game Design Concept

### Working Title
**Driver Dash**

### Concept Statement
A fast-paced arcade driving game with smooth drifting, boost mechanics, item pickups, and cargo that changes how you drive.

### Genre
**Arcade / Driving**

### Target Audience
Players who enjoy short arcade sessions. Any age and gender.

### Unique Selling Points
| Cargo | Mechanic | Effect |
|-------|----------|--------|
| **Pizza** | Cools over time | Goes cold if you take too long |
| **Ice Cream** | Melts with heat | Melts *faster* when you boost |
| **Hamburger** | Quality degrades on impact | Gets worse every collision |

**Core Mechanics:** Drift, boost, item pickups, smooth arcade driving, fun drift noises.

---

## Player Experience & Game POV

- **Role:** Delivery car in a goofy, arcade-style top-down 2D world
- **Vibe:** Fast, fun, chaotic — smooth driving feel with chaotic cargo management
- **Perspective:** Top-down 2D

---

## Platform
Portfolio piece on **GitHub Pages** (WebGL), playable on PC and web.

---

## Objectives
Pick up cargo → deliver to NPC → maintain cargo quality → have fun driving.

---

## Core Loops
1. **Pickup** → 2. **Drive & Drift** → 3. **Manage Cargo** (temp/quality) → 4. **Deliver** → 5. **Score & Repeat**

*Engagement comes from smooth drive physics + drifting + cargo challenges.*

---

## Interactivity
- **NPCs** receive deliveries and react to cargo condition
- **Road network** defines playable area; world outside is blocked
- **Traffic & obstacles** create routing decisions

---

## Stats Snapshot
| Metric | Target |
|--------|--------|
| **Session Length** | 2–4 min |
| **Cargo Types (MVP)** | 3 (Pizza, Ice Cream, Hamburger) |
| **Districts (MVP)** | 1 (Downtown) |
| **Core Mechanics** | Drift, Boost, Pickup, Deliver |
| **Platform** | Web (GitHub Pages), PC |
| **Engine** | Unity 2D URP → WebGL |

---

## Platform & Deployment
- **Primary:** GitHub Pages (WebGL build via Unity)
- **Secondary:** itch.io
- **Scope:** Portfolio showcase — free, no monetization

---

## Next Steps
- [ ] Prototype driving feel (drift + boost)
- [ ] Implement cargo temperature/quality system
- [ ] Build Downtown district loop
- [ ] Vertical slice: 1 district, 3 cargo types, 5 deliveries

---