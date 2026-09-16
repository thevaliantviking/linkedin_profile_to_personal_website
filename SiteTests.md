# Test checklist

- [ ] Page loads with no console errors after all edits.
- [ ] Nav: every visible nav button shows the correct, matching section; no button activates the wrong or a blank page.
- [ ] Hidden sections (Blog, Portfolio, testimonials/clients, etc., as decided) are fully absent from the rendered page and from tab order — verify with keyboard Tab navigation that focus never lands on something invisible.
- [ ] Keyboard-only pass: can reach and activate the sidebar "Show Contacts" toggle, every nav button, every social/contact link, and the contact form fields/button using only Tab/Shift+Tab/Enter/Space.
- [ ] All `<img>` alt text is accurate and meaningful (avatar, any remaining icons) — no leftover "Richard hanrick" or placeholder text.
- [ ] All links have meaningful, non-generic text (no bare "click here" or unlabeled icon-only links without an accessible name).
- [ ] Color contrast unchanged/still passes (no new text-on-background combinations introduced).
- [ ] Mobile viewport (≤480px) check: sidebar collapses correctly, "Show Contacts" toggle works, no horizontal overflow, remaining nav items fit or wrap properly with fewer tabs.
- [ ] Tablet/desktop breakpoints still look correct after removing sections (no leftover empty gaps from deleted grid/flex children).
- [ ] Contact form still can't submit anywhere real (`action="#"`) — confirms no backend was introduced.
- [ ] No analytics/tracking scripts, cookies, or external data calls were added anywhere (grep the diff for `<script src=` and `fetch(`/`XMLHttpRequest`).
- [ ] `LICENSE` file byte-for-byte unchanged; README still credits the original template/author.
- [ ] New avatar image displays correctly at the sizes used in both the sidebar (80px) and, if referenced elsewhere, any other size.
- [ ] Validate `index.html` doesn't have leftover orphaned `data-nav-link`/`data-page` pairs (count of nav buttons === count of page articles).
