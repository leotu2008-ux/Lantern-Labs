# Lantern Labs

Website for **Lantern Labs**: a room full of students building things, every week, with a demo night at the end of each semester. You own 100% of what you make: no equity, no fees, no strings.

Lantern Labs is a [Lantern](https://lantern.ventures) project.

**Live:** [lantern-labs-phi.vercel.app](https://lantern-labs-phi.vercel.app)

## The page

One static page, `index.html`, with no build step and no dependencies.

- **ASCII lantern:** the hero is a lantern drawn in monospace characters on a `<pre>`. Each lit cell starts as noise and resolves to its final character. A few cells keep flickering up and down the brightness ramp, like a flame.
- **Link hover:** link letters scramble, then resolve left to right.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
```

It deploys as-is to Vercel, Netlify or GitHub Pages.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The page: markup, styles and the lantern animation |
| `logo.png` | Lantern Labs logo |
| `brand/linkedin-company-banner*.png` | LinkedIn company banner (1x and 2x) |
