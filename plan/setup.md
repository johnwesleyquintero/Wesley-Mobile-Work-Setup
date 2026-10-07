# 📱 Mobile Workstation System Design

> *"A portable, resilient work system for operations, development, and remote work — from coffee shops to campsites."*

**Status:** Planning  
**Target Laptop Budget:** ₱55,000  
**Primary Use:** Work / Travel / Coffee Shop / Inn / Camp  
**Design Principle:** Bottleneck-based development  

---

## 💰 Master Budget & Pricing Summary

*Note: These are planning estimates based on PH retail pricing. Actual prices should be verified before purchase.*

| Phase | Item | Estimated Cost (₱) | Notes / Target Specs |
| :--- | :--- | :--- | :--- |
| **Phase 1: Core** | Dedicated 14" Laptop | 55,000 | Target budget (Win 11, 16GB RAM, 512GB SSD) |
| | Main Backpack (23L) | 4,000 – 6,000 | Thule EnRoute or equivalent |
| | 100W USB-C PD Power Bank | 2,500 – 4,000 | 20,000mAh class, laptop-compatible |
| | Bluetooth Mouse | 800 – 2,000 | High priority for ergonomics |
| | Cable / Accessory Kit | 500 – 1,000 | Organizer, USB-C cables |
| | **Phase 1 Subtotal** | **₱62,800 – ₱68,000** | *Serious coffee shop / inn / travel workstation* |
| **Phase 2: Resilience**| 4G/5G Hotspot | 2,500 – 6,000 | Primary/Backup SIM redundancy |
| | Portable Power Station | 13,000 – 20,000 | 245–512Wh (LiFePO4, e.g., EcoFlow RIVER 3) |
| | **Phase 2 Subtotal** | **₱15,500 – ₱26,000** | *Adds off-grid capability and network failover* |
| **Phase 3: Camp** | Foldable Laptop Stand | 800 – 1,500 | Ergonomics for 4+ hour sessions |
| | USB-C Rechargeable Fan | 800 – 2,000 | Heat management (High priority for PH) |
| | USB-C Rechargeable Lantern| 500 – 1,500 | Camp / night work lighting |
| | Folding Table | 1,000 – 2,500 | ~60 × 40 cm target |
| | Folding Chair | 1,500 – 3,500 | Stable, compact, good back support |
| | Weather Protection | 500 – 1,000 | Rain cover, waterproof pouch, laptop sleeve |
| | **Phase 3 Subtotal** | **₱5,100 – ₱12,000** | *Outdoor comfort and hardware protection* |
| **Existing** | Tablet | ₱0 | Already owned (provides PC/desktop mode) |
| | Headphones | ₱0 | Already owned |
| **GRAND TOTAL** | **Full Camp Configuration**| **₱83,400 – ₱106,000** | *Maximum work capability per kilo and per peso* |

---

## 📋 Overview

This project defines a mobile workstation **system** rather than a collection of gadgets.

The goal is simple:  
> *"Open laptop → connect → work."*

The system should work seamlessly across:
- ☕ Coffee shops
- 🏨 Inns / hotels
- 🚗 Road trips
- 🏕️ Campsites
- 🏠 Home
- 🧑‍💻 Coworking spaces

The setup prioritizes **portability, power resilience, connectivity, ergonomics, and redundancy** without unnecessary hardware.

---

## 🏗️ System Architecture

```text
                    MOBILE WORKSTATION
                           │
          ┌────────────────┼────────────────┐
          │                │                │
       COMPUTE          CONNECTIVITY       POWER
          │                │                │
      ┌───┴───┐        ┌───┴───┐       ┌───┴────┐
      │       │        │       │       │        │
    Laptop  Tablet   SIM A   SIM B   Power   Power
    Primary Backup   Primary Backup  Bank   Station
```

**Core Principle:**
- **Laptop** = Primary workstation
- **Tablet** = Secondary / emergency workstation
- **Power bank** = Short-term backup
- **Power station** = Off-grid power
- **SIM A/B** = Connectivity redundancy

---

## 💻 Hardware

### 1. Dedicated Laptop
**Target Budget:** ₱55,000

**Target Specification:**
| Component | Target |
| :--- | :--- |
| **Display** | 14" |
| **Aspect Ratio** | 16:10 preferred |
| **Resolution** | 1920×1200+ |
| **RAM** | 16 GB minimum |
| **Storage** | 512 GB SSD minimum |
| **CPU** | Modern Ryzen 5/7 or Core Ultra 5/7 |
| **Battery** | 60 Wh+ preferred |
| **Charging** | USB-C PD |
| **Wi-Fi** | Wi-Fi 6/6E |
| **Webcam** | 1080p preferred |
| **Weight** | ≤1.6 kg preferred |
| **OS** | Windows 11 |
| **Ports** | USB-C + USB-A + HDMI |

