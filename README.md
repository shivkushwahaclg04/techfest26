# techFEST'26 | SLIET Longowal

Website for **techFEST'26**, the annual technical fest of Sant Longowal Institute of Engineering and Technology (SLIET), held **20-21 October 2026**.

## Features
- 14 event domains with 50+ events, descriptions, team sizes and prizes
- Event finder with search and Individual / Team filter
- Prize chart by domain and a fee calculator
- Account signup and login, profile, per-event registration with team details, ticket with print option
- Animated hero with a robot, light and dark theme, responsive layout

## Project structure
```
index.html   page content
style.css    styling, themes and animations
script.js    event data, registration logic and interactions
robot.webp   hero robot image (transparent background)
```

## Run locally
Keep all four files in the same folder and open `index.html` in a browser. No build step is needed.

## Deploy on GitHub Pages
1. Create a new repository on GitHub (for example `techfest26`).
2. In this folder run:
   ```
   git init
   git add .
   git commit -m "Initial commit: techFEST'26 website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/techfest26.git
   git push -u origin main
   ```
3. On GitHub open **Settings > Pages**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then save.
4. After a minute the site is live at `https://<your-username>.github.io/techfest26/`.

## Notes
- This is a front-end project. Accounts and registrations are saved in the visitor's own browser (localStorage) and are not sent to any server, and no payment is processed.
- Fonts load from Google Fonts, so an internet connection is needed for the intended typography.
- Check the licence of `robot.webp` before publishing publicly and add credit to its author if required.
