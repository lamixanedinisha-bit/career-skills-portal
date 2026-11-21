# Student Career & Skills Development Portal — ICT306

> **Portfolio documentation, recreated from the ICT306 report and presentation in Google Drive — original uni code / prototype files are no longer accessible (student email closed).**
>
> This repo contains the **design and deployment documentation** for the portal, not a running copy of the original prototype. Do not present it as the original submitted code.
>
> Dinisha Lamichhane was a member of the team of 4; her individual contribution is **[to confirm]** — do not assume a specific section from this repo alone.

## The problem

The institution used Moodle and MES for learning but had no integrated career platform. Jobs were shared by email and social media, with no skill-gap analysis or employability tracking.

## What was designed

A web-based enterprise portal integrated with Moodle:

- Job postings
- Skill-gap analysis and course recommendations
- Application tracking
- Employment reporting

See `docs/ARCHITECTURE.md` and `docs/DEPLOYMENT-PLAN.md`.

## Result

- **Unit:** ICT306 Information Systems Deployment & Management, T1 2026 — **85 HD**
- Completed report + presentation in Drive
- Prototype linked in the slides: https://nmyrp8.csb.app/
  - **Link status: NOT verified.** Muse checked it on 21 Nov 2026 and again at 19:33 ACST and got only a Cloudflare "Sorry, you have been blocked" page. It may still work from Dinisha's own browser/phone. **Do not add it to LinkedIn or a resume until she has opened it herself and confirmed it loads.**

## Tech / concepts

Multi-tier architecture (presentation / application / database layers) · Moodle API integration · Hybrid deployment (cloud portal + on-premise Moodle; AWS / Azure) · Role-based access control, HTTPS, CIA triad · Privacy Act 1988 and Australian Privacy Principles compliance · Cost-benefit analysis, risk register, phased transition roadmap (requirements → design → pilot → full deployment), Gantt chart.

## Licence

MIT — see `LICENSE` (same MIT text as the phishing repo; add before pushing).