**Primary Workloads:**
- Hungry Artisan operations, Asana, Google Sheets, Slack, Gmail
- Freight / logistics, browser-heavy workflows
- VS Code, Git / GitHub, Scripts, Spreadsheet debugging
- General Windows applications

**Selection Principle:**  
Prioritize: 1. Reliability, 2. Battery life, 3. Portability, 4. Keyboard/ergonomics, 5. USB-C charging, 6. Serviceability, 7. Performance.  
*Raw gaming performance is unnecessary.*

### 2. Existing Tablet
**Cost:** ₱0  
The existing tablet already provides PC/desktop mode.

**Role:** Ultra-light work, quick tasks, coffee-shop sessions, travel, emergency workstation, laptop backup, media/entertainment.

**Strategy:**  
The tablet is not being replaced. Instead:
```text
Tablet  → Ultra-mobile / backup workstation
Laptop  → Dedicated primary workstation
```
This creates hardware redundancy without purchasing a second laptop.

---

## 🎒 Carry System

### 3. Main Backpack
**Target:** Thule EnRoute 23L or equivalent  
**Estimated:** ₱4,000–₱6,000

**Requirements:**
- ~23L capacity, dedicated laptop & tablet compartments
- Water resistance, lightweight construction, padded back
- Comfortable shoulder straps, bottle/umbrella pocket
- Luggage pass-through preferred, durable zippers/construction

**Expected Load:**
```text
┌──────────────────────────┐
│       MOBILE BAG         │
├──────────────────────────┤
│ 14" Laptop               │
│ Tablet                   │
│ 100W USB-C Power Bank    │
│ Laptop Charger           │
│ Bluetooth Mouse          │
│ Headphones               │
│ Phone / Hotspot          │
│ Water Bottle             │
│ Notebook                 │
│ Light Clothing           │
│ Cables                   │
└──────────────────────────┘
```
**Design Target:** Large enough for the complete mobile workstation. Small enough to remain comfortable as an everyday coffee-shop/travel backpack.

---

## 🔋 Power System

### 4. USB-C PD Power Bank
**Target:** 20,000mAh / 100W  
**Estimated:** ₱2,500–₱4,000

**Requirements:** 20,000mAh class, 100W USB-C PD, laptop-compatible, USB-C input/output.  
**Role:** Short-duration backup power.
```text
Laptop Battery → USB-C PD Power Bank → Power Station
```
*The power bank should handle situations where deploying the larger power station is unnecessary.*

### 5. Portable Power Station
**Target:** 245–512Wh  
**Estimated:** ₱13,000–₱20,000  
**Example Product Class:** EcoFlow RIVER 3 / RIVER 3 Plus, BLUETTI Elite-class compact units, or equivalent LiFePO4 systems.

**Requirements:** LiFePO4 chemistry, USB-C PD, AC output, USB outputs, car charging, solar charging capability, portable form factor.

**Loads:**
```text
Power Station
     │
 ┌───┼───────────┐
 │   │           │
PC  Fan        Light
 │
Laptop
```
> **Upgrade Rule:** Do not immediately purchase a 1kWh+ power station. Start small. Measure actual usage. Upgrade only when capacity becomes a real bottleneck.

---

## 📶 Connectivity

### 6. Primary Internet
- **Option A:** Phone hotspot
- **Option B:** Dedicated 4G/5G hotspot  
**Estimated hotspot budget:** ₱2,500–₱6,000

### 7. Connectivity Redundancy
Use two independent networks.
```text
        INTERNET
           │
     ┌─────┴─────┐
     │           │
   SIM A       SIM B
  Primary      Backup
```
**Objective:** Do not make work dependent on coffee-shop, hotel, inn, or campsite Wi-Fi. If Network A fails, switch to Network B.

---

## 🖱️ Work Accessories

| Item | Estimated Cost | Priority |
| :--- | :--- | :--- |
| Bluetooth mouse | ₱800–₱2,000 | High |
| Foldable laptop stand | ₱800–₱1,500 | Medium |
| Cable organizer | ₱300–₱700 | Medium |
| USB-C cables | ₱200–₱500 | High |
| Headphones | ₱0 | Existing |

> **Rule:** Do not replace working accessories. *"Upgrade only when there is a real bottleneck."*

---

## 🏕️ Camp Layer
*These components are only required when operating outdoors.*

### 8. USB-C Rechargeable Fan
**Estimated:** ₱800–₱2,000 | **Priority:** High (for PH outdoor work)  
**Purpose:** Heat management, work comfort, USB-powered operation (runs from power bank or station).

### 9. USB-C Rechargeable Lantern
**Estimated:** ₱500–₱1,500  
**Purpose:** Camp lighting, emergency lighting, night work.

### 10. Folding Table
**Estimated:** ₱1,000–₱2,500 | **Target:** ~60 × 40 cm  
**Capacity:**
```text
┌─────────────────────────┐
│ Laptop    │ Phone       │
│           │             │
│ Mouse     │ Drink       │
└─────────────────────────┘
```
*No need for a large camping workstation.*

