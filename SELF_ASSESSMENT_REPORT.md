# Self-Assessment Report — ShiftNest PA#2

## 1. Team Information

| Full Name | Student ID | Role |
|---|---:|---|
| Phan Lê Anh Minh | 24127082 | Team Leader |
| Hồ Phan Như Nguyệt | 24127211 | Team Member |
| Huỳnh Thái Hoàng | 24127171 | Team Member |

## 2. Project Overview

ShiftNest is a shift-management website for small cafés and bakeries. The CSC13008 PA#2 Responsive Prototype covers one three-screen shift-transfer flow: Nguyet submits a request, Hoang responds as the receiver, and Minh reviews an accepted request as the shift leader. Nguyet remains assigned to the shift until final approval.

The intended deliverable uses semantic HTML5 and vanilla CSS, without a framework, backend, package dependency, or build step. The original PA#1 references are preserved in `docs/pa1/`, while the approved revised designs are stored separately in `docs/revised-wireframes/`.

As of the verified Git output on 2026-11-01, `HEAD` is documentation commit `933f48c` on `feat/screen-3-approver`; local `main` and `origin/main` also point to `933f48c`. Screen 3 has an initial staged implementation in `review-and-approve.html` and `styles/screen-3.css`, followed by unstaged review corrections in those same files. Screens 1 and 2 and their screen-specific stylesheets remain empty. Commit `870519c` renamed two empty HTML files and did not implement their page content despite its title.

## 3. Rubric-Based Self-Assessment

| Criterion | Maximum | Claimed | Current evidence |
|---|---:|---:|---|
| Three linked PA#1 screens | 20 | TBD | Screen 3 has initial markup and relative links; Screens 1 and 2 remain empty, so the full linked flow is incomplete. |
| Responsive design | 25 | TBD | Shared CSS is committed and Screen 3 has mobile-first styles; reliable 360px and complete three-screen testing remain pending. |
| Semantic and valid HTML | 20 | TBD | Screen 3 uses semantic landmarks, one `h1`, labels, and buttons. A session W3C Nu response contained no messages, but retained evidence and the other screens are pending. |
| Consistent and verifiable design | 10 | TBD | Screen 3 follows the revised reference and shared CSS; full-page comparison and final screenshots remain pending. |
| Brief and project rules | 10 | TBD | Rules and earlier documentation are committed at `933f48c`; current documentation updates await review. |
| AI-LOG | 10 | TBD | `AI-LOG.md` records Screen 3 assistance and review corrections; the update is uncommitted. |
| Git commit history | 5 | TBD | Eight project commits are visible through `933f48c`; the Screen 3 work is not committed and PR/review evidence is pending. |
| **Total** | **100** | **TBD** | Final scoring awaits implementation review and verification evidence. |

No final rubric score is claimed at this stage.

## 4. Verification Evidence

| Verification item | Required scope | Status | Evidence |
|---|---|---|---|
| Responsive layout at 360px, 768px, and 1280px | All three pages | Pending verification | Screen 3 was visually inspected in headless Edge at 768px and 1280px; the attempted 360px render was unreliable, and Screens 1–2 are empty. |
| JavaScript-disabled content and navigation | Main three-screen flow | Pending verification | No documented browser test results provided. |
| Horizontal overflow and clipped content | All required widths | Pending verification | Screen 3 wrapping safeguards were reviewed; reliable 360px and full-page checks remain pending. |
| W3C HTML validation | Zero errors per completed page | Partial evidence | The W3C Nu service returned no messages for Screen 3 during the implementation session; no retained file exists under `checks/`, and Screens 1–2 are incomplete. |
| CSS validity | Shared and screen-specific stylesheets | Pending verification | No CSS validation results provided. |
| Accessibility and keyboard operation | Landmarks, headings, labels, alternative text, contrast, focus, and order | Pending verification | Conventions exist; page-level test evidence is unavailable. |
| Relative navigation links | Main three-screen flow | Pending verification | Screen 3 contains relative links to all three filenames, but the first two destinations are empty. |
| Full-page screenshots with JavaScript disabled | Three pages at three viewport widths (nine images) | Pending verification | No screenshot evidence provided. |

A commit message alone is not evidence that rendered behavior, validation, or accessibility checks have passed.

## 5. Development Evidence

### Committed Git History

The verified history contains the following project commits, listed from oldest to newest:

| Commit | Description |
|---|---|
| `38cbc02` | `chore: establish PA2 project rules` |
| `b001a0f` | `chore: initialize PA2 project structure` |
| `14de5d2` | `docs: add original PA1 screen designs` |
| `69f85b7` | `docs: add revised PA2 wireframe` |
| `870519c` | `feat: implement PA2 prototype pages` |
| `a718c63` | `chore: finalize project rules` |
| `8b92f6a` | `style: establish shared responsive design system` |
| `933f48c` | `docs: update project documentation` |

`HEAD` is `933f48c` on `feat/screen-3-approver`; local `main` and `origin/main` also point to that commit. Inspection of `870519c` confirms it contains only two zero-content renames. No Pull Request approval or teammate-review record was supplied.

### Local Screen 3 and Documentation Changes

The initial Screen 3 implementation is staged in:

- `review-and-approve.html`
- `styles/screen-3.css`

Follow-up corrections to the same files are unstaged. They distinguish historical sample checks from live validation and strengthen responsive wrapping. This documentation task also modifies:

- `AI-LOG.md`
- `PROTOTYPE.md`
- `SELF_ASSESSMENT_REPORT.md`
- `brief.md`

None of these current Screen 3 or documentation changes are included in `HEAD`.

### Design Revision Evidence

The original PA#1 images under `docs/pa1/` were previously verified against their committed versions. Revised references under `docs/revised-wireframes/` explicitly identify Nguyet as Sender, Hoang as Receiver, and Minh as Approver. The revised Screen 3 changes the historical request ID `REQ-2024-8841` to `REQ-2026-8841` and clarifies that Nguyet remains assigned until final approval. These are verified design-reference changes, not proof of completed browser implementation.

## 6. What We Did Not Manage

- Screens 1 and 2 remain empty, so the complete workflow is not implemented.
- Reliable 360px rendering, JavaScript-disabled flow, full-page overflow, accessibility, keyboard behavior, and color contrast remain unverified.
- A session W3C Nu check returned no Screen 3 messages, but retained W3C evidence and CSS validation are still pending.
- The nine required full-page screenshots have not yet been supplied for review.
- Screen 3 still requires final browser review against the approved revised wireframe after its staged and unstaged changes are reconciled.
- Pull Request and teammate-review evidence has not yet been confirmed, even though the listed commits are already present on `main` and `origin/main`.
- The Screen 3 implementation, review corrections, and latest documentation changes remain uncommitted.
- Backend processing, authentication, persistence, and real shift-conflict detection are outside the scope of this static prototype; illustrative controls must not imply that real business actions were completed.

## 7. What We Would Do Differently

- Preserve original PA#1 references and revised wireframes in separate directories from the beginning, with a short rationale for each approved change.
- Capture prompts, manual contributions, changes, and genuine rejections when they occur instead of reconstructing them later.
- Verify each implemented screen at all required viewport widths and record validation evidence before considering a feature complete.
- Keep implementation commits and documentation updates focused, with explicit Pull Request review evidence where required by the team workflow.

These reflections should be confirmed by the team leader before final submission.

## 8. Final Claimed Score

- **Total claimed score:** TBD / 100
- **Supporting evidence status:** Incomplete; implementation inspection and validation evidence pending
- **Submission ZIP filename:** TBD
