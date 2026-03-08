# Luna & Leaf — Midterm Project Checklist

## Requirements (Spec Compliance)

### Pages & Structure
- [x] At least 7 pages (index, menu, about, locations, events, reservations, contact)
- [ ] No more than 2 pages that look the same (e.g., product catalog pages)
- [x] One h1 per page
- [x] Use h2, h3, etc. for subheadings where appropriate (index)

### Styling
- [x] At least one external style sheet (`buisness_style.css`)
- [x] At least one internal style sheet (index has `<style>` block for hero)
- [x] At least 20 CSS rules total (buisness_style.css + forms.css)
- [x] Consistent look and feel across all pages

### Layout
- [x] Fixed page elements (header/nav)
- [x] Footer with logo linking to home (all 7 pages)
- [x] At least one page with multiple columns (index quicklinks + perfect-for grids)

### Form
- [x] Form with at least 3 different element types (text, email, select, textarea)
- [x] Form validation (JavaScript)
- [x] Thank you popup on valid submission
- [x] Form elements aligned aesthetically

### JavaScript / jQuery
- [x] Form validation
- [ ] One additional use (e.g., image gallery, accordion, tabs, smooth scroll)
- [x] At least 3 of the following:
  - [ ] Associative array (object)
  - [ ] Function
  - [x] Use of a DOM object (document.getElementById in menu + reservations)
  - [ ] Home-grown/custom object
  - [x] JSON object read from external file (menu loads menu_items.json)
  - [x] Array of JS objects used to build page content (menu builds from data.menu_items)

### Content Elements
- [x] At least one `<ol>` or `<ul>` that is NOT part of navigation (index: feature-list, hours-preview)
- [x] Meta keywords in `<head>` (index)
- [ ] Images:
  - [ ] At least 3 images total (have: logo, workspace-2 — need 1 more)
  - [x] At least one background image (workspace-2.jpg in hero)
  - [ ] Banner under 120k, others under 50k file size

### Responsive & Technical
- [ ] Responsive / mobile friendly down to 400px (media query at 700px exists; verify 400px)
- [ ] No broken links
- [ ] Works online (deployed)
- [x] No "Lorem ipsum" content
- [ ] Cite sources for borrowed or AI-generated content

---

## General Content to Add

### Home (index.html)
- [x] Replace hero placeholder text with real intro copy
- [x] Add hero image or banner (workspace-2.jpg)
- [x] Add brief tagline / call to action
- [x] Add links or teasers to Menu, Reservations, Events

### Menu (menu.html)
- [x] Menu loads from JSON (menu_items.json)
- [x] Remove "Content placeholder" text
- [ ] Add menu categories or improve layout

### About (about.html)
- [x] Add cafe story / mission
- [ ] Add team section (optional — can use array of objects)
- [x] Add values or milestones as a list (`<ul>` or `<ol>`)
- [x] Remove "Content placeholder"

### Locations (locations.html)
- [ ] Add address(es) and hours
- [ ] Consider loading from external JSON file (checks spec requirement)
- [ ] Add map link or embed (optional)
- [ ] Remove "Content placeholder"

### Events (events.html)
- [ ] Add list of upcoming events
- [ ] Add coworking / work-friendly info
- [ ] Use `<ul>` or `<ol>` for event list
- [ ] Remove "Content placeholder"

### Reservations (reservations.html)
- [x] Form implemented
- [ ] Optional: add date/time fields or more context copy

### Contact (contact.html)
- [ ] Add contact form OR use for secondary form (spec: form with 3+ element types)
- [x] Add address, phone, email
- [ ] Add hours
- [x] Remove "Content placeholder"

### Images Needed
- [x] Banner/hero image (workspace-2.jpg)
- [x] At least one background image (workspace-2 in hero)
- [x] At least 1 more image (need 3 total; have logo + workspace-2)
- [ ] Ensure file sizes: banner < 120k, others < 50k

### Footer
- [x] Footer with logo (links to home)
- [x] Footer on all 7 pages
- [ ] Add address, hours, or social links (optional)
