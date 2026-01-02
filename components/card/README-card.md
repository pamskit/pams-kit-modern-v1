# Card Component – Pams Kit v1

A collection of **modern card components** built with pure HTML & CSS.  
Designed for UI kits, dashboards, landing pages, and content layouts.  
No JavaScript and no framework dependency.

---

## Usage

### 1. Import CSS

```html
<link rel="stylesheet" href="/base/reset.css" />
<link rel="stylesheet" href="/base/base.css" />
<link rel="stylesheet" href="/components/card/card.css" />
```

If you are using icons:

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css"
  rel="stylesheet"
/>
```

---

## Available Card Types

This component includes multiple card variations, each designed for different use cases:

```
pk-basic-card        → Content / blog preview card
pk-recipe-card       → Recipe / article card with meta & tags
pk-profile-card      → User / profile card
pk-product-card      → Product / ecommerce card
pk-job-card          → Job vacancy / career card
pk-stat-card         → Analytics / statistics card
pk-status-card       → Status / notification card
pk-interaction-card  → Call-to-action / interaction card
```

---

## Basic Example

```html
<div class="pk-basic-card">
  <img class="pk-basic-card__img" src="image.jpg" alt="Card image" />

  <div class="pk-basic-card__body">
    <h4 class="pk-basic-card__title">Card Title</h4>
    <p class="pk-basic-card__description">Short description goes here.</p>
  </div>

  <div class="pk-basic-card__footer">
    <button class="pk-basic-card__button">Action</button>
  </div>
</div>
```

---

## Customization

All cards use **CSS Variables** for easy customization:

```css
:root {
  --pk-primary: #6366f1;
  --pk-dark: #0f172a;
  --pk-radius: 10px;
}
```

You can override these variables globally or per project without touching the component styles.

---

## Notes

- Each card is **standalone** and can be used independently
- Card styles are modular and do not affect each other
- Icons are provided by **Bootstrap Icons**
- Safe for copy–paste usage
- Built for static HTML & CSS projects

---

📬 Contact & Links
If you have questions, feedback, or would like to collaborate, feel free to reach out through the following channels. I’m open to discussions related to UI kits, frontend styling, and component design.

- WhatsApp: +62 838-3373-5915
- GitHub: https://github.com/pamskit
- Instagram: @pams_uikit
