# JAY VU. — Work & Projects v5.3.1 | Changelog & QA

## Approved choices
- Layout A: Editorial Cards, 2 columns desktop / 1 column mobile
- Detail A: Challenge → My Contribution → Outcome (balanced)
- Metrics A: KPI highlight with before/after and qualifying context
- Cost A: show only ~90% reported storage-cost reduction, with caveat; omit 100% printing-cost claim
- Sync A: Work, Homepage, About, Stories EN/VI

## Changes
- Rebuilt the six existing Work case studies in English and Vietnamese with consistent structured narratives and visible metrics.
- Distinguished reported outcomes (5.1× recorded feedback, 75% processing-time reduction, ~90% storage-cost reduction) from scope indicators (four business units, 5,000+ users).
- Retained the already synchronized Homepage, About and Stories pages from verified v5.3 source; did not add unsupported new metrics to those pages.
- Preserved the Green Global Mar 2018–Jul 2020 and Softone Dec 2020–Dec 2021 timeline, as well as ECRM Feb–Sep 2024, Pi Group Oct 2024–Aug 2026, and New Pine Aug 2026–present.
- Preserved original Life Road JavaScript, image artwork, milestones, and page structure.
- Added scoped CSS `assets/brand-v5/work-v5.3.1.css`; did not modify global CSS or JavaScript.

## QA scope
- Static validation: six cards per language, matching KPI and narrative structure, correct dates, relative paths, original Stories assets unchanged.
- Browser visual QA at 375/768/1440 is NOT certified in this package; review in browser before deployment.
- Embedded `documents/Tran_Van_Ha_CV.pdf` remains the original PDF from the v5.3 source and may contain an outdated Green Global date. Do not assume it was updated.
- No GitHub deployment performed.
