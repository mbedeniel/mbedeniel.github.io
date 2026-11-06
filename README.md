# mbedeniel.github.io

Personal portfolio of Niel MBEDE, robotics engineering student (Université de Toulouse, UPSSITECH).

Live at **https://mbedeniel.github.io**

## How it is built

- One static page, `index.html`, with its CSS and JavaScript inline. No framework, no build step, no tracking.
- English by default, French with the EN / FR switch. Link straight to French with `?lang=fr`.
- Dark theme by default, light theme with the toggle. Both choices are remembered in the visitor's browser.
- The hero figure is a real extended Kalman filter run (range and bearing to three landmarks), drawn as inline SVG.
- Font: [Instrument Sans](https://github.com/Instrument/instrument-sans), self-hosted (SIL Open Font License, see `fonts/OFL.txt`).
- Tool logos: one SVG sprite, `icons.svg`, from [Simple Icons](https://simpleicons.org) (CC0) and [Devicon](https://devicon.dev) (MIT) for MATLAB and Gazebo. A logo is used with `<svg class="ic"><use href="icons.svg#python"/></svg>`.
- School and lab logos: `logos/`, taken from my own reports and slides. All logos are trademarks of their owners and are shown only to name the institutions and tools.

## Visit statistics

- Counted with [GoatCounter](https://www.goatcounter.com): no cookies and no personal data, so no consent banner. The counting script `count.js` is hosted here (ISC license) and loads after the page, so it never slows it down.
- Dashboard (login required): https://mbedeniel.goatcounter.com. The shortcut `/stats` opens it and stops counting the owner's own visits in that browser.
- Per-application links: add `?ref=name`, e.g. `https://mbedeniel.github.io/?ref=thales` (works with `&lang=fr`). The name shows up as the visit's source.
- Clicks are counted on elements that have a `data-goatcounter-click` attribute.

## Editing

Every text appears twice, once per language:

```html
<p lang="en">English text</p>
<p lang="fr">Texte en français</p>
```

Edit both, commit, and GitHub Pages republishes within a minute or two.
