# 🏠 Homepage Structure — Artist Shopify Theme

This document outlines the homepage section layout for a custom Shopify theme designed for visual artists. The theme draws aesthetic inspiration from [lirona.me](https://www.lirona.me) and is tailored for artists to present their work in an elegant, minimalist, and story-driven layout.

---

## 🎨 Design Principles

- Editorial, gallery-like presentation
- Serif headings + modern sans-serif body font
- Soft neutral tones (white, black, beige, soft pink)
- Full-bleed imagery, generous whitespace
- Minimal hover effects, scroll-based animations
- Clean, mobile-first responsive design

---

## 🧱 Section Order

### 1. Hero Section

- **Full viewport height**
- Large background image or video
- Centered artist name or logo
- Optional subtitle or short tagline
- Minimal or no CTA (scroll indicator optional)

### 2. Featured Projects / Gallery Grid

- 4–6 artwork pieces in 2x2 or 3x2 layout
- Each block: artwork image + title (optionally tag/category)
- Clickable to individual product or collection page

### 3. Artist Statement

- Serif heading: _"About the Artist"_ or _"Artist Statement"_
- 3–5 sentence paragraph about the artist’s process or philosophy
- Optional small portrait photo or full-width background

### 4. Video / Process Section _(Optional)_

- Embedded Vimeo/YouTube or hosted video
- Full-width or 2-column layout
- Caption or quote beneath video

### 5. Featured Collection (Shop)

- Collection selector: choose 1 featured collection
- Grid or slider layout
- Each item: image, title, price, optional “Limited Edition” tag
- CTA: _"Shop the Collection"_ or _"View All Works"_

### 6. Testimonials / Collector Quotes

- Short quotes from collectors, buyers, press
- Carousel or two-column layout
- Optional attribution: name, artwork, or publication

### 7. Event Announcements

- Upcoming exhibitions or shows
- Each item: Title, date, venue, optional image/flyer
- CTA or map link optional

### 8. Newsletter Signup _(Optional)_

- Heading: _"Join My Studio Newsletter"_
- Input field + submit button
- Optional incentive or benefit text

---

## 📱 Mobile Behavior

- All sections stack vertically with consistent padding
- Navigation collapses to hamburger
- Images shrink to single-column layouts

---

## 🔧 Implementation Notes

- Built using Shopify Online Store 2.0 JSON templates
- Each section should be implemented in `/sections/` with editable settings via `settings_schema.json`
- `templates/index.json` will define this layout order
- Hero, project gallery, statement, and video are top-priority for V1

---

## ✅ Initial Sections to Build

- `hero.liquid`
- `project-gallery.liquid`
- `artist-statement.liquid`
- `video-embed.liquid` _(optional for V1)_
- `featured-collection.liquid`
- `testimonials.liquid`
- `event-announcement.liquid`
- `newsletter-signup.liquid`

---

For questions or updates, contact the theme owner or creative lead.
