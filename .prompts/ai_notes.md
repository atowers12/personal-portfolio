# USER PROVIDED STRUCTURE:

## Tasks

### Remaining
- Add reflection & AI prompt logs to `.prompts/dev_notes.md`
- Test site in two browsers (record which + date)
- Validate HTML & CSS via W3C validators (record outcome)
- Add lightweight accessibility pass (tab order, labels, color contrast quick check)
- Optional: add favicon & meta tags (description, viewport already required)
- Optional: performance pass (optimize image sizes)

### Accomplished
- Reformatted assignment specification in `.prompts/task.md` for clarity
- Created `.github/copilot-instructions.md` with project-specific AI guidance
- Established AI notes structure (`ai_notes.md`) for tracking progress & features
- Scaffolded all required pages with shared navigation and semantic layout
- Authored responsive `styles.css` with color palette, typography, and component styling
- Wrote biography, resume, and project content grounded in provided resume details
- Added placeholder SVG images under `images/` with descriptive alternate text
- Implemented accessible contact form with validation attributes, JS password match, and redirect
- Upgraded mobile navigation to a hamburger toggle with smooth transitions
- Replaced project placeholders with real screenshots, copy, and live repo/site links
- Tuned project visuals (hero placeholder + scaled Spotter screenshot for better layout)
- Reworked project card layout to align imagery left with fully visible screenshots and right-hand copy
- Added contact form message textarea with matching styles and validation

## Features
### [Feature] Name
### [Feature] Description
### [Feature] Purpose
### [Feature] Potential Risks
### [Feature] Future Ideas/Implementations

### Multi-Page Static Site
### Description
Six-page static portfolio/resume site: landing + about + resume + projects + contact + thank-you.
### Purpose
Showcase personal profile and satisfy assignment rubric (content + AI usage + form validation).
### Potential Risks
Scope creep on styling; inconsistent nav duplication; missing required alt text.
### Future Ideas/Implementations
Add dark mode toggle; add print-friendly resume stylesheet.

### Shared Navigation Bar
### Description
Consistent `<nav>` element across all pages linking core sections.
### Purpose
Usability & grading requirement for consistent navigation.
### Potential Risks
Manual copy updates causing mismatch; broken relative links.
### Future Ideas/Implementations
Abstract into a server include (future) or use a JS inject snippet (optional, not required now).

### Responsive Layout
### Description
Mobile-first CSS with fluid typography and stacked-to-horizontal layout shifts.
### Purpose
Meet assignment requirement for responsiveness; improve usability on phones.
### Potential Risks
Over-complication; forgetting viewport meta tag; layout breakpoints untested.
### Future Ideas/Implementations
Use CSS container queries; add print and prefers-color-scheme tweaks.

### Contact Form & Validation
### Description
Form on `contact.html` with required fields (first/last name, email, password, confirm password) using HTML5 validation + JS password match + redirect to `thankyou.html`.
### Purpose
Demonstrate form semantics, accessibility, and basic client-side validation skills.
### Potential Risks
Passwords not matching without clear feedback; forgetting `minlength=8`; missing `for`/`id` pairs.
### Future Ideas/Implementations
Add progressive enhancement (strength meter); basic spam honeypot.

### Accessibility & Alt Text
### Description
All interactive elements labeled; images have descriptive `alt`; semantic structure via `<header> <nav> <main> <footer>`.
### Purpose
Assignment requirement; inclusive design practice.
### Potential Risks
Decorative images accidentally given verbose alt; contrast issues.
### Future Ideas/Implementations
Add skip link; ARIA landmarks audit; color contrast tooling run.

### AI Prompt Logging
### Description
`.prompts/dev_notes.md` captures at least 3 prompts (prompt, AI output, acceptance decision) plus ~150 word reflection.
### Purpose
Demonstrate responsible AI-assisted development and reflective practice.
### Potential Risks
Incomplete logging; overwriting earlier entries; reflection too short.
### Future Ideas/Implementations
Tag prompts by category (scaffold, refine, debug); add timestamp metadata.

### Image & Asset Management
### Description
All media stored under `images/` with human-readable filenames.
### Purpose
Organization, portability, consistent relative paths.
### Potential Risks
Large image sizes impacting load; inconsistent naming.
### Future Ideas/Implementations
Automate compression; add responsive `srcset`.

### Styling Architecture
### Description
Single `styles.css` containing base resets, typography scale, layout utilities, component styles (nav, cards, form), and responsive breakpoints.
### Purpose
Keep project simple and within assignment scope (no build tools).
### Potential Risks
File bloat; lack of organization; accidental specificity conflicts.
### Future Ideas/Implementations
Modularize via naming conventions (BEM-ish), optional CSS custom properties.
