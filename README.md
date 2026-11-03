# mbedeniel.github.io

Personal portfolio of Niel MBEDE, robotics engineering student (Université de Toulouse, UPSSITECH).

Live at **https://mbedeniel.github.io**

## How it is built

- One static page, `index.html`, with its CSS and JavaScript inline. No framework, no build step, no tracking.
- English by default, French with the EN / FR switch. Link straight to French with `?lang=fr`.
- Dark theme by default, light theme with the toggle. Both choices are remembered in the visitor's browser.
- The hero figure is a real extended Kalman filter run (range and bearing to three landmarks), drawn as inline SVG.
- Font: [Instrument Sans](https://github.com/Instrument/instrument-sans), self-hosted (SIL Open Font License, see `fonts/OFL.txt`).

## Editing

Every text appears twice, once per language:

```html
<p lang="en">English text</p>
<p lang="fr">Texte en français</p>
```

Edit both, commit, and GitHub Pages republishes within a minute or two.
