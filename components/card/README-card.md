# Pams Kit v1 -- Modern Cards

Pams Kit v1 adalah kumpulan **UI Card Components berbasis HTML & CSS
murni** yang dirancang untuk web developer modern.\
Tidak bergantung pada framework (React, Vue, dll), mudah dicopy-paste,
dan siap dikustomisasi.

------------------------------------------------------------------------

## ✨ Fitur Utama

-   Pure HTML & CSS
-   Menggunakan **BEM Naming Convention**
-   Modern UI + hover interaction
-   Responsive (Flexbox)
-   Menggunakan **Bootstrap Icons**
-   Mudah dikembangkan menjadi UI Kit / Design System

------------------------------------------------------------------------

## 📦 Struktur File

    /base
     ├─ reset.css
     ├─ base.css
    /cards
     ├─ card.css
    index.html

------------------------------------------------------------------------

## 🚀 Cara Menggunakan

### 1. Sertakan CSS

``` html
<link rel="stylesheet" href="/base/reset.css" />
<link rel="stylesheet" href="/base/base.css" />
<link rel="stylesheet" href="/cards/card.css" />
```

### 2. Sertakan Bootstrap Icons

``` html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css"
  rel="stylesheet"
/>
```

------------------------------------------------------------------------

## 🧩 Komponen Card yang Tersedia

### 1. Basic Card

Cocok untuk konten umum, artikel, atau landing page.

Class utama:

``` html
.basic-card
```

------------------------------------------------------------------------

### 2. Recipe Card

Digunakan untuk resep makanan, blog kuliner, atau konten cooking.

Class utama:

``` html
.recipe-card
```

------------------------------------------------------------------------

### 3. Profile Card

Untuk menampilkan profil user, freelancer, atau team member.

Class utama:

``` html
.profile-card
```

------------------------------------------------------------------------

### 4. Product Card

Untuk kebutuhan e-commerce sederhana.

Class utama:

``` html
.product-card
```

------------------------------------------------------------------------

### 5. Job Card

Untuk job listing atau career page.

Class utama:

``` html
.job-card
```

------------------------------------------------------------------------

### 6. Analytics / Stat Card

Menampilkan data statistik atau KPI.

Class utama:

``` html
.stat-card
```

------------------------------------------------------------------------

### 7. Status Card

Untuk alert status seperti success / info.

Class utama:

``` html
.status-card
```

------------------------------------------------------------------------

### 8. Interaction Card

Untuk CTA (Call to Action).

Class utama:

``` html
.interaction-card
```

------------------------------------------------------------------------

## 🎨 Design Token

Pams Kit menggunakan CSS Variable minimal & bersih:

``` css
:root {
  --pk-primary: #6366f1;
  --pk-dark: #0f172a;
  --pk-radius: 10px;
}
```

> Kamu bisa override token ini untuk theme berbeda (dark mode, brand
> color, dll).

------------------------------------------------------------------------

## 📱 Responsive Layout

Gunakan container berikut untuk layout grid:

``` html
<div class="pk-card-group">
  <!-- cards -->
</div>
```

Menggunakan: - `flex-wrap` - `gap` - `justify-content: center`

------------------------------------------------------------------------

## 🛠️ Customisasi

-   Ganti warna utama lewat `--pk-primary`
-   Ganti radius global lewat `--pk-radius`
-   Tambahkan variant card baru tanpa mengubah card lama

------------------------------------------------------------------------

## 📄 Lisensi

Free to use untuk personal & commercial project.

------------------------------------------------------------------------

## 👨‍💻 Author

**Pams Kit v1**\
Built for web developers who love clean UI & reusable components.

------------------------------------------------------------------------

Happy Coding 🚀
