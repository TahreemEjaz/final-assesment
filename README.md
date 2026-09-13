# PHEC scholarship landing page

Open `index.html` directly in a browser. No build step, internet connection, JavaScript, or Bootstrap JavaScript is required. All Bootstrap CSS, fonts, photos, logos and exported icons are local in `assets/`.

The page was reconstructed from `Assessment - LP.fig` because the Figma connector denied access to the shared online file. The local file supplied the 1920 × 5913 layout, text, colors, image references and original vector path data. Responsive layouts were added for tablet and mobile.

## Files

- `index.html`: semantic HTML and Bootstrap layout classes.
- `style.css`: design styling, responsive layouts and CSS-only interactions.
- `assets/`: images used by the page, exported Figma vector icons, fonts and Bootstrap 5.3.8 CSS, with applicable licenses.

## Static interactions and content

- Mobile navigation, FAQs and the expanded ranking table use native `details` / `summary` elements.
- The form uses native required-field validation. Submitting opens eligibility guidance, not an automatic eligibility determination. University/program options are examples based on the design's ranking cards, not a verified eligibility database.
- No application or login endpoint was supplied. Apply Now and Login open a contact panel using the contact details shown in the design. Replace those links with the actual portal URL when available.
- FAQ answer copy was added because the design included question labels but used a cropped example website image beneath them. It refers to the supplied criteria and directs unresolved questions to PHEC.
- Social icons have no external destinations because the design supplied no profile URLs.
- The repeated “100% Scholarship Coverage” heading and the associated details-card descriptions are preserved from the design. Ranking values and scholarship criteria are design content, not independently verified current program information.
- Fonts and Bootstrap include their licenses under `assets/fonts/` and `assets/vendor/`.
