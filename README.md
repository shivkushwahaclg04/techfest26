# techFEST'26 | SLIET Longowal

### Submission for **Pixel Wizard** (Plexus, CSE) · techFEST'26

A complete, working website for **techFEST'26**, the annual technical fest of Sant Longowal Institute of Engineering and Technology (SLIET), held **20-21 October 2026**.

Built with plain **HTML, CSS and JavaScript**. There is no framework, no build step and no backend, so it opens instantly and runs anywhere.

---

## What I built (features)

### Content and discovery
- **14 event domains, 50+ events**, each with a description, team size and prize details
- **Event finder** with live search (by name, domain or keyword) and an Individual / Team filter
- **Prize chart** that compares prize money across domains
- **Schedule, sponsors, FAQs and contact** sections, plus a **robotics showcase gallery**
- Sticky navigation with smooth scrolling to every section

### Registration system (fully working, front-end only)
- **Sign up and log in**, with a profile for each user
- **Per-event registration** with team details for team events
- **Fee calculator** that works out the total for any number of participants, with hostel and SLIET-student options
- **Ticket generation** after registration, with a print option
- Everything is saved in the browser (`localStorage`), with an in-memory fallback if storage is blocked

### Design and experience
- **Light and dark theme** toggle
- **Fully responsive** layout for desktop, tablet and phone
- **Accessible** touches: labelled buttons, image alt text, and `prefers-reduced-motion` support that switches animations off

---

## What is unique

1. **An animated robot in the hero section.** It is not a static picture. The robot floats and "breathes", its **eyes glow and blink**, a **scanning light sweeps across its body**, and it **tilts in 3D to follow the cursor**. All of it is done with CSS and a few lines of JavaScript, with no animation library.
2. **The hero reacts to the mouse.** A light follows the pointer across the hero, and event cards respond to pointer movement.
3. **A real registration flow without a server.** Accounts, per-event registration, team details and printable tickets all work in the browser alone.
4. **Smart fee calculator.** Pricing updates instantly for group size, accommodation and SLIET-student status.
5. **Scroll-reveal animations** built on `IntersectionObserver`, so they run efficiently without scroll listeners.
6. **Theme-aware from the ground up.** Every colour comes from CSS variables, which is how the light and dark themes switch cleanly.
7. **Tiny and fast.** No dependencies apart from Google Fonts, and images are compressed to WebP.

---

## Tech stack
| Part | Used |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (variables, grid, flexbox, keyframe animations, masks) |
| Logic | Vanilla JavaScript (ES6) |
| Storage | Browser `localStorage` |
| Fonts | Google Fonts (Fraunces, Manrope) |

## Project structure
```
index.html          page content
style.css           styling, themes and animations
script.js           event data, registration logic and interactions
robot.webp          hero robot image (transparent background)
robotic-car.webp    showcase image: autonomous robotic car
robotic-hand.webp   showcase image: robotic hand
```

## Run locally
Keep all the files in the same folder and open `index.html` in a browser. No installation is needed.

## Notes
- This is a front-end project. Accounts and registrations stay in the visitor's own browser and are not sent to any server. No payment is processed.
- Fonts load from Google Fonts, so an internet connection is needed for the intended typography.
- Image credits: `robot.webp`, `robotic-car.webp` and `robotic-hand.webp` are used for demonstration. Check their licences and add credit before publishing publicly.
