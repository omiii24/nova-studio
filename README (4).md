# Nova Studio — Responsive Digital Agency Landing Page

**Created by:** Om Pawar

Nova Studio is a static landing page for a fictional creative digital agency. It introduces the agency, presents its services, shares an About section, and provides a contact call-to-action.

## Project links
- **GitHub repository:** https://github.com/omiii24/nova-studio
- **Live website:** https://omiii24.github.io/nova-studio/

## Website sections
1. **Header / Navigation** — NOVA STUDIO logo and links to Home, Services, About, and Contact.
2. **Hero** — “Good Ideas Deserve Great Digital Experiences.” headline, description, Start a Project link, and circular “MAKE IT MATTER” graphic.
3. **Services** — Digital Strategy, UI/UX Design, and Web Development cards.
4. **About** — “Small Details. Big Difference.” heading and agency description.
5. **Contact** — “Let's Make Something Great.” call-to-action and Contact Us email link.
6. **Footer** — Copyright notice and “Designed with HTML & CSS.”

## Technologies
- HTML5 for semantic structure.
- CSS3 for styling, spacing, colors, and typography.
- Flexbox for navigation, hero alignment, and footer.
- CSS Grid for service cards and About layout.
- CSS media queries for responsive changes.

## Responsive breakpoints in the actual `style.css`
| Layout | Media query / width | Main behaviour |
|---|---|---|
| Wider screens | Default styles | Horizontal navigation, side-by-side hero, 3 service columns, 2 About columns |
| Tablet | `max-width: 900px` | Reduced hero spacing and graphic size; services use 2 columns |
| Mobile | `max-width: 600px` | Navigation wraps; hero stacks and centers; services use 1 column; About and footer stack |

Suggested viewport sizes for manual review: 1440px (desktop), 768px (tablet), and 375px (mobile).

## Repository files
- `index.html` — webpage structure and content.
- `style.css` — styling and responsive media queries.
- `README.md` — project documentation.

## Run locally
1. Clone or download this repository.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in a web browser.
4. Resize the browser or use Developer Tools device emulation to inspect responsive layouts.

## Testing checklist
- [ ] Inspect at 1440px width.
- [ ] Inspect at 768px width.
- [ ] Inspect at 375px width.
- [ ] Confirm navigation links move to the correct sections.
- [ ] Confirm Start a Project moves to Contact.
- [ ] Confirm Contact Us opens the email action.
- [ ] Check for overlapping content and unwanted horizontal scrolling.

Only mark a check as complete after manually testing it.

## Implementation note
This README describes the source currently in the repository. The stylesheet uses breakpoints at 900px and 600px. The mobile navigation wraps its links; it does not implement a hamburger menu. The hero graphic is CSS-created, and the About section is text-based rather than an image-and-text section.
