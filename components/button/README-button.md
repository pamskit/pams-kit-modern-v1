# Button Component – Pams Kit v1

Komponen **Button** berbasis HTML & CSS.  
Modular, copy–paste friendly, tanpa JavaScript.

---

## Cara Pakai

### 1. Import CSS

```html
<link rel="stylesheet" href="/base/reset.css" />
<link rel="stylesheet" href="/base/base.css" />
<link rel="stylesheet" href="/components/button/button.css" />
```

Jika menggunakan icon:

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css"
  rel="stylesheet"
/>
```

---

## Contoh Dasar

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

## Dengan Icon

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

## Customisasi

Semua warna & radius menggunakan CSS Variable:

```css
:root {
  --pk-primary: #6366f1;
  --pk-radius: 10px;
}
```

---

## Notes

- Class bebas dikombinasikan selama logis
- Icon menggunakan **Bootstrap Icons**
- Tidak tergantung framework atau JavaScript
