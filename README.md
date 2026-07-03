# Alexandra Yaen — Interactive Resume ⚡🍵

An interactive, single-page resume for Alexandra Yaen, electrical engineering
student at The George Washington University.

**Live site:** https://alexandrayaen.netlify.app

## The concept

PCB solder mask and ceremonial-grade matcha are basically the same color —
so the whole site is styled like a matcha-colored circuit board:

- Animated PCB traces with traveling current pulses in the background
- Experience timeline routed like a copper trace with solder-pad nodes that light up
- Skills displayed as IC chips, contact info as a pin header
- A whiskable matcha bowl (click it!), a matcha-level meter, and a lab-lights dark mode
- Zero dependencies — one HTML file, vanilla CSS + JS

## Development

No build step. Open `index.html` in a browser, or:

```sh
npx serve .
```

## Deploy

Deployed to Netlify:

```sh
netlify deploy --prod --dir .
```
