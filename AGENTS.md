# Workspace Guide

## Project shape
- This is a collection of standalone HTML/CSS/JavaScript exercises, not a single bundled application.
- Root HTML files include practice pages and forms. `SIH/` contains separate project pages.
- `style.css` and `script.js` are shared by pages that explicitly include them; other pages may keep styles or scripts inline.

## Editing conventions
- Keep changes scoped to the page or exercise being worked on. Do not assume every HTML page shares the same design or behavior.
- Preserve the existing plain HTML, CSS, and browser JavaScript approach. Do not introduce a framework, build system, or dependency unless requested.
- Check the target page's existing asset references before changing shared CSS or JavaScript, since those files can affect multiple pages.

## Verification
- There is no configured package manager, build command, or automated test suite.
- For page changes, open the affected HTML file in a browser and verify the relevant layout and interaction. Check the browser console for JavaScript errors when scripts are involved.