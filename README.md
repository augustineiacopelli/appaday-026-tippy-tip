# 026 · Tippy Tip

**Category:** U — Utility  
**Live URL:** https://augustineiacopelli.github.io/appaday/appaday-026-tippy-tip/

A mobile-friendly Italian tipping guide for travelers. Select your situation, enter relevant details, and get culturally accurate tip guidance — including whether a tip is expected, optional, or not needed, plus suggested amounts and a phrase to say in Italian.

## Usage

1. Tap **Step 1** to select your situation (Restaurant, Café/Bar, Hotel, Taxi/Driver, Tour Guide, Venice, or Other)
2. **Step 2** unlocks and opens automatically with context-specific inputs
3. Enter your bill total, party size, hotel tier, or other relevant details
4. Receive a verdict (tip expected / optional / not needed) with three amount tiers and an Italian phrase
5. Tap **Step 3** at any time to consult the full Quick Reference guide

## Scenarios Covered

- **Restaurant** — with Servizio incluso and Coperto toggles
- **Café / Bar** — counter vs. table service
- **Hotel** — Porter, Housekeeping, Room Service, Doorman, Concierge (routine and special), with tip amounts scaled by hotel star tier (1–3 star, 4-star, 5-star)
- **Taxi / Driver** — short city ride, airport transfer, private driver
- **Tour Guide** — large group (17+), small group (≤16), private tour with duration input
- **Venice** — Gondola, Water Taxi, Vaporetto
- **Other** — Spa/Salon, Cloakroom, Food Delivery, Restroom Attendant, Street Performer

## Technical Notes

- Single-file vanilla HTML/CSS/JS — no frameworks, no dependencies beyond Google Fonts
- No API calls, no data stored, no backend
- Mobile-first layout with `viewport-fit=cover` and `env(safe-area-inset-bottom)` for iPhone safe area
- Accordion UI guides the user through a three-step flow; Step 2 is locked until a scenario is selected
- Italian phrases selected randomly from a curated set using the polite *lei* form

## Definition of Complete

- [x] Functional across all 7 scenario categories and all sub-options
- [x] Single purpose — Italian tipping guidance only
- [x] Mobile friendly — tested at 375px viewport
- [x] Visually polished — terracotta and aged parchment palette, Playfair Display / DM Sans typography
- [x] Published to GitHub Pages before midnight Wichita time
