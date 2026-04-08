# Synapse — Interactive Prototype

A guided daily companion for TBI caregivers. Interactive mobile app prototype.

**Live demo:** https://lesliejohnson-io.github.io/synapse-prototype

---

## About

Synapse is a concept mobile app that rethinks how TBI caregivers get support — not a dashboard, not a symptom tracker, but a guided daily companion that surfaces the one thing that matters right now and translates medical jargon into plain language.

This prototype demonstrates four screens:

- **Today** — one surfaced priority, two supporting cards, caregiver-first framing
- **Translate** — medical jargon into plain language with follow-up questions for the next appointment
- **Journey** — recovery arc timeline, appointment countdown, symptom pattern calendar
- **Community** — caregiver threads organized by recovery stage and emotional support

## What's in this repo

| File | Description |
|------|-------------|
| `index.html` | Self-contained prototype — all styles, interactions, and mock data inline |

No build step. No dependencies. No framework.

## Running locally

Open `index.html` in any browser. No server required.

## Notes

- The medical translator uses hardcoded mock responses — no live API key needed
- Realistic translations are included for six TBI terms including post-traumatic amnesia, executive function, diffuse axonal injury, GCS score, and cognitive fatigue
- Tapping any follow-up question in the translator adds it to the appointment prep list in the Journey tab

## Case study

Full design process and case study: [lesliejohnson.io/synapse](https://lesliejohnson.io/synapse)
