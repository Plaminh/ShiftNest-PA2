# ShiftNest PA#2 Prototype

## 1. Team

| Team member | Student ID | Role |
|---|---:|---|
| Phan Lê Anh Minh | 24127082 | Team Leader |
| Hồ Phan Như Nguyệt | 24127211 | Team Member |
| Huỳnh Thái Hoàng | 24127171 | Team Member |

## 2. How to Open

ShiftNest is a static HTML5 and CSS3 prototype with no build step, framework, backend, or JavaScript dependency. Screen 3 can currently be opened directly by opening `review-and-approve.html` in a modern browser. `index.html` and `respond-to-request.html` remain empty, so the complete three-screen main flow is not yet available.

## 3. Screens

The prototype covers one three-step shift-transfer flow: Nguyet sends a request to Hoang, Hoang accepts or declines it, and Minh reviews an accepted request as the shift leader. Nguyet remains assigned to the shift until final approval.

| File | Screen | Actor and purpose | Current status |
|---|---|---|---|
| `index.html` | Send Transfer Request | Nguyet, the employee and sender, selects Hoang and submits the transfer request. | Empty; implementation planned |
| `respond-to-request.html` | Respond to Request | Hoang, the employee and receiver, reviews the request and accepts or declines it. | Empty; implementation planned |
| `review-and-approve.html` | Review & Approve | Minh, the shift leader and approver, reviews request details and approval guidance. Approve and Reject controls are illustrative only. | Initial HTML/CSS implementation present; full verification pending |

## 4. Changed Since PA#1

The original PA#1 references are preserved unchanged in `docs/pa1/`. The approved revised wireframes are stored separately in `docs/revised-wireframes/` and clarify the same main flow rather than adding new screens.

The revised designs add explicit step, actor, and role labels on all three screens so the current user's responsibility is unambiguous. They make the Nguyet → Hoang → Minh sequence clearer, state that Nguyet remains assigned until final approval, and correct the original Screen 3 request ID from `REQ-2024-8841` to `REQ-2026-8841`. These revisions address the recorded PA#1 feedback. Screen 3 now implements this revised content; Screens 1 and 2 are still pending.

## 5. Not Wired Yet

Screens 1 and 2, their screen-specific styles, and the complete main-flow navigation remain pending. Screen 3 navigation links are present, but two destinations are empty. Approval, rejection, persistence, authentication, notifications, schedule updates, and actual conflict or eligibility checks are not implemented; Screen 3 presents historical sample data and illustrative decision controls only. Full responsive acceptance, accessibility and keyboard testing, JavaScript-disabled flow checks, CSS validation, and required full-page screenshots remain pending. A session W3C Nu check returned no messages for Screen 3, but no retained submission evidence has yet been added under `checks/`.

## 6. CSS

`styles/base.css` provides the shared mobile-first foundation: grayscale tokens, system typography, the 4–48px spacing scale, fluid containers, navigation, cards, form controls, buttons, status indicators, focus treatment, and 768px/1024px breakpoints. `styles/screen-3.css` now implements the approval page layout, transfer path, detail panels, decision area, and responsive header behavior while reusing those shared primitives. `styles/screen-1.css` and `styles/screen-2.css` remain empty. Required support at 360px, 768px, and 1280px still needs final browser verification.
