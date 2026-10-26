# NPTEL Environment & Development — Practice Site

Static practice quiz site for NPTEL NOC26 HS216 (Weeks 0–12, 126 questions). No build step.

- **Learn** — every question with the correct answer highlighted
- **Practice a Week** / **Practice All** — optional option/question shuffling, instant feedback, mistake review, retry-mistakes mode, personal best saved locally
- Keyboard: `1–4` / `A–D` to answer, `←` `→` to navigate

## Files
- `index.html` — the site
- `data.js` — question bank (`DATA[week] = [{q, o: [4 options], a: index}]`)
- `vercel.json` — clean URLs + security headers

## Run locally

    npx serve .

## Deploy

Push to GitHub and import the repo in Vercel (Framework preset: **Other**), or run `npx vercel --prod` in this folder.
