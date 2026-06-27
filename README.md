# Elite Landing Page 

A premium, modern landing page built for **ESCARAE**, a digital agency specializing in fast, responsive, and secure web experiences. The page features rich typography, modular styling, and lightweight animations that bring the interface to life.

---

## FILES

- [index.html]: Document structure with semantic HTML5 elements.
- [style.css]: Vanilla styling, layout grids, variables, and responsive media queries.
- [script.js]: Scroll events, mobile navigation drawer controls, and form handling.

---

##  Features & Functionality

1. **Responsive Navigation Menu**:
   - Includes a logo, header navigation links, and a mobile hamburger menu (`☰`).
   - Toggles into a responsive layout drawer on mobile viewports. Clicking a link closes the drawer automatically.
2. **Interactive Call-to-Action Buttons**:
   - Micro-interactions added to all button clicks (scales down slightly and returns to normal state on click).
3. **Scroll Reveal Animation**:
   - Uses custom JavaScript to monitor viewport scrolls and toggle the `.active` class on `.reveal` elements (Features, About Us, Reviews, Contact).
   - Elements slide upward and fade in smoothly as they enter the browser viewport.
4. **Interactive Contact Form**:
   - Submissions are intercepted via JavaScript (`e.preventDefault()`).
   - Validates input entries and triggers a confirmation message alert (`Message Sent Successfully 🚀`).

---

##  Technology Stack

- **Structure**: Semantic HTML5 (header, nav, section, footer, grids)
- **Styling**: Vanilla CSS3, custom CSS variables, Poppins font from Google Fonts
- **Interactivity**: Vanilla JavaScript (ES6)

---

##  How to Run

Open [index.html] directly in your browser. 

```
