# NFO1005 — Final readiness and testing status
Date: 6 November 2026

## Completed automatically (local checks)
- All five HTML files present: index, about, resume, portfolio, contact.
- Every page has a non-empty document title and a single H1 (earlier local audit).
- Internal file paths checked: no missing linked local pages, images, CSS, JS or PDF.
- Custom CSS parsed with tinycss2 without syntax parse errors.
- Navigation home active state corrected in previous version.
- Site contains a Bootstrap-based responsive layout and an interactive portfolio feature in the code.

## Not verified — do not tick as completed yet
- Official W3C Nu HTML validation (all five files) and W3C CSS validation.
- Visual browser testing in Chrome and Firefox: an attempted automated Chromium run was blocked by environment restrictions (ERR_BLOCKED_BY_ADMINISTRATOR); no successful browser test is claimed.
- Functional testing of external Bootstrap/CDN dependencies, modal interactions, social link destination, and email draft.
- Adobe Express authoring and export, Adobe Color colour-blindness check, Favicon.io generation.
- Two genuine user usability tests, feedback-driven changes, and two peer reviews.
- GitHub Pages publication and live-site test.
- Submission to vUWS.

## Actions for James
1. Extract the ZIP and open index.html in Chrome and Firefox; check the navigation, mobile view, portfolio popups, resume PDF and contact links.
2. Submit each HTML file to https://validator.w3.org/nu/ (File Upload) and css/custom.css to https://jigsaw.w3.org/css-validator/; save screenshots. Fix any errors before final submission.
3. Create and export the branded resume using Adobe Express, document the chosen palette and accessibility check in Adobe Color, and generate the final favicon in Favicon.io. Replace the relevant files.
4. Recruit two real testers. Record their devices, tasks, observations, and the changes actually made. Ask two classmates for peer review using the provided form.
5. Create a GitHub repository, upload the *contents* of james-lennox-portfolio at the repository root, then Settings > Pages > Deploy from branch > main / (root). Wait for the site URL and verify it.
6. Zip the final website folder and submit both the ZIP and live URL to vUWS before the course deadline.

## Authenticity checks
- Confirm the Instagram handle belongs to James; it is labelled as unconfirmed on the site.
- Confirm the university name, education dates and any coaching/leadership experience before adding them.
- The cricket statistics 13 wickets and best bowling 5/41 were confirmed by James in chat.
- No real coaching projects, testing results or university grades have been invented.

## Evidence log
| Check | Result | Evidence |
|---|---|---|
| Local HTML structure | Passed previous static audit | validation-report.md |
| Local CSS syntax parse | Passed | validation-report.md |
| Local assets and links | Passed | Local path audit, 6 Nov 2026 |
| Official W3C HTML/CSS | Not performed | Awaiting validator access |
| Browser render/interaction | Blocked | Chromium file navigation ERR_BLOCKED_BY_ADMINISTRATOR |
| User testing | Not performed | Requires actual participants |
| Deployment | Not performed | Requires GitHub account |
