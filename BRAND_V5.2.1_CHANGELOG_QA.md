# JAY VU. v5.2.1 — CHANGELOG & QA REPORT

## Scope
- Fix root cause of white/light text on the light Career Snapshot background, both EN and VI.
- Explicitly preserve dark background and light text for Career Journey.
- Add scoped light/dark color rules for homepage sections, hero, project cards, footer, and Stories.
- Improve chip labels and mobile layout safeguards.
- Preserve HTML text, images, Life Road artwork, 8 chapters, 4 milestones, and JavaScript.
- Cache-bust shared stylesheet reference to v5.2.1.

## Verification performed
- Static inspection of HTML and stylesheet references; check all 12 main EN/VI pages.
- Confirmed internal CSS references exist.
- Compared unchanged JavaScript and artwork to v5.2 source.
- No GitHub deployment.

## Verification NOT performed
- No real browser screenshot QA at 375/768/1440px; this remains required before production signoff.
- No computed-style or automated WCAG contrast audit across rendered DOM.
- No live deployment parity verification.

## Unresolved editorial items
- Any disputed employment dates and degree-awarding details require user verification; not altered.
- Any untranslated prose is not silently rewritten in this technical color-fix build.

## Static audit warnings
- None detected

## Changed files
- vi/index.html
- en/index.html
- assets/brand-v5/brand-v5.2.css
- en/about/index.html
- en/contact/index.html
- en/work/index.html
- en/education/index.html
- en/stories/index.html
- vi/about/index.html
- vi/contact/index.html
- vi/work/index.html
- vi/education/index.html
- vi/stories/index.html
