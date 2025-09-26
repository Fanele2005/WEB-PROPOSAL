## Change log (Part 2)

- 2025-09-26 — External stylesheet and base styles
  - Created `css/style.css` and linked it to all pages.
  - Moved inline `<style>` rules from HTML into `style.css`.
  - Implemented CSS reset and base theme variables (colors, typography, spacing).
  - Established desktop-first layout, using rem-based units for scalability.

- 2025-09-26 — Typography and accessibility
  - Applied consistent typography scale (headings, body, links).
  - Added improved link text for blog items for SEO and screen readers.
  - Included `aria-label` for primary navigation and social links.
  - Ensured descriptive `alt` text for images.

- 2025-09-26 — Layout structure (Grid & Flexbox)
  - Header uses Flexbox for alignment.
  - Services and Blog sections use CSS Grid for multi-column layouts on desktop.
  - About section uses Flexbox with responsive wrapping.

- 2025-09-26 — Visual styles and interactivity
  - Added button hover, focus, and active states (`:hover`, `:focus`, `:active`).
  - Introduced card styling with shadows and border radii.
  - Added gradient background for the hero section.

- 2025-09-26 — Responsive design
  - Implemented breakpoints at 1024px, 768px, and 480px using media queries.
  - Multi-column layouts gracefully collapse to single column on smaller screens.
  - Adjusted font sizes and spacing per breakpoint.
  - Navigation wraps for smaller viewports.

- 2025-09-26 — Responsive images and performance
  - Added `picture`, `srcset`, and `sizes` for hero and photos.
  - Applied `loading="lazy"` to non-critical images.
  - Ensured iframes have a title and are styled responsively.

- 2025-09-26 — README updates
  - Added screenshots for desktop, tablet, and mobile views (see `/docs/screenshots/`).
  - Updated references list with any new sources/tools.
