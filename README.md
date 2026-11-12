# WardTrack – Quarantine Centre Tracker (prototype)

Static app: no build step, no backend (data is kept in the browser's localStorage).

## Deploy on Vercel
Option A (CLI):  `npm i -g vercel` → `cd` into this folder → `vercel --prod` (framework: "Other", no build command, output dir = `.`)
Option B (dashboard): vercel.com/new → drag-and-drop this folder, or push to GitHub and import the repo.

## Demo
Pick Nurse / Doctor / Admin on the first screen. Use "Next day" and "Reset data" in the dark bar.
