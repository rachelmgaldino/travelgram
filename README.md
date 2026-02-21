# Travelgram

A responsive travel profile page UI with a photo grid, built with HTML and CSS.

## Overview

Travelgram is a static, single-page layout that mimics a social/travel profile experience (profile header, location/travel stats, and a gallery feed). This project highlights my ability to build a clean UI from a design using semantic HTML, modern CSS, and reusable layout patterns.

**Preview:**

![Travelgram preview](./assets/travelgram-demo.png)

---

## Features

- ✅ Profile header layout (avatar, bio, and quick stats)
- ✅ Responsive navigation (collapses on mobile)
- ✅ Responsive header layout (stacks on mobile)
- ✅ Responsive photo gallery using Flexbox + wrapping:
    - Mobile: 1 column (full width inside `16px` container padding)
    - Tablet: 3 columns (auto-sized via `calc()`)
    - Desktop: fixed-size tiles
- ✅ Clean navigation bar with icons and user avatar
- ✅ Design tokens with CSS variables + consistent typography

---

## Tech Stack

**Frontend:**

- HTML5
- CSS3 (Flexbox)
- SCSS (authored) + CSS (compiled)

**Other Tools:**

- Google Fonts (Poppins)

---

## Getting Started

### Prerequisites

- Any modern browser (Chrome, Firefox, Edge)
- (Optional) VS Code + Live Server extension
- (Optional) VS Code Live Sass Compiler (to auto-generate `.css` from `.scss`)

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/rachelmgaldino/travelgram.git
cd travelgram
```

2. **Run locally (choose one):**

- Open `index.html` directly in your browser, or
- Use VS Code Live Server and open `index.html`

### Editing Styles (SCSS)

This project is written in SCSS and compiled to plain CSS for the browser.

- Source: `styles/*.scss`
- Compiled output (committed): `styles/*.css`
- Sourcemaps (ignored): `*.css.map`

If you're using the VS Code **Live Sass Compiler**, start “Watch Sass” and edit the `.scss` files. The compiler will update the corresponding `.css` files automatically.

---

## Project Structure

```
travelgram/
├── index.html
├── styles/
│   ├── global.css / global.scss
│   ├── nav.css / nav.scss
│   ├── header.css / header.scss
│   ├── main.css / main.scss
│   ├── footer.css / footer.scss
│   └── index.css / index.scss
└── assets/
    ├── travelgram-demo.png
    ├── Logo.svg
    ├── icons/
    └── images/
```

---

## What I Learned

This project taught me:

- How to structure a profile layout with flexible containers and predictable spacing
- How to build an image gallery that maintains consistent sizing (`object-fit: cover`) while wrapping cleanly
- How to create breakpoints that feel consistent across devices (mobile/tablet/desktop)
- How to keep styles scalable using CSS variables and small, focused style files

---

## What I’d Improve

If I were to rebuild this project, I would:

- [ ] Improve accessibility (replace `alt="..."` placeholders with descriptive text and add visible focus states)
- [ ] Add an npm-based Sass build script (e.g. `sass --watch`) to standardize compilation (instead of relying on a VS Code-only workflow)
- [ ] Turn the navigation and footer items into real links/routes

---

## Contact

**Rachel Galdino**

- Email: rachel.galdino@proton.me
- LinkedIn: https://linkedin.com/in/rachel-galdino
- GitHub: https://github.com/rachelmgaldino

---

## Acknowledgments

- Design inspiration from a UI layout challenge / portfolio exercise