### 11. Folding Chair
**Estimated:** ₱1,500–₱3,500  
**Requirements:** Stable, compact, good back support, comfortable for multi-hour sessions. Ergonomics becomes critical when work sessions exceed 4+ hours.

---

## 🌧️ Weather / Protection

| Item | Estimated Cost |
| :--- | :--- |
| Backpack rain cover | ₱300–₱700 |
| Waterproof electronics pouch | ₱200–₱500 |
| Laptop sleeve | ₱500–₱1,000 |

> **Outdoor Rule:** Electronics should never be left directly on wet surfaces, exposed to rain, in direct sunlight for extended periods, or on dusty ground.

---

## 🚀 Deployment Modes

**Mode 1 — Ultra-Light**  
`Tablet + Phone`  
*Approx. additional cost: ₱0*  
For: Quick tasks, casual travel, light work.

**Mode 2 — Coffee Shop**  
`Laptop + Mouse + Hotspot`  
*Estimated system investment: ₱60k+*  
Primary environment: Coffee shops / coworking spaces.

**Mode 3 — Inn / Hotel**  
`Laptop + Tablet + Power Bank + Hotspot`  
Designed for a full workday away from home.

**Mode 4 — Camp**  
```text
Laptop
Tablet
   │
Hotspot
   │
Power Bank
   │
Power Station
   ├── Fan
   └── Lantern

Folding Table
Folding Chair
```
Designed for independent remote work.

---

## ⚡ Power Architecture

```text
                       POWER
                         │
             ┌───────────┴───────────┐
             │                       │
         SHORT TERM              OFF-GRID
             │                       │
        USB-C PD Bank          Power Station
             │                       │
          Laptop             ┌───────┼───────┐
                             │       │       │
                           Laptop   Fan    Light
                                     
                         INPUT SOURCES
                              │
                    ┌─────────┼─────────┐
                    │         │         │
                   AC        Car      Solar
```

## 🌐 Connectivity Architecture

```text
                    INTERNET
                       │
              ┌────────┴────────┐
              │                 │
           Network A         Network B
            Primary            Backup
              │                 │
              └────────┬────────┘
                       │
                    Laptop
```

---

## 🛒 Purchase Order

**Priority 1 — Work**
- [ ] Dedicated 14" laptop — *₱55k target*
- [ ] 23L backpack — *₱4–6k*
- [ ] 100W USB-C power bank — *₱2.5–4k*
- [ ] Bluetooth mouse — *₱0.8–2k*

**Priority 2 — Resilience**
- [ ] Primary 4G/5G connectivity
- [ ] Backup SIM/network
- [ ] Portable power station

**Priority 3 — Ergonomics**
- [ ] Laptop stand
- [ ] Folding table
- [ ] Folding chair

**Priority 4 — Outdoor**
- [ ] USB-C fan
- [ ] USB-C lantern
- [ ] Rain cover
- [ ] Waterproof electronics pouch

---

## 🧠 Design Principles

1. **Bottleneck-Based Development**  
   Do not buy equipment because it looks useful. Buy it when a real limitation appears.
2. **Existing Hardware First**  
   The tablet already works. Keep it. The laptop adds dedicated Windows capability rather than replacing everything.
3. **Redundancy Without Bloat**  
   Laptop + Tablet | SIM A + SIM B | Battery + Power Bank + Power Station. Three layers where failure actually matters.
4. **Portable by Default**  
   Every component should be easy to: Carry, Pack, Deploy, Charge, Store.
5. **No Gear Collection**  
   The objective is not maximum equipment. The objective is: *"Maximum work capability per kilogram and per peso."*

---

## 🎯 Target End State

```text
                    WESLEY
               MOBILE WORKSTATION
                        │
              ┌─────────┴─────────┐
              │                   │
           COMPUTE             INFRA
              │                   │
        ┌─────┴─────┐       ┌─────┴──────┐
        │           │       │            │
      Laptop      Tablet  Internet      Power
      Primary     Backup      │            │
                           SIM A/B      Bank/Station
                                             │
                                      ┌──────┼──────┐
                                      │      │      │
                                    Laptop  Fan   Light
                       

        ┌─────────────────────────────────────┐
        │          PORTABLE ENVIRONMENTS      │
        ├──────────┬──────────┬───────────────┤
        │ Coffee   │   Inn    │     Camp      │
        │  Shop    │  Hotel   │               │
        └──────────┴──────────┴───────────────┘
```

**Mission:**  
> *"A dedicated workstation that can leave the house without sacrificing the ability to work."*  
Not a camping rig. Not a digital-nomad influencer setup. Not a collection of gadgets. **A portable income/work asset.**

---

## ⚙️ Operating Rule

> *"If it works, use it.*  
> *If it's not broken, don't fix it.*  
> *If unsure, simplify.*  
> *One simple upgrade at a time."*

***
