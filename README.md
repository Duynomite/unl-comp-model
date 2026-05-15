# UNL Ancillary Comp Model

Agent-facing compensation calculator for **Clear Path Coverage** (CPC) agents selling UNL ancillary products (Home Healthcare Shield + Hospital Indemnity Shield).

**Live:** https://duynomite.github.io/unl-comp-model/

## What it shows

- **Career outlook** — realistic Year 1 and Year 5 annual income at four activity levels (Building / Steady / Strong / Top performer)
- **Career calculator** — interactive sliders for sales per day, annual premium, placement rate, M12 retention, Y2+ retention, and optional MA cross-sell (with CMS compliance guidance)
- **Per-sale calculator** — drill into one policy by product / state / age / premium
- **Payment timeline** — when each dollar arrives (advance, monthly residuals, renewals)
- **Cancellation scenarios** — what's owed back if a policy lapses in any given month
- **Rate reference tables** — agent rates by state for both products
- **FAQ** — pay timing, cancellation mechanics, lead coverage, CMS cross-sell rules

## Stack

Single-file HTML. React 18 + Tailwind v4 via CDN. No build step.

## Compliance

Agent-side rates only. No agency-side compensation values appear anywhere in the UI, source comments, or data layer. Mirrors the same disclosure pattern as `UNL_Ancillary_Academy.html`.
