# AIU Anveshan Simulations

Two Three.js "film" simulations of the SURAKSHA-LINK idea, plus the three reference
sheets that go with them. Everything is a plain static site — no build step, no server.

| Page | What it is |
| --- | --- |
| `index.html` | **Simulation 1** — SURAKSHA-LINK flood probes (mission B: city mesh & satellite backhaul) |
| `second.html` | **Simulation 2** — SURAKSHA-LINK short film (the quake, the collapse, the resilient message route) |
| `1.png` | Reference sheet for simulation 1 — sensor buoy |
| `2.png` | Reference sheet for simulation 1 — sensor pod, section |
| `3.png` | Reference sheet for simulation 2 — impact capsule |

## Navigating

Both simulations carry the same strip in the top-left corner (bottom-right on phones):

```
[ 1 ] [ 2 ] [ 3 ]      [ SIM 1 ] [ SIM 2 ]
```

* **1 / 2 / 3** (click or press the key) — open that reference image full screen.
  The film pauses while an image is open and resumes when you close it.
* **SIM 1 / SIM 2** (click, or press **I** / **S**) — jump between the two simulations.
* **Esc** (or **Close**) — close the image viewer. Clicking the dark area closes it too.
* The start card also has Image 1/2/3 and Simulation 1/2 buttons, so the whole site is
  reachable with the mouse alone.

Simulation keys are unchanged: **Space** play/pause · **R** replay · **H** hide interface ·
**← / →** step a second.

## Publishing with GitHub Pages

The site uses only relative paths, so it works from any sub-folder URL.

1. Push this folder to GitHub (`main` branch, files at the repository root).
2. On GitHub: **Settings → Pages → Build and deployment**.
3. Source: **Deploy from a branch**. Branch: **main**, folder: **/(root)** → **Save**.
4. Wait for the green "Your site is live" banner, then open
   `https://Deepak2344-coder.github.io/AIUAnveshanSimulations/`.

That URL opens simulation 1; the strip in the corner reaches simulation 2 and all three
reference images.
