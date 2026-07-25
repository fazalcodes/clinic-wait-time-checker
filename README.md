# Clinic Wait-Time Checker

An AI-assisted product build, from problem brief to a working, accessibility-audited prototype — built as part of Anthropic and CodePath's **AI Fluency for Builders** program.

**Scenario:** A community health clinic needs a way for patients to check wait times before coming in.

## What this project shows

This isn't just a coding exercise — it's a full product cycle, using AI deliberately at each stage rather than as a single "write me an app" prompt:

| Stage | What happened |
|---|---|
| **Empathy** | Defined real users (elderly patients, no-smartphone patients, non-English speakers) and real constraints (budget, privacy, patchy internet) |
| **Design** | Wrote measurable requirements — not "fast," but "5 seconds on 3G, one screen, no login" |
| **Architecture** | Proposed a technical approach with AI, then rejected two of its suggestions (patient login, EHR integration) for violating privacy/budget constraints |
| **Implementation** | Built a working static HTML/CSS/JS prototype — no backend, no login, works on old phones |
| **Judgement** | Ran a manual accessibility audit (color contrast math, screen reader gaps, keyboard navigation) and documented exactly what AI missed on its own |
| **Shipping** | Answered 5 honest diligence questions (Understanding, Testing, Access, Responsibility, Feedback loop) before treating it as demo-ready |

## Project versions

- `app/wait-time-checker-v1.html` — first working build
- `app/wait-time-checker-v2.html` — rebuilt against a formal design spec, with accessibility fixes (focus trap, ARIA live regions, contrast fixes)
- `app/wait-time-checker-v3.html` — one real iteration: clearer messaging + a tappable phone number when wait data is stale

## Full write-ups

- [`docs/01-problem-brief-and-delegation-plan.docx`](docs/01-problem-brief-and-delegation-plan.docx)
- [`docs/02-spec-and-tests.docx`](docs/02-spec-and-tests.docx)
- [`docs/03-design-spec-and-accessibility-audit.docx`](docs/03-design-spec-and-accessibility-audit.docx)
- [`docs/04-shipping-diligence.docx`](docs/04-shipping-diligence.docx)

## Why this matters

Every state (normal wait, zero wait, clinic closed, stale/no data) was tested and audited on purpose — including honestly documenting what the build *doesn't* serve well (patients without smartphones, non-English/Spanish speakers) rather than hiding the gaps.

---
Built by Mohd Fazal
