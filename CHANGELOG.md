# Changelog


## 1.2.0 (19 November 2026)

- GitHub and Support links in the app's footer, its help window and the user guide
- Saving a response or exporting response files no longer stalls the page when a URL contains a long run of spaces or dots
- Screen-reader labels for the rule tester and the file picker; the capture timeline is announced as a labelled figure rather than an image, and the panel divider announces its position
- The start-screen illustration now uses its dark colours when dark mode is picked with the theme button, not only when it comes from the system setting
- Code clean-up after a SonarQube Cloud review, with no change in behaviour: the filter box parser, a pattern in the sensitive data rules and the user guide's note styles

## 1.1.0 (17 November 2026)

- Licence changed from the GNU GPL v3 to the MIT License
- New logo: a magnifying glass revealing a redacted line, with separate light and dark versions
- The logo adapts to light and dark themes automatically
- Browser-tab icon for the app and the user guide
- New start-screen illustration: requests stream in as light-trails, then one is redacted; plays once and respects the system's reduced-motion setting
- Logo in the About window and the user guide header

## 1.0.0 (14 October 2026)

First release: a complete rewrite of the earlier 0.1 prototype.

- Request table with sorting, filters, search syntax and virtual scrolling for large captures
- Capture timeline with drag-to-filter and click-to-select
- Detail tabs: overview, headers, payload, response, cookies, timings, sensitive data and raw entry
- Sensitive data scanner with built-in rules, custom text and pattern rules, and a rule tester
- Masking with configurable labels such as `[REDACTED]` and `[SENSITIVE DATA]`
- Exports: diagnostic report (Markdown, text, JSON), sanitised HAR, sensitive data list, request CSV and a ZIP of response bodies
- Copy as cURL, fetch or URL
- Hash-pinned Content Security Policy, no network access, no third-party code
- User guide with screenshots, linked from the app
- About and licence window with the full GNU GPL v3 text
