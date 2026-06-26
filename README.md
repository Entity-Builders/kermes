---
name: 'Kermes'
tagline: 'Local commerce activation through QR play, merchant-locked tickets, and neighborhood impact'
platform: 'Web / PWA'
status: 'concept'
category: 'local-commerce'
icon: '🎟️'
features:
  - 'Merchant-cluster pilot'
  - 'Storefront sticker and QR entry'
  - 'Human-vs-human trivia match'
  - 'Merchant-locked tickets'
  - 'Verified local cause ledger'
downloadUrl: ''
visible: false
---

# Kermes

Kermes is a planning-stage Entity Builders app for validating a local commerce
activation network. The first pilot is intentionally narrow: pre-adhere a
cluster of local merchants, install simple Kermes signage, run one trivia-based
QR flow, issue merchant-locked tickets, and support verified local causes.

## Current Status

Status: concept / PRD draft.

There is no runtime app code in this folder yet. This folder exists to reserve
the app identity, document the product boundary, and give future agents a stable
place to start when implementation begins.

## Product Boundary

Kermes MVP is not the full licensed real-money product. The MVP does not include:

- tradable token,
- cash-out prizes,
- minors,
- citywide CABA launch,
- broad marketplace,
- tax-benefit promises,
- public token appreciation claims,
- user-created paid matches.

The MVP focuses on the merchant-cluster pilot:

1. Pre-adhere 5-15 merchants in one barrio or commercial corridor.
2. Prepare merchant-specific QR and signage.
3. Let users scan in-store and play a short human-vs-human trivia match.
4. Issue merchant-locked tickets to winners.
5. Record transparent local cause support.
6. Run a one-day event only after the merchant cluster exists.

## Durable Context

- OpenSpec change:
  `openspec/changes/define-kermes-merchant-cluster-pilot/`
- BMAD PRD:
  `_bmad-output/planning-artifacts/prds/prd-entity-builders-2026-06-21/prd.md`
- BMAD PRFAQ:
  `_bmad-output/planning-artifacts/prfaq-entity-builders.md`
- App-scoped agent context:
  `.agents/apps/kermes/context.md`

## Implementation Rule

Before adding runtime code, read the OpenSpec change and resolve the open
questions around legal/economic model, first barrio/corridor, first trivia
format, cause verification, and event permit assumptions.
