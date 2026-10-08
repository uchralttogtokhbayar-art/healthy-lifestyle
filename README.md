# Healthy Lifestyle — a cinematic lecture

A university Human Development lesson on **healthy lifestyle**, built as an animated web presentation rather than slides: one continuous 3D particle world, live-drawn diagrams, counting numbers and interactive charts.

**▶ Open it:** https://uchralttogtokhbayar-art.github.io/healthy-lifestyle/

## Controls

| Input | Action |
| --- | --- |
| → · Space · click · scroll down | Next step / slide |
| ← · scroll up | Previous slide |
| Home / End | First / last slide |
| F | Fullscreen |
| N | Speaker notes |

Swipe on phones. Add `#18` to the URL to open slide 18.

Interactive moments: hover the rainbow model (slide 7), breathe with the circle (13), press → to morph the 21-day myth into the real habit curve and hover it (18), and run the 10-minute class timer (21).

## Structure

1. **The concept** — WHO definitions, the NCD burden, the Dahlgren & Whitehead rainbow model
2. **The pillars** — move, eat, sleep, mind, cut
3. **Human development** — emerging adulthood, stages of change, habit formation
4. **Put it to work** — a daily blueprint, class activity, debate and quiz

See [`CONCEPT.md`](CONCEPT.md) for the visual concept and the slide-by-slide motion plan.

## Tech

Plain HTML, CSS and JavaScript — no build step to run it. [GSAP](https://gsap.com) (with SplitText, DrawSVG and MorphSVG) drives the motion; [Three.js](https://threejs.org) renders the particle world. Fonts: Inter Tight and JetBrains Mono (SIL Open Font License), self-hosted in `fonts/`.
