# swarajgajare.github.io

Personal portfolio site for Swaraj Gajare — Robotics & Mechatronics Engineer, MS Mechatronics & Robotics @ NYU. Hosted via GitHub Pages.

## Sections

- **About Me** — background
- **Research** — academic research work
- **Buggy Teleoperation Test** — ASAS Labs field test (drive-by-wire steering conversion), with video
- **Publication** — research output
- **Projects** — engineering work
- **Work Experience** — industry experience
- **Skills** — competencies
- **Contact**

## Structure

- `index.html` — single-page site (HTML/CSS/JS, no build step)
- `images/` — gallery and project images referenced by `index.html`
- `Buggy_Teleop_Test.mp4` — teleoperation test video

## Local development

Just open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Served directly from the `main` branch via GitHub Pages — any push to `main` updates the live site at `https://swarajgajare.github.io`.
