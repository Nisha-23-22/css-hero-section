# Laundry Services - Hero Section

Navbar and hero section for a laundry service web application, built with HTML and CSS only.

## Files

- `index.html` - page structure (navbar + hero section)
- `style.css` - all styling, linked from the HTML
- `laundry.png` - laundry related image shown in the right div
- `Readme.md` - this file

## What was done

- **Navbar:** logo on the left, links (Home, Services, About Us, Contact Us) in the centre, user's name on the right. Built with `display: inline-block` / `inline`, **no Flexbox**.
- **Hero section:** two divs.
  - Left div: heading, description and the "Book a service today!" button.
  - Right div: laundry image (washing machine with basket).
- **Viewport units:** `vw` / `vh` are used for sizes, spacing and fonts so the whole section fits the screen without scrolling (navbar 12vh + hero 88vh = 100vh).

## How to run

Keep `index.html`, `style.css` and `laundry.png` in the same folder and open `index.html` in a browser.
