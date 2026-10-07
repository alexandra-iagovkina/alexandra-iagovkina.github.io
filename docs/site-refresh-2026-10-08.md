# Website refresh — 8 October 2026

Based on the approved text and design audits and the latest `portfolio-preview-live` source at `54fbb26f869a6da4e773720ba5ef9515e6f9adc6`.

## Implemented

- Revised English copy across Home, Services, Method, Work, About, Contact and all ten case studies.
- Diagnostic as the primary entry point; original EUR fees preserved.
- Simplified dark / cream / red visual system, typography, spacing, page hierarchy and responsive layouts.
- Four method phases with eight steps and a clearly labelled illustrative Lácteo decision analysis.
- Self-initiated status, scope and future testing questions distinguish concepts from commissioned launches or measured outcomes.
- Edited case sequences: 85 retained image placements; all original asset files, logos and patterns unchanged. Noctra card now shows the product identity.
- Responsive image variants use actual image dimensions. Detail enlargement opens the original high-resolution image.
- Three required enquiry fields and optional context. Draft generation and copy fallback; no server submission, analytics or form storage added.
- Mobile navigation keyboard handling, skip links, labels, reduced-motion styles and legal page contents navigation.
- Updated document titles, descriptions and no-JavaScript fallback; preview noindex retained.
- Earlier commercial experience remains qualified as involvement in projects, without implying direct client relationships.

## Held pending factual answers

1. Diagnostic: session duration; whether comparison of alternatives, reasoned recommendation, open assumptions and a first-test plan are included in the written Blueprint. A full deliverable sample depends on these answers.
2. Venture Shaping: whether the practice conducts interviews / market research / pilots or only prepares a plan; who performs and pays for testing.
3. Portfolio production: authorship and method for imagery (own photography, AI, CGI, mockups and third-party materials), to add accurate credits.
4. Commercial experience: actual role, outputs and engagement relationship for each named company, and examples that may be shown.
5. VODA SODA / Sourish: brand architecture and exact relationship between the names visible in the artwork.
6. Noctra: original standalone logo and pattern source files for a clean identity board. Do not recreate the assets from mockups.
7. About: whether 10+ years of portrait photography and 3 years of astrological practice remain current. Existing 12+ design years retained.
8. Privacy and provider facts: operating status / jurisdiction, actual providers, enquiry retention, and handling of optional birth data. Existing substantive policy preserved pending confirmation.
9. Publication destination: main contains a different older website; confirm which live domain/version should ultimately be replaced. This refresh is a separately saved preview.

## Verification

- `node --check preview/site.js` and `node --check preview/projects.js` passed.
- `node scripts/check-preview.cjs` rendered all 19 routes and verified heading structure, links, local assets, 85 case images and enquiry body generation.
- Separate jsdom checks passed on all 19 pages: unique IDs, image sources, labels, mobile menu open/Escape/focus, required fields, prepared mailto draft and selected service. No enquiry was sent.
- Browser screenshots, real viewport layout and real device / mail application behavior have not been verified. The supported browser QA capability was unavailable; responsive code checks are not a substitute for visual review.

The root website and original portfolio assets are unchanged. No new contractual service commitments or claims of proven commercial results were added.
