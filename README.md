# NNPC CubHouse — Digital Portal & Member Governance System
**Location:** NNPC Quarters, Sabo, Kaduna, Nigeria  
**Established:** 1978  
**Facility:** 6 Championship Floodlit Hard Courts, Clubhouse & Pavilion  

---

## Overview

**NNPC CubHouse** is a luxury digital portal, court reservation system, and member governance platform built for **NNPC Tennis Club**, located at the **NNPC Senior Staff Quarters, Sabon Tasha (Sabo), Kaduna, Nigeria**. Built as a zero-dependency, self-contained single-page application using HTML5, Tailwind CSS, and Vanilla JavaScript with `localStorage` persistence.

---

## Key Features & Modules

1. **Clubhouse Overview & 60-Second Rotating Hero**
   - Full-bleed hero gallery cycling through curated tennis action imagery every 60 seconds with manual indicator pills.
   - Live court status ticker marquee displaying telemetry for all 6 floodlit hard courts.
   - Live club KPIs (480+ Members, 31 Championship Titles, 6 Floodlit Hard Courts, 06:00–23:00 Hours).
   - Kaduna weather & court conditions readout.

2. **Court & Match Reservation Engine**
   - Dual-mode booking: **Club Member** (complimentary access) and **Visiting Player / Guest** (₦5,000 Guest Day-Pass).
   - All 6 floodlit hard courts supported:
     - Court 1: Championship Hard Court
     - Court 2: Tournament Hard Court
     - Court 3: Match Hard Court
     - Court 4: Practice & Training Hard Court
     - Courts 5–6: Floodlit DecoTurf Hard Courts (Late Night Illuminated Play)
   - Formats: Singles, Doubles, Ball Machine Session, Open Partner Request.
   - Real-time conflict checking, confirmation modals, and schedule feed.

3. **Player Passport & Printable ISO CR80 Physical ID Studio**
   - Interactive 3D flip card with **Obsidian Forest** and **Championship White** themes.
   - **Member QR Code & Player Profile:** The back of the ID card displays a QR code containing the member ID, cardholder name, contact, address, tier, ratings, expiry, status, issuer, and player profile URL and a button that opens the **Player Profile Modal**.
   - Real-time rating calibration (NTRP & UTR) and stroke telemetry sliders (Forehand Topspin, Backhand Slice, First Serve MPH, Net Volley).
   - Custom portrait uploader & sample avatar cycling.
   - **Print-ready ISO CR80 standard card sheet** (`85.6mm × 53.98mm`) featuring front and a back with the member details QR code and cut lines formatted via `@media print`.
   - Credential JSON export.

4. **Member Ladder & Player Roster**
   - Searchable and NTRP-tier filterable member directory.
   - Realistic member ladder records with Win/Loss tallies, club rankings, and play styles.
   - "Challenge to Match" quick action.

5. **Clubhouse Media Studio**
   - Community gallery for match photography and video highlights.
   - Local drag-and-drop / file upload with Base64 preview.
   - Interactive applause / like counters.

6. **Dues & Treasury Portal**
   - Membership tiers:
     - **Monthly Court Pass** (₦15,000 / 30 days)
     - **Quarterly Competitor** (₦40,000 / 90 days)
     - **Annual Heritage Patron** (₦150,000 / 365 days)
   - Instant payment simulation with automated ID card expiry date extension.
   - Official Kaduna Treasury Ledger Receipts with unique reference numbers (`TXN-NNPC-KD-...`).

7. **Admin Governance Console**
   - Passcode-protected access (Default: `nnpc2026` or `admin`).
   - Member management table: toggle dues clearance, extend validity dates, register new members.
   - Tennis ball inventory: record donations against registered members, log usage, and view received, used, and remaining counts with a dated history. Print the inventory report or download a CSV to share with members. Records are stored in the current browser.

---

## How to Run & Preview

### Option 1: Direct File Open
Double click [index.html](file:///Users/victorbenedict/Documents/clubHouse/index.html) or run in terminal:
```bash
open index.html
```

### Option 2: Local HTTP Server
Run a local Python server:
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

---

## Project Structure
- [index.html](file:///Users/victorbenedict/Documents/clubHouse/index.html) — Complete self-contained application
- [nnpc_cubhouse_project_brief.md](file:///Users/victorbenedict/Documents/clubHouse/nnpc_cubhouse_project_brief.md) — Specification and requirements brief
- [vs_code_antigravity_setup_guide_nnpc_cubhouse.md](file:///Users/victorbenedict/Documents/clubHouse/vs_code_antigravity_setup_guide_nnpc_cubhouse.md) — Antigravity / VS Code setup guide
