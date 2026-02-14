### Graded Assignment: Flexbox Mastery

**Reminder: Create a repo (GitHub + local)**

- **On GitHub:** Sign in → "+" → "New repository" → Name it (e.g. `css_flexbox_assignment`) → Leave "Add a README file" **unchecked** → Create repository.
- **In the terminal (locally):**
  1. `mkdir project-name` then `cd project-name`
  2. `git init`
  3. Create your files, then: `git add .` → `git commit -m "Initial commit"`
  4. `git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git`
  5. `git branch -M main` (if needed)
  6. `git push -u origin main`

**What this assignment is for:** You show that you can build a layout using only what you learned in Lessons 5.1–5.3 (flex containers, flex items, alignment, flex-wrap). You do **not** need media queries (those are in Module 8).

**Requirements:**
1. Create a page layout with header, main content area, sidebar, and footer using **only flexbox** for layout (no floats, no positioning for layout).
2. Use `display: flex`, `flex-direction`, and `flex-wrap` so that when the container is narrow, items can wrap (e.g. sidebar and main stack).
3. Navigation bar: use flexbox with spacing (e.g. `justify-content`, `gap`).
4. Include a section with at least 6 cards that use flexbox and `flex-wrap` so cards wrap when space is limited.
5. Use flex so the footer stays at the bottom when content is short (e.g. `flex: 1` on main).
6. Center a hero section horizontally and vertically using `justify-content` and `align-items`.
7. Use flex properties (e.g. `flex`, `flex-grow`) to control item sizing where appropriate.

**Deliverables:**
- HTML file with clear structure
- CSS file that uses only flexbox for layout (and styles from earlier modules)
- Code comments that explain your flexbox choices

**Grading Criteria:**
- Correct use of flexbox properties from this module (30%)
- Use of flex-wrap and alignment (25%)
- Code organization and comments (20%)
- Layout and spacing (15%)
- Completeness and clarity (10%)
