# WVU Nexus — Student OS

An interactive concept pitch and prototype for a unified campus app for West Virginia University. WVU students currently juggle 15+ disconnected systems (Blackboard/eCampus, STAR/Banner, DegreeWorks, PRT tracker, LiveSafe, GET Mobile, and more) with no shared login and no data syncing between them. Nexus proposes a single "student OS" that unifies academics, campus life, and safety into one experience.

Built with Next.js and served as a self-contained, single-page app: an 8-slide investor/stakeholder deck (problem, solution, live demo, campus sentiment, technical architecture, business case, rollout roadmap, and closing pitch) with an embedded, fully interactive phone-mockup demo.

## Demo features

- **Smart dashboard** — assignments, grades, and deadline nudges pulled into one view
- **Campus Pulse** — live, anonymous sentiment feed and occupancy status across campus locations
- **SafeWalk** — a walk-home safety mode with live location sharing and a panic button
- **Syllabus Scanner** — mock AI extraction of due dates from an uploaded syllabus
- **Nexus AI** — a chat assistant for schedule, dining, and transit questions

All data in the demo is mocked/hardcoded for presentation purposes — there is no backend or live integration with WVU systems.

## Tech stack

- [Next.js](https://nextjs.org) 16 (App Router) + React 19
- TypeScript
- Tailwind CSS 4
- [Framer Motion](https://www.framer.com/motion/) for animation
- [Lucide](https://lucide.dev/) for icons

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it. The presentation and demo live in [app/page.tsx](app/page.tsx).

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local dev server |
| `npm run build` | Production build |
| `npm run start` | Serve the production build |
| `npm run lint` | Run ESLint |
