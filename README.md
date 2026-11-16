# JENSENATOR

Half human. All compute. A fan-made parody site with a scroll-driven 4K orbit animation.

## Structure
- `index.html`: the whole site (HTML, CSS, JS in one file, no build step)
- `frames/`: 241 desktop frames (1920px) scrubbed by scroll
- `frames_sm/`: 241 mobile frames (960px), used below 900px width
- `fonts/`: self-hosted Alfa Slab One, Share Tech Mono, Inter
- `logo.png`, `logo-800.jpg`, `favicon.png`, `apple-touch-icon.png`, `og.jpg`

## Deploy
Static site. On Vercel: **Add New → Project → import this repo**, framework preset **Other**, no build command, output directory `./`.

Local preview: `python3 -m http.server` then open http://localhost:8000

## Disclaimer
Unofficial fan-made parody. Not affiliated with, endorsed by or sponsored by NVIDIA Corporation or Jensen Huang. NVIDIA, GeForce, CUDA and NVLink are trademarks of NVIDIA Corporation.
