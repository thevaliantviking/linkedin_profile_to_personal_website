# Test checklist

- [x] Page loads with no console errors after all edits.
- [x] Nav: every visible nav button shows the correct, matching section; no button activates the wrong or a blank page.
- [x] Hidden sections (Blog, Portfolio, testimonials/clients, etc., as decided) are fully absent from the rendered page and from tab order — verify with keyboard Tab navigation that focus never lands on something invisible.
- [x] Keyboard-only pass: can reach and activate the sidebar "Show Contacts" toggle, every nav button, every social/contact link, and the contact form fields/button using only Tab/Shift+Tab/Enter/Space.
- [x] All `<img>` alt text is accurate and meaningful (avatar, any remaining icons) — no leftover "Richard hanrick" or placeholder text.
- [x] All links have meaningful, non-generic text (no bare "click here" or unlabeled icon-only links without an accessible name).
- [x] Color contrast unchanged/still passes (no new text-on-background combinations introduced).
- [x] Mobile viewport (≤480px) check: sidebar collapses correctly, "Show Contacts" toggle works, no horizontal overflow, remaining nav items fit or wrap properly with fewer tabs.
- [x] Tablet/desktop breakpoints still look correct after removing sections (no leftover empty gaps from deleted grid/flex children).
- [x] Contact form still can't submit anywhere real (`action="#"`) — confirms no backend was introduced.
- [x] No analytics/tracking scripts, cookies, or external data calls were added anywhere (grep the diff for `<script src=` and `fetch(`/`XMLHttpRequest`).
- [x] `LICENSE` file byte-for-byte unchanged; README still credits the original template/author.
- [x] New avatar image displays correctly at the sizes used in both the sidebar (80px) and, if referenced elsewhere, any other size.
- [x] Validate `index.html` doesn't have leftover orphaned `data-nav-link`/`data-page` pairs (count of nav buttons === count of page articles).
