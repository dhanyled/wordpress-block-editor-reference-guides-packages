# 🌐 WordPress Block Editor Reference Guides & Packages Showcase

Interactive 3D Fluid-Responsive Showcase & Comprehensive Catalog of all **124 official WordPress JavaScript packages (`@wordpress/*`)** powering the Gutenberg editor and modern WordPress ecosystem.

---

## 🚀 Live Interactive Demo
- **GitHub Pages / Vercel Ready:** Just open `index.html` in your browser.
- **Reference Source:** [developer.wordpress.org/block-editor/reference-guides/packages/](https://developer.wordpress.org/block-editor/reference-guides/packages/)

---

## 🌟 Key Features

1. **Official WordPress 3D Emblem & Aesthetic:**
   - Pure vector official WordPress SVG logo.
   - 3D floating badge with ambient glowing shadows.
2. **Adaptive Desktop vs Mobile Experience:**
   - **Desktop:** Perspective 3D mouse parallax tilt on cards (reacts smoothly to cursor position via `@media (hover: hover) and (pointer: fine)`).
   - **Mobile & Tablet:** Touch-safe animations (hover parallax disabled on touch devices to prevent sticky hover bugs, replaced with responsive `:active` tap feedback).
3. **Fluid Responsive Typography & Layout:**
   - Built using modern CSS `clamp()` for font sizes, padding, and gap spacing.
   - Zero horizontal overflow from 360px mobile screens to 4K desktop displays.
4. **Performance & Security First:**
   - **Zero external bloat:** 100% native GPU-accelerated CSS 3D transforms (running at silky 60fps).
   - Pure Vanilla JS for instantaneous search & filtering (124 KB total bundle).
   - Safe external outbound links with `rel="noopener noreferrer"`.
5. **Interactive 124 Packages Catalog:**
   - Real-time instant search by package name, category, or description.
   - 8 Category filter pills (Content, Blocks, Data, Screens, UI, Interactivity, Utils, DevTools).
   - Direct reference link to every package's official documentation.

---

## 🛠️ What Can You Build with These Packages?

1. **Custom Gutenberg Blocks:**
   - Slider, Accordion FAQ, pricing tables, calculator blocks (`@wordpress/blocks`, `@wordpress/block-editor`, `@wordpress/components`).
2. **Sidebar & Custom Meta Boxes:**
   - Extend the WP-Admin post editor with editorial checklists and custom inputs (`@wordpress/plugins`, `@wordpress/edit-post`, `@wordpress/editor`).
3. **Modern Admin Data Views (WP 6.5+):**
   - Dynamic table, photo grid, and Kanban boards in WP-Admin (`@wordpress/dataviews`, `@wordpress/core-data`).
4. **Lightning-Fast Frontend without Page Reloads:**
   - Instant search, dynamic product filters, and SPA navigation (`@wordpress/interactivity`, `@wordpress/interactivity-router`).
5. **Standalone Text & Wordcount Engines:**
   - Text editing apps with official Gutenberg wordcount algorithms (`@wordpress/wordcount`, `@wordpress/rich-text`, `@wordpress/autop`).
6. **Mass Content Parsers & Migration Tools:**
   - Convert raw HTML drafts into native WordPress block comments (`@wordpress/block-serialization-default-parser`).
7. **Automated End-to-End Testing Bots:**
   - Test editor flows and forms in real browsers using Playwright (`@wordpress/e2e-test-utils-playwright`, `@wordpress/env`).

---

## 📄 License
MIT License. Open source and free to use.
