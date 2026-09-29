# Sparsh

Static site, no build step.

## Deploy
Option A: `npm i -g vercel && vercel --prod` inside this folder
 (Framework Preset: Other, no build command, output directory blank).
Option B: push to GitHub, import at vercel.com/new (same settings).

Files: index.html, sw.js (offline cache), vercel.json (headers), package.json.
