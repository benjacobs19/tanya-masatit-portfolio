# Tanya Masatit — Marketing Portfolio

Two static portfolio designs for Tanya Masatit (marketing coordinator, Toronto). No build step.

| Version | Path | Style |
|---|---|---|
| 1 | `index.html` | Editorial: Bodoni + camel and black, dark/light aware |
| 2 | `pink/index.html` | Pink, script-and-sans, modeled on a reference portfolio |

Live: <https://tanya-masatit.web.app/> and <https://tanya-masatit.web.app/pink/>

## Run locally

```bash
python3 -m http.server 8671
```

## Deploy (Firebase Hosting)

```bash
firebase deploy --only hosting:tanya
```

## Placeholders to replace

- Contact email (`hello@tanyamasatit.com`)
- Tha Phae Tavern bullet points and the software list
- The five project cover images in `assets/proj-*.jpg` are AI-generated stand-ins
