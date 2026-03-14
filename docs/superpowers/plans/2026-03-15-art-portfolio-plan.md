# Art Portfolio Website Implementation Plan

> **For agentic workers:** REQUIRED: Use superpowers:subagent-driven-development (if subagents available) or superpowers:executing-plans to implement this plan. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a stunning art portfolio website for Saumya (Instagram: saumya.chaurasia04) with gallery, about, and contact pages

**Architecture:** Multi-page static website with vanilla HTML, CSS, and JavaScript. Masonry gallery layout with lightbox, dark mode toggle, smooth scroll animations

**Tech Stack:** Vanilla HTML5, CSS3, JavaScript (no frameworks)

---

## File Structure

```
website/
├── index.html          # Homepage with hero and featured works
├── gallery.html        # Full gallery page with filters
├── about.html          # About the artist
├── contact.html       # Contact form
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   └── main.js        # JavaScript for interactions
├── assets/
│   └── images/        # Image placeholder folder
└── docs/
    └── superpowers/
        └── plans/
            └── 2026-03-15-art-portfolio-plan.md
```

---

## Chunk 1: Project Setup & Base Styles

### Task 1: Create Project Structure

- [ ] **Step 1: Create directory structure**

```bash
mkdir -p website/css website/js website/assets/images website/docs/superpowers/plans
```

- [ ] **Step 2: Create index.html (Homepage)**

Write complete HTML with:
- Header with navigation and dark mode toggle
- Hero section with featured artwork slider
- Featured works section (6 placeholders)
- Latest artworks preview
- Footer with social links

- [ ] **Step 3: Create gallery.html**

Write complete HTML with:
- Same header/footer as index
- Filter buttons (All, Digital, Traditional, Sketches, Photography)
- Masonry grid gallery with 12 placeholder images
- Lightbox modal structure

- [ ] **Step 4: Create about.html**

Write complete HTML with:
- Same header/footer
- Artist bio section
- Timeline of creative journey
- Skills/tools section

- [ ] **Step 5: Create contact.html**

Write complete HTML with:
- Same header/footer
- Contact form (Name, Email, Message fields)
- Social media links section
- Location placeholder

---

### Task 2: Create CSS Stylesheet

**Files:**
- Create: `website/css/style.css`

- [ ] **Step 1: Create style.css with all base styles**

Write complete CSS including:
- CSS Variables for colors (light/dark themes)
- Reset and base styles
- Typography (Google Fonts import)
- Navigation styles
- Hero section styles
- Gallery masonry grid
- Lightbox styles
- Form styles
- Footer styles
- Dark mode styles
- Responsive breakpoints
- Animations (fade-in, hover effects)

---

### Task 3: Create JavaScript File

**Files:**
- Create: `website/js/main.js`

- [ ] **Step 1: Create main.js with all interactions**

Write complete JavaScript including:
- Dark mode toggle (save to localStorage)
- Mobile menu toggle
- Gallery filter functionality
- Lightbox open/close/navigate
- Scroll animations (Intersection Observer)
- Form validation
- Smooth scroll for navigation

---

## Chunk 2: Testing & Verification

### Task 4: Verify Implementation

- [ ] **Step 1: Verify file structure**

Run: `ls -la website/`
Expected: index.html, gallery.html, about.html, contact.html, css/, js/, assets/

- [ ] **Step 2: Validate HTML syntax**

Check all HTML files are well-formed

- [ ] **Step 3: Test in browser**

Open index.html and verify:
- Homepage loads correctly
- Navigation works
- Dark mode toggle works
- Gallery filters work
- Lightbox opens/closes
- Contact form displays
- Responsive on mobile viewport

---

## Implementation Notes

1. All placeholder images use picsum.photos for demo
2. Instagram link will be: https://instagram.com/saumya.chaurasia04
3. Colors can be easily customized via CSS variables
4. Form is ready to integrate with backend service (Formspree, etc.)
5. All animations use CSS transitions and Intersection Observer for performance

---

**Plan complete and saved to `docs/superpowers/plans/2026-03-15-art-portfolio-plan.md`. Ready to execute?**
