```markdown
# Kidnap & Ransom Exposure & Underwriting Intelligence

A self-contained, single-file dashboard for exploring kidnap & ransom (K&R) underwriting risk — built for underwriters, brokers, and risk analysts who need to reason about exposure, pricing, and controls at a glance.

## Overview

The dashboard models how protective measures, travel behavior, sector risk, and regional volatility combine to drive a policy's risk score, premium, and recommended retention. It ships with a synthetic 100-policy portfolio so every view — from executive summary to line-item detail — is populated and interactive out of the box.

## Features

- **Executive Dashboard** — portfolio-wide KPIs, risk band distribution, and a risk-score-vs-premium scatter view sized by incident severity.
- **Underwriting Simulator** — a live scoring engine you can drive with sliders and toggles: close protection, crisis response retainers, HEAT training, travel tracking, prior incidents, travel frequency, and regional instability. Outputs an estimated premium, recommended retention, sector benchmark comparison, and tailored underwriting recommendations and exclusions.
- **Portfolio Explorer** — searchable, sortable, filterable table across all synthetic policies, with a full per-policy detail view.
- **Sector Heat Map** — cross-sector comparison of average risk score, incident frequency, severity, premium, and base incident probability, color-coded by relative exposure.
- **Threat Exposure** — sector-by-sector breakdown of incident probability, average ransom/response cost, captivity duration, and travel exposure.

## Design & Interaction

- Dark, editorial navy-and-gold visual language suited to a crisis-response / underwriting context.
- Fully interactive, continuously animated network background — nodes drift, breathe, and send signal pulses along their connections, with a swirling reaction to cursor movement, reinforcing the "signal tracking" theme without competing with the data.

## Tech

Vanilla HTML/CSS/JS with [Chart.js](https://www.chartjs.org/) for charting — no build step, no dependencies to install. Open `index.html` directly in any modern browser.

## Data Disclaimer

All figures — sector risk weights, ransom estimates, captivity durations, and the 100-policy portfolio — are **synthetic and illustrative only**. They are generated from a seeded model for demonstration purposes and do not represent any real insurer, client, or book of business.
```

Want me to also add a screenshot/GIF placeholder section, a table of contents, or a "Getting Started" block with clone/open instructions?
