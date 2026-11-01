# ShiftNest PA#2 Prototype

## 1. Team

| Team member | Student ID | Role |
|---|---:|---|
| Phan Lê Anh Minh | 24127082 | Team Leader |
| Hồ Phan Như Nguyệt | 24127211 | Team Member |
| Huỳnh Thái Hoàng | 24127171 | Team Member |

## 2. How to Open

ShiftNest is planned as a static HTML5 and CSS3 prototype with no build step, framework, backend, or JavaScript dependency. After the screen markup is implemented, open `index.html` directly in a modern browser to start the main flow. The repository currently contains the target HTML files, but they are empty, so the working prototype is not yet available.

## 3. Screens

The prototype covers one three-step shift-transfer flow: Nguyet sends a request to Hoang, Hoang accepts or declines it, and Minh reviews an accepted request as the shift leader. Nguyet remains assigned to the shift until final approval.

| File | Screen | Actor and purpose | Current status |
|---|---|---|---|
| `index.html` | Send Transfer Request | Nguyet, the employee and sender, selects Hoang and submits the transfer request. | Empty; implementation planned |
| `respond-to-request.html` | Respond to Request | Hoang, the employee and receiver, reviews the request and accepts or declines it. | Empty; implementation planned |
| `review-and-approve.html` | Review & Approve | Minh, the shift leader and approver, reviews the accepted transfer and approves or rejects it. | Empty; implementation planned |

## 4. Changed Since PA#1

The original PA#1 references are preserved unchanged in `docs/pa1/`. The approved revised wireframes are stored separately in `docs/revised-wireframes/` and clarify the same main flow rather than adding new screens.

The revised designs add explicit step, actor, and role labels on all three screens so the current user's responsibility is unambiguous. They make the Nguyet → Hoang → Minh sequence clearer in headings and supporting text, state that Nguyet remains assigned until approval, and correct the original Screen 3 request ID from `REQ-2024-8841` to `REQ-2026-8841` so its year matches the 2026 shift. Status wording and decision guidance were also refined to make the consequences of each action easier to understand. These revisions address the recorded PA#1 feedback and are present in the approved wireframes, but they have not yet been implemented in HTML.

## 5. Not Wired Yet

The three HTML pages and their screen-specific stylesheets are currently empty. Main-flow links and the final responsive screen layouts are therefore not wired yet. This is a static prototype: form submissions, authentication, notifications, schedule updates, conflict detection, and persistent approval state will not connect to a backend. W3C validation, accessibility and keyboard testing, JavaScript-disabled checks, responsive checks at 360px, 768px, and 1280px, and full-page screenshots are pending; no completion is claimed for these items.

## 6. CSS

`styles/base.css` contains the shared mobile-first design foundation: grayscale color tokens, system typography, the 4–48px spacing scale, borders and radii, fluid containers, header and navigation styles, cards, form controls, buttons, status indicators, and visible focus treatment. It uses responsive breakpoints at 768px and 1024px and 44px minimum control heights. Screen-specific layout and presentation are planned for `styles/screen-1.css`, `styles/screen-2.css`, and `styles/screen-3.css`; those files are currently empty. The completed pages must support 360px, 768px, and 1280px viewports without horizontal overflow.
