# Changelog

## 1.1.0 (18 November 2026)

- Licence changed from the GNU GPL v3 to the MIT License
- New logo: a magnifying glass revealing a redacted line, with separate light and dark versions
- The logo adapts to light and dark themes automatically
- Browser-tab icon for the app and the user guide
- New start-screen illustration: requests stream in as light-trails, then one is redacted;
  plays once and respects the system's reduced-motion setting
- Logo in the About window and the user guide header

## 1.0.0 (15 October 2026)

First release: a complete rewrite of the earlier 0.1 prototype.

- Request table with sorting, filters, search syntax and virtual scrolling for large captures
- Capture timeline with drag-to-filter and click-to-select
- Detail tabs: overview, headers, payload, response, cookies, timings, sensitive data and raw entry
- Sensitive data scanner with built-in rules, custom text and pattern rules, and a rule tester
- Masking with configurable labels such as `[REDACTED]` and `[SENSITIVE DATA]`
- Exports: diagnostic report (Markdown, text, JSON), sanitised HAR, sensitive data list,
  request CSV and a ZIP of response bodies
- Copy as cURL, fetch or URL
- Hash-pinned Content Security Policy, no network access, no third-party code
- User guide with screenshots, linked from the app
- About and licence window with the full GNU GPL v3 text
