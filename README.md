# Joseph Lee portfolio repo

This repo is the existing static site foundation for josephrlee.com. The portfolio rebuild will live here on top of the current dark-theme readme landing page.

## Structure

- `index.html` — current landing page shell, to be replaced with new portfolio homepage
- `assets/case-studies/` — generated screenshots for the 4 case studies
- `content/` — approved handoff source files (copy + layout intent)
- `README.md` — project notes

## Planned portfolio structure

- `/` — home page
- `/about.html` or `/about/index.html` — About page
- `/work/payments/` etc. — case study detail pages
- `styles.css` — centralized portfolio styling

## Notes

- Keep the existing dark theme, Typekit fonts, and deployment setup already in the repo.
- Use the `content/*.dc.html` mockups as source material, not as final production code.
- Use the generated case-study screenshots in `assets/case-studies/*` for the real visuals.
- Do not publish the internal `canvas.json` notes.
