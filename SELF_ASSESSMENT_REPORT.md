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

As of the supplied Git output on 2026-11-01, local `main` and `origin/main` both point to `8b92f6a`. The committed history includes project rules, revised wireframes, a shared responsive CSS foundation, and a commit titled `feat: implement PA2 prototype pages` (`870519c`). The contents and rendered behavior of those prototype pages have not been independently verified for this report. Four documentation files are modified locally and have not yet been committed in their latest form.

## 3. Rubric-Based Self-Assessment

| Criterion | Maximum | Claimed | Current evidence |
|---|---:|---:|---|
| Three linked PA#1 screens | 20 | TBD | Prototype-page commit `870519c` exists; actual markup, screen coverage, and relative navigation still require inspection. |
| Responsive design | 25 | TBD | Shared CSS foundation committed at `8b92f6a`; rendered testing at 360px, 768px, and 1280px is not yet evidenced. |
| Semantic and valid HTML | 20 | TBD | HTML conventions are defined in `AGENTS.md`; page semantics and W3C validation remain unverified. |
| Consistent and verifiable design | 10 | TBD | Original PA#1 references (`14de5d2`), revised wireframes (`69f85b7`), and shared CSS (`8b92f6a`) are in Git; rendered comparisons remain pending. |
| Brief and project rules | 10 | TBD | Project rules committed at `a718c63`; `brief.md` and `PROTOTYPE.md` have local documentation updates pending review and commit. |
| AI-LOG | 10 | TBD | `AI-LOG.md` records AI-assisted work; its latest local revision is not yet committed. |
| Git commit history | 5 | TBD | Seven commits are visible on `main` and `origin/main`; Pull Request and teammate-review evidence has not been provided. |
| **Total** | **100** | **TBD** | Final scoring awaits implementation review and verification evidence. |

No final rubric score is claimed at this stage.

## 4. Verification Evidence

| Verification item | Required scope | Status | Evidence |
|---|---|---|---|
| Responsive layout at 360px, 768px, and 1280px | All three pages | Pending verification | No browser screenshots or measurements provided for review. |
| JavaScript-disabled content and navigation | Main three-screen flow | Pending verification | No documented browser test results provided. |
| Horizontal overflow and clipped content | All required widths | Pending verification | No viewport inspection evidence provided. |
| W3C HTML validation | Zero errors per completed page | Pending verification | No validation results provided. |
| CSS validity | Shared and screen-specific stylesheets | Pending verification | No CSS validation results provided. |
| Accessibility and keyboard operation | Landmarks, headings, labels, alternative text, contrast, focus, and order | Pending verification | Conventions exist; page-level test evidence is unavailable. |
| Relative navigation links | Main three-screen flow | Pending verification | Link destinations and browser behavior have not been independently checked. |
| Full-page screenshots with JavaScript disabled | Three pages at three viewport widths (nine images) | Pending verification | No screenshot evidence provided. |

A commit message alone is not evidence that rendered behavior, validation, or accessibility checks have passed.

## 5. Development Evidence

### Committed Git History

The supplied `git log -8 --oneline` shows the following commits, listed from oldest to newest:

| Commit | Description |
|---|---|
| `38cbc02` | `chore: establish PA2 project rules` |
| `b001a0f` | `chore: initialize PA2 project structure` |
| `14de5d2` | `docs: add original PA1 screen designs` |
| `69f85b7` | `docs: add revised PA2 wireframe` |
| `870519c` | `feat: implement PA2 prototype pages` |
| `a718c63` | `chore: finalize project rules` |
| `8b92f6a` | `style: establish shared responsive design system` |

Both local `main` and `origin/main` point to `8b92f6a` in the supplied output. The exact file contents of commit `870519c` require source inspection before its functionality can be assessed. No Pull Request approval or teammate-review record was supplied.

### Local Documentation Changes

The supplied `git status --short` shows exactly four locally modified files:

- `AI-LOG.md`
- `PROTOTYPE.md`
- `SELF_ASSESSMENT_REPORT.md`
- `brief.md`

These changes are not included in the committed `HEAD` shown above. No staged or untracked entries appear in the supplied status output.

### Design Revision Evidence

The original PA#1 images under `docs/pa1/` were previously verified against their committed versions. Revised references under `docs/revised-wireframes/` explicitly identify Nguyet as Sender, Hoang as Receiver, and Minh as Approver. The revised Screen 3 changes the historical request ID `REQ-2024-8841` to `REQ-2026-8841` and clarifies that Nguyet remains assigned until final approval. These are verified design-reference changes, not proof of completed browser implementation.

## 6. What We Did Not Manage

- No verified browser evidence has yet been supplied for responsive rendering, JavaScript-disabled navigation, overflow, accessibility, keyboard behavior, or color contrast.
- W3C HTML and CSS validation evidence has not yet been supplied.
- The nine required full-page screenshots have not yet been supplied for review.
- The actual scope and quality of the pages introduced by `870519c` still need inspection against the approved revised wireframes.
- Pull Request and teammate-review evidence has not yet been confirmed, even though the listed commits are already present on `main` and `origin/main`.
- The latest changes to the four documentation files remain uncommitted.
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