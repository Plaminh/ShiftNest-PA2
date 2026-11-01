# AI Usage Log — ShiftNest PA#2

## 2026-10-28 — Initial Repository Setup

**Tool:** ChatGPT (guidance); Git and PowerShell (manual execution).

**Asked for:** Guidance on creating the ShiftNest PA#2 repository, defining project rules, initializing the required structure, and preserving the original PA#1 wireframes.

**Kept:** The static HTML5/CSS3 architecture, initial project rules, required documentation files, and three-screen scope.

**Changed:** Created `AGENTS.md` (`38cbc02`), initialized the project structure (`b001a0f`), and added the original PA#1 design references (`14de5d2`).

**Rejected:** No documented rejection.

**By hand:** Created and connected the GitHub repository, executed Git and PowerShell commands, organized project files, and pushed the initial commits.

## 2026-11-01 — Shared Design System

**Tool:** Codex 5.6 Sol (VS Code).

**Asked for:** Refine `AGENTS.md` and implement a reusable, mobile-first CSS foundation for all three screens without implementing the HTML pages.

**Kept:** The grayscale palette, system typography, spacing scale, responsive containers, reusable header and navigation, cards, forms, buttons, status indicators, visible focus styles, and 768px/1024px breakpoints.

**Changed:** Expanded `AGENTS.md` with scope, accessibility, validation, and collaboration rules. Implemented shared design tokens and components in `styles/base.css`. An initial patch application failed and was successfully reapplied.

**Rejected:** No design proposal was rejected. The patch failure was a technical issue, not a design decision.

**By hand:** Submitted the implementation prompt, inspected the generated changes, and retained responsibility for reviewing and committing the shared foundation.

## 2026-11-01 — Repository and Design System Audit

**Tool:** Codex 5.6 Sol (VS Code).

**Asked for:** Perform a read-only audit of repository structure, Git history, project rules, shared CSS, PA#2 rubric compliance, PA#1 references, and readiness for screen implementation.

**Kept:** The audit findings confirming that shared project rules and CSS existed while the three HTML screens remained unimplemented and browser verification was pending.

**Changed:** No repository files were modified. The audit identified incomplete documentation, an unrelated staged `.vscode/settings.json`, and the historical `REQ-2024-8841` identifier in the original PA#1 approval screen.

**Rejected:** No documented rejection.

**By hand:** Requested the audit, reviewed the findings, and identified the necessary cleanup before implementation.

## 2026-11-01 — Wireframe Review and Reference Preservation

**Tool:** Figma (manual design editing); ChatGPT (design review and organization guidance).

**Asked for:** Review the revised wireframes against lecturer feedback and retain both the original PA#1 designs and the improved references for PA#2 implementation.

**Kept:** The original three-screen transfer workflow, grayscale visual direction, and sender–receiver–approver sequence.

**Changed:** Revised the designs to explicitly identify Nguyet as Sender, Hoang as Receiver, and Minh as Approver. Corrected the Screen 3 request ID from `REQ-2024-8841` to `REQ-2026-8841`, clarified approval responsibilities, and stated that Nguyet remains assigned until final approval. Preserved the original references in `docs/pa1/` and stored revised exports separately in `docs/revised-wireframes/`.

**Rejected:** No documented AI design suggestion was rejected. Keeping separate original and revised references was adopted to preserve design history and support the required PA#1 comparison.

**By hand:** Revised the Figma designs, exported the updated wireframes, organized their repository locations, and checked that the original PA#1 images remained unchanged.

## 2026-11-01 — Documentation Maintenance

**Tool:** Codex 5.6 Sol (VS Code).

**Asked for:** Update `brief.md`, `AI-LOG.md`, and `SELF_ASSESSMENT_REPORT.md` using available development history, repository evidence, and the PA#2 rubric.

**Kept:** Chronological prompt history, evidence-based AI usage records, the seven rubric criteria, and explicit pending verification states.

**Changed:** Updated the three documentation files and corrected wording that could imply an undocumented AI suggestion had been rejected.

**Rejected:** Unsupported rejection claims were excluded because the available records did not establish those decisions.

**By hand:** Defined the documentation requirements, reviewed the output, and retained responsibility for Git operations.

## 2026-11-01 — Conversation and Development History Audit

**Tool:** Codex 5.6 Sol (VS Code).

**Asked for:** Recover accessible AI prompts, compare them with Git commits and diffs, identify missing evidence, and evaluate the accuracy of `brief.md` and `AI-LOG.md`.

**Kept:** Recoverable original prompts and the distinction between manual repository setup, AI-assisted implementation, read-only audits, and documentation tasks.

**Changed:** No repository files were modified. The audit clarified which original prompts were verifiable and identified incomplete provenance for certain file renames and local artifacts.

**Rejected:** No documented rejection.

**By hand:** Requested the audit and reviewed the resulting report against the project's known development history.

## 2026-11-01 — Documentation Refinement

**Tool:** Codex 5.6 Sol (VS Code).

