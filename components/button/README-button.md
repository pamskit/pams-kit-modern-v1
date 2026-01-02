# Button Component – Pams Kit v1

A **Button component** built with pure HTML & CSS.  
Modular, copy–paste friendly, and JavaScript-free.

---

## Usage

### 1. Import CSS

```html
<link rel="stylesheet" href="/base/reset.css" />
<link rel="stylesheet" href="/base/base.css" />
<link rel="stylesheet" href="/components/button/button.css" />
```

If you are using icons:

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css"
  rel="stylesheet"
/>
```

---

## Basic Example

```html
<button class="pk-btn pk-btn--primary">
  <span class="pk-btn__text">Primary</span>
</button>
```

---

## Variants

```
pk-btn--primary
pk-btn--secondary
pk-btn--success
pk-btn--danger
pk-btn--warning
pk-btn--info
pk-btn--dark
pk-btn--light
pk-btn--outline
pk-btn--ghost
pk-btn--gradient
pk-btn--neumorph
```

---

## Size

```
pk-btn--lg
pk-btn--sm
```

---

## Shape

```
pk-btn--rounded
pk-btn--pill
```

---

## State

```
pk-btn--loading
pk-btn--disabled
```

---

## With Icon

```html
<button class="pk-btn pk-btn--success">
  <i class="bi bi-check-circle pk-btn__icon"></i>
  <span class="pk-btn__text">Success</span>
</button>
```

### Icon Only

```html
<button class="pk-btn pk-btn--icon-only pk-btn--light" aria-label="Settings">
  <i class="bi bi-gear"></i>
</button>
```

---

## Customization

All colors and border radius values are controlled using CSS Variables:

```css
:root {
  --pk-primary: #6366f1;
  --pk-radius: 10px;
}
```

---

## Notes

- Classes can be freely combined as long as they make sense
- Icons are provided by **Bootstrap Icons**
- No framework and no JavaScript dependency

---

📬 Contact & Links
If you have questions, feedback, or would like to collaborate, feel free to reach out through the following channels. I’m open to discussions related to UI kits, frontend styling, and component design.

- WhatsApp: +62 838-3373-5915
- GitHub: https://github.com/pamskit
- Instagram: @pams_uikit
