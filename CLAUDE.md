# Pochade Legal

Static HTML pages hosting the Privacy Policy and Terms of Service for the Pochade iOS app.

## Files

- `privacy-policy.html` — Privacy Policy page
- `terms-of-service.html` — Terms of Service page
- `support.html` — Support & FAQ page

## HTML Conventions

- **No build system, no dependencies, no tests.** Each file is a single self-contained HTML document.
- **Inline CSS** — all styles are written in a `<style>` block in the `<head>`.
- **Google Fonts** — loaded via `<link>` tags pointing to fonts.googleapis.com.
- **Dark mode support** — styles include a `@media (prefers-color-scheme: dark)` block that adjusts background and text colors.
