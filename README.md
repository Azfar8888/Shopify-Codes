# 🧩 Shopify Custom Sections – Liquid Components

This repository contains a set of custom Shopify Liquid components designed to enhance the visual layout and functionality of Shopify storefronts. All components are modular, responsive, and easily configurable through the Shopify theme editor.

---

## 📁 Included Files

### `1. Hero-Slider.liquid`
→ A responsive hero banner slider supporting:
- Desktop & mobile image versions
- Optional headings, subheadings, and link buttons
- Auto-slide every 5 seconds
- Manual navigation arrows

### `2. Video-Hero-Slider.liquid`
→ A multimedia version of the Hero Slider:
- Supports `.mp4` video backgrounds (desktop & mobile)
- Fallback to image if video not present
- Includes content overlay (headings, subheadings)
- Mobile-optimized and autoplay enabled

### `3. Collection-Slider.liquid`
→ Horizontally scrolling carousel for featured collections:
- Custom image, title & link per collection
- Desktop arrow navigation, mobile swipe support
- Responsive scroll behavior

### `4. Attractive-Collection-Grid.liquid`
→ A stylized grid layout to display featured collections:
- Fixed image height with overlay text
- Gradient overlay for legibility
- Hover arrow animation
- Adjustable padding, grid columns, and color scheme

### `5. Product-Tab-Grid.liquid`
→ Product carousel with tabbed collections:
- Users can switch between collections using tabs
- Each tab loads a separate product carousel (via Splide.js)
- Custom margins & layout controls for desktop/tablet/mobile
- Optimized for performance with lazy loading

---

## 🔧 Setup Instructions

1. **Upload Files:** Place all `.liquid` files inside your theme’s `sections/` directory.
2. **Customize Theme:** Go to Shopify Admin → Online Store → Customize.
3. **Add Sections:** Use the Shopify editor to add and configure the desired section on any page.
4. **Edit Styles (Optional):** Most sections use inline or embedded styles. Adjust directly inside `.liquid` files if needed.
5. **Ensure Assets:** If any sections reference external assets (fonts, CSS), ensure they're loaded correctly in the theme.

---

## 🖼️ Fonts & Dependencies

- **Google Fonts:** `Poppins`, `Assistant` used across components
- **Splide.js:** Used in `Product-Tab-Grid.liquid` for the carousel
```html
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.3/dist/js/splide.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.3/dist/css/splide.min.css">