**Asked for:** Refine existing documentation by removing duplicated prompt records, preserving verified original prompts, correcting tool attribution, and aligning project descriptions with actual Git evidence.

**Kept:** Original recoverable prompts, chronological development records, rubric-aligned self-assessment content, and honest verification statuses.

**Changed:** Refined `brief.md`, `AI-LOG.md`, and `SELF_ASSESSMENT_REPORT.md`. Removed duplicated material and unsupported completion claims.

**Rejected:** Duplicate records and unsupported claims were excluded because they reduced accuracy and traceability.

**By hand:** Reviewed the revised documents and retained control over staging, commits, pushes, and merges.

## 2026-11-01 — PROTOTYPE Documentation

**Tool:** Codex (VS Code).

**Asked for:** Prepare `PROTOTYPE.md` using the project structure, original PA#1 references, approved revised wireframes, shared CSS, and actual implementation progress.

**Kept:** The six required sections, correct team information, Nguyet-to-Hoang-to-Minh workflow, direct-file opening instructions, and explicit prototype limitations.

**Changed:** Created `PROTOTYPE.md` describing the planned screens, design revisions, CSS architecture, and work not yet implemented or verified.

**Rejected:** No documented rejection.

**By hand:** Supplied the requirements, reviewed the document's scope, and retained responsibility for subsequent Git operations.

## 2026-11-01 — Phase 1 Final Audit and Documentation Revision

**Tool:** Codex (VS Code).

**Asked for:** Audit the Phase 1 repository, verify original and revised wireframes, review the shared design foundation, and revise the four authorized Markdown documents for factual consistency.

**Kept:** Verified project rules, reusable CSS architecture, approved three-screen workflow, preserved original references, separate revised references, and pending implementation and testing statuses.

**Changed:** Updated `PROTOTYPE.md`, `brief.md`, `AI-LOG.md`, and `SELF_ASSESSMENT_REPORT.md`. Clarified the original and corrected request IDs, improved cross-document consistency, and aligned the self-assessment with the required report structure.

**Rejected:** No new design suggestion was rejected. Unsupported completion claims remained excluded because implementation and verification evidence was not yet available.

**By hand:** Requested the audit, reviewed its findings, and confirmed the intended separation between original PA#1 references and revised PA#2 wireframes.

## 2026-11-01 — Team Leader Review and Project Rules Clarification

**Tool:** ChatGPT (review guidance); VS Code and Git (manual review).

**Asked for:** Review `AGENTS.md` and `styles/base.css` before committing the shared project foundation, identify potential issues, and clarify the static-prototype requirements.

**Kept:** The three-screen scope, semantic HTML conventions, shared CSS design system, responsive requirements, accessibility guidelines, and feature-branch workflow.

**Changed:** Clarified `AGENTS.md` to require functional main-flow navigation without JavaScript while allowing illustrative business action controls. This prevents the static prototype from falsely implying that requests are actually submitted, approved, rejected, or persisted. Identified tablet header density and small-text sizing as points to verify during rendered screen testing.

**Rejected:** No documented AI suggestion was rejected. Additional speculative CSS changes were deferred until an implemented screen could be tested.

**By hand:** Reviewed the project rules and shared CSS, applied the approved rules clarification, inspected the relevant Git changes, and managed the commit process independently.

## 2026-11-01 — Screen 3: Review & Approve

**Tool:** Codex 5.6 Sol (implementation and refinement assistance); W3C Nu validator and Microsoft Edge headless rendering during earlier review.

**Asked for:** Implement Screen 3 from the approved revised wireframe, correct sample-state and responsive risks, then perform a final targeted refinement of header consistency, typography, and accessibility while updating the AI records.

**Kept:** The approved Screen 3 structure and visual hierarchy; shared tokens and components from `styles/base.css`; semantic landmarks; relative navigation; one `h1`; accessible labeling; request `REQ-2026-8841`; sender Nguyet, receiver Hoang, and approver Minh; decision guidance; and illustrative Approve/Reject controls without backend behavior.

**Changed:** Implemented the Screen 3 HTML and mobile-first CSS. Follow-up review labeled approval and availability checks as historical sample data, corrected time-sensitive wording, clarified hypothetical production validation, and strengthened narrow-screen wrapping. Final refinement added the approved “My Store” header context, retained only the three valid workflow links, made navigation labels consistent, and raised section labels, detail labels, person roles, sample notes, form hints, and status text to at least 16px through screen-specific CSS. A fresh W3C Nu check of the refined HTML returned no messages.

**Rejected:** No documented rejection.

**By hand:** The team leader supplied the approved reference and implementation requirements, reviewed the initial result, requested the sample-state, responsive, header, and typography refinements, and retained responsibility for staging and all Git operations. Strict UTF-8 decoding of the refined HTML found no replacement characters. Earlier headless renders covered 768px and 1280px but predate the final refinement. Reliable 360px rendering, final viewport rechecks, full-page screenshots, keyboard testing, CSS validation, and accessibility testing remain pending.
