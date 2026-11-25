# Web Dev I Lab Assignment 3 — Responsive Personal Portfolio Website

**Student:** Pranav Raj  
**Course:** B.Tech CSE Core  
**Assignment:** Responsive Personal Portfolio Website (CSS Advanced)

## Project overview

A one-page personal portfolio built with semantic HTML, modern CSS, and a small amount of JavaScript. The design includes a personal photo in the hero section, a responsive navigation bar, About, Skills, Projects, Contact, and Footer sections. It is designed to work across desktop, tablet, and mobile screens.

## Project files

- `index.html` — page structure, content, navigation, contact form, and interaction scripts.
- `styles.css` — design system, Flexbox, CSS Grid, responsive breakpoints, relative units, hover states, transitions, transforms, and keyframe animations.
- `pranav-raj-photo.jpeg` — profile photo displayed in the hero section.

**Important:** Keep all three files in the same folder. Do not rename the image unless you also update its `src` in `index.html`.

## How to run

1. Download and extract the ZIP file.
2. Open the extracted `portfolio_assignment_3` folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension in VS Code.
4. Keep an internet connection for the optional Google Fonts. System fallbacks are included if Google Fonts are unavailable.

## CSS concepts used

| Assignment requirement | Implementation |
|---|---|
| Flexbox | Header navigation, hero layout, section headings, contact layout, and footer alignment |
| CSS Grid | Skills cards, project cards, About layout, contact form fields, and footer layout |
| Media queries | Tablet breakpoint at `60rem`, mobile breakpoint at `42rem`, and small-phone adjustments at `25rem` |
| Relative units | `rem`, `%`, `vw`, `vh`, and flexible sizing with `clamp()`, `min()`, and `max()` |
| Hover effects | Navigation links, buttons, skill cards, project cards, and text links |
| Transitions and transforms | Smooth color changes, lifts, rotations, and hover movement |
| Keyframe animations | `fade-up`, `fade-in`, `role-glow`, and `float` |
| Accessibility | Semantic landmarks, image alt text, keyboard focus styles, skip link, menu labels, and reduced-motion support |

## Responsive testing

Use browser Developer Tools (device toolbar) to test these viewport widths:

- **375 px** — small mobile phone
- **430 px** — large mobile phone
- **768 px** — tablet portrait
- **1024 px** — small laptop / tablet landscape
- **1440 px** — desktop

Check that the mobile menu opens and closes, the hero text and photo stack neatly on narrow screens, cards adapt to the available width, and the contact form stays inside the viewport.

## Contact form note

The contact form validates the fields and prepares an email using the visitor's default email application (`mailto:`). It does **not** send or store messages on a server. A hosted contact form requires a backend or a form service.

## Before submission

1. The assignment brief asks you to build on Lab 2. Compare this version with your Lab 2 work and merge any required existing code before submission.
2. Test the website in a browser at the viewport widths listed above.
3. Check the navigation, image, email link, and GitHub project links.
4. Push `index.html`, `styles.css`, `pranav-raj-photo.jpeg`, and this README to your GitHub repository.
5. Share the repository link with your faculty.

## GitHub commands

Run these commands in the project folder after creating an empty GitHub repository:

```bash
git init
git add index.html styles.css pranav-raj-photo.jpeg README.md
git commit -m "Improve responsive portfolio - lab assignment 3"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the final repository URL with your actual repository URL.
