# Accessible Component Patterns

A single dependency-free page (`index.html`) showing common interactive patterns built native-first, with ARIA only where needed, following the WAI-ARIA Authoring Practices.

## Components
- **Skip link and landmarks:** skip-to-content link, header, nav, main.
- **Disclosure menu:** button with `aria-expanded` and `aria-controls`; Escape closes it and returns focus to the button.
- **Tabs:** ARIA tablist with roving tabindex; arrow keys, Home and End move between tabs.
- **Dialog:** native `<dialog>` with `showModal()`: focus is trapped, Escape closes it, focus returns to the opener.
- **Validated form:** visible labels, hint linked with `aria-describedby`, `aria-invalid`, an error summary that receives focus, and a status message on success.
- **Visual:** visible focus outline, light/dark themes, reduced-motion support.

## Run
Open `index.html` in a browser, or enable GitHub Pages for the repository and open this folder's URL.

## Testing
TODO: add your own results (keyboard walkthrough, NVDA announcements for each component, axe scan, issues found and fixed).
