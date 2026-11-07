# Architectural Landmarks Gallery

A responsive and accessible HTML5 photo gallery built for the **Final Project: Photo Gallery** assessment in Coursera's Advanced Styling with Responsive Design course.

## Live Demo

- **Live Site:** [View Photo Gallery on GitHub Pages](https://ekazadex.github.io/responsive-final-gallery/)
- **Repository:** [GitHub Repository](https://github.com/Ekazadex/responsive-final-gallery)

## Responsive Features & Specifications

- **Mobile View (Mobile First):** Single-column CSS Grid with a `10px` row and column gap without media queries.
- **Tablet View (`min-width: 772px`):** Dual-column layout, `50%` circular border-radius on figures, with the last figure spanning both columns (`grid-column: 1 / -1`).
- **Large Screen View (`min-width: 992px`):** Every 3rd figure spans across two columns (`figure:nth-child(3n)`), and border-radius is reset to `0`.
- **Accessibility (`prefers-reduced-motion`):** Smooth scroll behavior is removed (`scroll-behavior: auto`).
- **Dark Mode (`prefers-color-scheme: dark`):** Figures adopt a dark background, black border (`#000000`), and high-contrast yellowish text (`#fef08a`).

## Standards Compliance

- **W3C Nu Html Checker:** 0 errors.
- **WAVE Accessibility Tool:** 0 contrast errors and 0 accessibility alerts.

## Author

Created by Ekananda Zhafif Dean.
