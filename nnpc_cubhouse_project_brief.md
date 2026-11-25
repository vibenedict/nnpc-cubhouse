# Project Brief: **NNPC CubHouse**
**Location:** NNPC Quarters, Sabo, Kaduna, Nigeria  
**Project Type:** Private Tennis & Social Club Digital Portal, Court Booking & Member Governance System  

---

## 1. Executive Summary
**NNPC CubHouse** is a modern, full-screen responsive web portal built for **NNPC Tennis Club Kaduna**. Inspired by the refined hospitality and heritage aesthetic of premier private tennis institutions, the platform unifies member onboarding, player skill rating calibration, printable ISO CR80 physical ID card generation, court and game reservations for both members and visiting guests, clubhouse media sharing, dues treasury management, and backend club administration into a single seamless application.

---

## 2. Core Objectives
- **Elevate Club Heritage & Identity:** Present an authoritative, welcoming digital clubhouse featuring the official **NNPC Tennis Club Kaduna** crest, forest-green and metallic-gold styling, and a rotating 60-second tennis action hero showcase.
- **Streamline Court & Match Bookings:** Enable registered members (complimentary access) and visiting players (guest day-pass access) to reserve Championship Floodlit Hard Courts (1–6), or post open partner requests.
- **Digitize Member Credentials & Ratings:** Allow players to maintain verified **NTRP** and **UTR** ratings, stroke telemetry profiles, and generate print-ready front-and-back **CR80 Member ID Cards** with QR verification.
- **Centralize Dues & Backend Governance:** Provide transparent dues billing with instant receipt generation alongside a protected **Admin Backend Console** for managing ID card expiry dates and member dues clearance.

---

## 3. Target User Personas
1. **Club Members:** Registered NNPC CubHouse players who book courts, track NTRP/UTR ratings, upload match photos/videos, pay dues, and print their official ID cards.
2. **Visiting Players / Guests:** Non-member players in Kaduna who book single sessions, register for guest day-passes, and join open partner match requests.
3. **Club Administrators / Stewards:** Club governance officers who authenticate into the Admin Console to update member ID validity dates, verify ratings, and toggle dues payment standing.

---

## 4. Key Functional Modules
- **Clubhouse Overview & Rotating Hero:** Full-bleed hero gallery cycling through 5 tennis action photographs every 60 seconds, paired with live court telemetry marquee, club KPIs, and recent match highlights.
- **Book a Game / Court Reservation System:** Dual-mode booking form (`Club Member` vs. `Visiting Player`) supporting Singles, Doubles, Ball Machine practice, and Open Partner matching across all 6 courts.
- **Player Passport & Printable CR80 ID Studio:** Interactive 3D-tilt digital passport, portrait uploader, stroke calibration sliders, and a dual-sided (`Obsidian Forest` or `Championship White`) printable physical ID card sheet.
- **Media Studio:** Community gallery supporting local file uploads (`image/*` and `video/*`) as well as external media URLs with applause/like interactions.
- **Member Ladder & Roster:** Searchable and NTRP-filterable directory enabling friendly match challenges across skill tiers.
- **Dues & Treasury Portal:** Membership tier checkout (`Monthly Court Pass`, `Quarterly Competitor`, `Annual Heritage Patron`) that automatically extends ID card expiry dates and issues ledger receipts.
- **Admin Backend Console:** Passcode-protected governance table for real-time updates to member ID expiry dates and dues payment status.

---

## 5. Design System & Technical Stack
- **Visual Aesthetic:** Heritage Forest (`#0F1E17`), Metallic Gold (`#C5A059`), and Warm Parchment (`#FAF8F5`) paired with *Cormorant Garamond* editorial headings, *Plus Jakarta Sans* UI copy, and *JetBrains Mono* telemetry badges.
- **Architecture:** Self-contained, zero-dependency single-file HTML5, Tailwind CSS, and Vanilla JavaScript application with `localStorage` persistence—ready for instant preview in VS Code / Google Antigravity or static deployment on Netlify, Vercel, or GitHub Pages.