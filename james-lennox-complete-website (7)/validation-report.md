# HTML and CSS validation report — James Lennox portfolio
Date: 6 November 2026

## Scope
Local static checks were run on index.html, about.html, resume.html, portfolio.html, contact.html and css/custom.css.

## Results
- All five HTML pages parsed successfully with the lxml HTML parser.
- All five pages have one H1 and a meaningful title.
- All locally referenced assets and linked pages were found; internal fragment references were checked.
- No duplicate IDs or missing image alt attributes were detected.
- The CSS was parsed with tinycss2: no stylesheet-level or declaration parsing errors were detected.
- Fixed: the Home navigation link now has active styling and aria-current="page" to match the other pages.

## Important limitations
These are LOCAL STATIC CHECKS, not official W3C Nu HTML or W3C CSS Validator certificates. The W3C validation website was unreachable from the execution environment (DNS resolution failed). CSS parsing is not the same as full CSS specification validation. Browser rendering, JavaScript behaviour, external links, colour contrast and accessibility were not comprehensively tested.

## Required final steps
1. Upload or paste each HTML file to https://validator.w3.org/nu/ and resolve any reported errors.
2. Submit css/custom.css to https://jigsaw.w3.org/css-validator/ and resolve any reported errors.
3. Test in Chrome and Firefox on desktop and mobile sizes, including navigation, modals and contact actions.
4. Record actual results and dates in the assessment UX/testing documentation. Do not report these local checks as W3C-certified validation.
