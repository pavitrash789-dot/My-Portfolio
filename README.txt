Pavitra Sharma – Portfolio Website (3D Animated Dark Edition)
=============================================================

WHAT CHANGED
- New cinematic dark theme: background #080808, electric blue (#6366F1) + neon cyan (#00E5FF) accents.
- Space Grotesk headings + Inter body text, glassmorphism sticky header, scroll progress bar.
- Animated preloader ("000% → 100%") that can never trap you behind it.
- Interactive 3D hero object (Three.js torus knot with neon lighting, mouse-follow, scroll-linked scale).
- Full expanded skill set in 6 tabs: Accounting & Finance, Excel & MIS, SQL & Data Analysis, Programming & Full-Stack, Learning & Exploring, Business & Process.
- 3D tilt on project cards, magnetic buttons, custom cursor on desktop, animated timeline glow, active-section nav indicator, mobile hamburger menu.
- Honors prefers-reduced-motion; falls back to a CSS orb when WebGL isn't available.

HOW TO RUN
1. Open index.html in any browser.
   - Works fully offline (fonts/3D library load from CDN when online; page still functions without them).
2. To publish free: drag the folder onto Netlify Drop, or push to GitHub Pages / Vercel.

HOW TO EDIT
- All text lives in index.html (headings, paragraphs, projects, experience timeline).
- Colours are the CSS variables at the top of the <style> block:
  --bg, --card, --ink, --muted, --accent (electric blue), --cyan (neon cyan).
- Skills list: see the "skills (full toolkit)" script near the bottom — edit the G object groups.
- Sample ledger data for the hero animation: the E array in the "ledger animation" script.
