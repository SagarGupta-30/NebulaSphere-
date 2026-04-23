# NebulaSphere.

A futuristic, gesture-driven particle simulation running entirely from a single `index.html` front end.

## Features..
- Full hand-first control (after one-time activation):
  - `Open Palm`: Rotate + swipe spin impulse
  - `Pinch`: Zoom and energy shaping
  - `One Finger`: Next render mode
  - `Two Fingers`: Spectral hue shift
  - `Three Fingers`: Toggle immersive audio
  - `Thumbs Up`: Toggle autopilot
  - `Fist`: Nova burst
- Real-time particle engine with multiple simulation modes
- Layered WebAudio sound design (ambient, reactive motion, event effects)
- Responsive HUD for desktop and mobile

## Run Locally
Because camera access requires secure contexts, use localhost (not opening the file directly):

```bash
python3 -m http.server 4173
```

Then open:

```text```
http://localhost:4173
```

## Deploy to GitHub Pages
1. Push this project to a GitHub repository.
2. In GitHub, open `Settings -> Pages`.
3. Set source to `GitHub Actions`.
4. Push to `main` branch; workflow `.github/workflows/deploy-pages.yml` deploys automatically.

## Deploy to Vercel
1. Import the repository in Vercel.
2. Keep framework preset as `Other`.
3. Build command: leave empty.
4. Output directory: leave empty (root static deployment).
5. Deploy.

`vercel.json` is included for static route fallback to `index.html`.

## Notes
- Camera permission is required for gesture input.
- Use HTTPS in production; GitHub Pages and Vercel both provide this by default.
# NebulaSphere-
