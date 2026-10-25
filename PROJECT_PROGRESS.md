# Insight.IO progress

## Done
- Vite + React scaffold; first commit
- Design inventory from GIF/video (swap = wipe transition, PiP cross-fade)
- Folder structure, global tokens, Sidebar (in progress)
- move “Sidebar” and “StatusBar, top-left pills, mode toggle” 

## Decisions
- React + Vite + Three.js; inline SVG icons and no CDNs (offline requirement)
- Plain CSS with variables, one folder per component
- “mode state lives in App (the WASD pad needs it); QUICK GOAL and INITIATE are visual only, because the demo doesn’t show their behavior”.
## Next
- StatusBar, top-left pills, mode toggle, e-stop, WASD pad
- MainView (video + pcd) with wipe swap
