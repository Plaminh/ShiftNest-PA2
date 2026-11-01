# ShiftNest — PA#2 Project Rules

## Scope

- Implement exactly the three PA#1 main-flow screens:
  - `index.html` — Send Transfer Request.
  - `respond-to-request.html` — Respond to Request.
  - `review-and-approve.html` — Review & Approve.
- Do not add application pages, alternate flows, backend behavior, or features outside these screens.
- Preserve all original PA#1 reference artifacts under `docs/pa1/`.
- Do not fabricate test evidence, screenshots, validation results, or `AI-LOG.md` entries.

## Technology stack

- Use semantic HTML5 and vanilla CSS3 only.
- Build static `.html` pages that run directly in a browser without a build step.
- Use a mobile-first responsive approach.
- Do not introduce React, Vue, another JavaScript framework, a backend, package manager tooling, or unnecessary dependencies.
- Do not add a dependency without team approval and a documented reason.
- Visible content and main-flow navigation must work when JavaScript is unavailable.

## HTML conventions

- Use `header`, `nav`, `main`, and `footer` landmarks where appropriate to the page content.
- Include exactly one `h1` per page and do not skip heading levels.
- Give every form control a visible, programmatically associated label.
- Give every `img` an `alt` attribute; use an empty value only for genuinely decorative images.
- Use relative `.html` URLs for navigation between the three screens.
- Use anchors for navigation and buttons for actions; do not use `onclick` navigation.
- Keep the DOM order logical and usable with a keyboard and screen reader.
- Do not use inline styles.

## CSS conventions

- Put shared tokens and reusable primitives in `styles/base.css`; keep screen-specific layout and presentation in the matching `screen-*.css` file.
- Use the shared custom properties and the 4, 8, 12, 16, 24, 32, 48px spacing scale.
- Support viewport widths of 360px, 768px, and 1280px without horizontal page overflow or clipped content.
- Do not hide layout defects with `overflow-x: hidden`.
- Keep body text at 16px or larger and standalone buttons and navigation links at least 44px tall.
- Maintain a text contrast ratio of at least 4.5:1 for normal text and a visible keyboard focus indicator.
- Avoid `!important`, fixed page widths, and arbitrary spacing values.
- Reuse shared classes where their semantics match instead of duplicating rules.

## Accessibility and validation

- All content and main-flow navigation must remain understandable and operable with JavaScript disabled.
- Static action controls may be illustrative and must not falsely imply that a request was submitted, approved, rejected, or persisted.
- Support keyboard-only use with a logical focus order and visible `:focus-visible` states.
- Preserve semantic names, labels, instructions, and status text; do not communicate meaning by color alone.
- Validate every completed HTML page with the W3C HTML validator and resolve all errors.
- Check CSS validity, text contrast, landmarks, heading order, labels, alternative text, keyboard navigation, and link destinations.
- Test each completed page at 360px, 768px, and 1280px and capture full-page screenshots with JavaScript disabled.
- Report only checks that were actually performed; list unperformed checks as pending.

## Git workflow

- Create an isolated feature branch for each developer task; do not commit feature work directly to the shared main branch.
- Keep commits focused and do not include unrelated files or generated artifacts.
- Open a Pull Request for review before merging.
- Require at least one teammate to review the Pull Request and address review feedback before merge.
- Recheck scope, navigation, accessibility, and validation evidence during review.
