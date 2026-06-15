# Modern Dark-Themed Registration Form

A lightweight, high-performance, and responsive Registration Form built using vanilla HTML5, CSS3, and modern JavaScript (ES6+). It features a premium dark theme, glassmorphism UI elements, smooth micro-interactions, and instant client-side validation paired with a custom success popup modal.

---

 Features

Glassmorphism UI: Built with a modern dark aesthetics card component utilizing `backdrop-filter` blur effects, ambient background radial glows, and responsive styling.
Instant Validation: Secure client-side form logic built without heavy external libraries or frameworks to optimize load speeds.
Custom Success Modal: Smooth, CSS-animated success popup modal (`scale` and `opacity` driven) replacing the dated native browser `alert()`.
Highly Optimized Code: Written using short-hand syntax, clean utility arrow functions, and compact selectors to keep the footprint as minimal as possible.

---

 Tech Stack Used

HTML5: Semantic architecture with `novalidate` configuration to override default browser error flags.
CSS3: Flexbox layouts, absolute blurred background elements, smooth input focus transitions, and modular dark theme styling.
JavaScript : Arrow functions, rapid ternary checks, dynamic element class toggles, and regex patterns for fast email verification.

---

 Implemented Validation Rules

| Field | Rule | Error Message |
| :--- | :--- | :--- |
| Username | Minimum 3 characters, spaces trimmed automatically | Min 3 characters required. |
| Email | Validates against a modern `user@domain.com` regex pattern | Enter a valid email. |
| Password | Minimum 6 characters required | Min 6 characters required. |
| Confirm Password | Must explicitly match the primary password field | Passwords do not match. |

---

