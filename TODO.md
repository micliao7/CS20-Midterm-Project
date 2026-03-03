# Luna & Leaf — Midterm Project Checklist

## Requirements (Spec Compliance)

### Pages & Structure
- [x] At least 7 pages (index, menu, about, locations, events, reservations, contact)
- [ ] No more than 2 pages that look the same (e.g., product catalog pages)
- [x] One h1 per page
- [ ] Use h2, h3, etc. for subheadings where appropriate

### Styling
- [x] At least one external style sheet (`buisness_style.css`)
- [ ] At least one internal style sheet (add `<style>` block on one page)
- [ ] At least 20 CSS rules total (currently ~25, verify count)
- [ ] Consistent look and feel across all pages

### Layout
- [x] Fixed page elements (header/nav)
- [ ] Footer with logo linking to home
- [ ] At least one page with multiple columns (CSS, not table) — e.g., menu, locations

### Form
- [x] Form with at least 3 different element types (text, email, select, textarea)
- [x] Form validation (JavaScript)
- [x] Thank you popup on valid submission
- [x] Form elements aligned aesthetically

### JavaScript / jQuery
- [x] Form validation
- [ ] One additional use (e.g., image gallery, accordion, tabs, smooth scroll)
- [ ] At least 3 of the following:
  - [ ] Associative array (object)
  - [ ] Function
  - [ ] Use of a DOM object
  - [ ] Home-grown/custom object
  - [ ] JSON object read from external file
  - [ ] Array of JS objects used to build page content (menu, events, locations, FAQs, etc.)

### Content Elements
- [ ] At least one `<ol>` or `<ul>` that is NOT part of navigation
- [ ] Meta keywords in `<head>`
- [ ] Images:
  - [ ] At least 3 images total
  - [ ] At least one background image
  - [ ] Banner under 120k, others under 50k file size

### Responsive & Technical
- [ ] Responsive / mobile friendly down to 400px
- [ ] No broken links
- [ ] Works online (deployed)
- [ ] No "Lorem ipsum" content
- [ ] Cite sources for borrowed or AI-generated content

---

## General Content to Add

### Home (index.html)
- [ ] Replace hero placeholder text with real intro copy
- [ ] Add hero image or banner
- [ ] Add brief tagline / call to action
- [ ] Add links or teasers to Menu, Reservations, Events

### Menu (menu.html)
- [ ] Add menu categories (e.g., Coffee, Food, Pastries)
- [ ] Add item names and prices
- [ ] Consider using array of JS objects to build menu dynamically (checks spec requirement)

### About (about.html)
- [ ] Add cafe story / mission
- [ ] Add team section (optional — can use array of objects)
- [ ] Add values or milestones as a list (`<ul>` or `<ol>`)

### Locations (locations.html)
- [ ] Add address(es) and hours
- [ ] Consider loading from external JSON file (checks spec requirement)
- [ ] Add map link or embed (optional)

### Events (events.html)
- [ ] Add list of upcoming events
- [ ] Add coworking / work-friendly info
- [ ] Use `<ul>` or `<ol>` for event list

### Reservations (reservations.html)
- [x] Form implemented
- [ ] Optional: add date/time fields or more context copy

### Contact (contact.html)
- [ ] Add contact form OR use for secondary form (spec: form with 3+ element types)
- [ ] Add address, phone, email
- [ ] Add hours

### Images Needed
- [ ] Banner/hero image (home page)
- [ ] At least one background image (on hero or section)
- [ ] At least 2 more images (food, interior, events, etc.)
- [ ] Ensure file sizes: banner < 120k, others < 50k

### Footer
- [ ] Create footer with logo (links to home)
- [ ] Add address, hours, or social links
- [ ] Add to all 7 pages
