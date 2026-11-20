# Kotoba ことば — Japanese Learning Adventure (Demo)

A mobile-first Progressive Web App (PWA) for beginner Japanese learners, designed around a visual island-adventure progression map.

## Highlights

- **Island Adventure Progression**: Structured learning path (`Journey`, `LessonPlayer`, `Review`, `Library`, `Profile`) guiding learners from their first lesson step-by-step.
- **Audio-Assisted Practice**: Interactive pronunciation playback (`AudioButton`) paired with vocabulary and sentence drills.
- **Offline-Ready PWA**: Built with Workbox service worker (`sw.js`) and `manifest.webmanifest` for installable mobile usage and offline caching.
- **Static Deployment Ready**: Zero-backend static bundle (`index.html` + `assets/`), deployable directly to GitHub Pages or Vercel.

## Project Structure

```text
kotoba-forge-demo/
├─ index.html              # Application entry point
├─ manifest.webmanifest    # PWA manifest & app icons
├─ sw.js                   # Workbox service worker
├─ art/                    # Island & character illustrations
└─ assets/                 # Bundled JS/CSS modules (Journey, LessonPlayer, Review, Library)
```

## Local Preview

Serve the directory with any static HTTP server:

```bash
npx http-server -p 8080 -c-1
```

Then open `http://localhost:8080` in a browser (recommended: mobile viewport).
