# Tokens CSS & Bootstrap 5

Ce guide fournit tout le nécessaire pour démarrer le développement manuel de l'interface BlaBlamU, soit en **CSS pur** (`:root`), soit par-dessus **Bootstrap 5** (CDN ou SCSS).

---

## 1. Import des polices (`<head>`)

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Golos+Text:wght@400;500;600;700&family=Inter:wght@400;600;700;800&family=SUSE+Mono:wght@700;800&display=swap" rel="stylesheet">
```

Si vous affichez les SVG `amU` en HTML/CSS sans vectoriser le texte, déclarez aussi `Monument Grotesk` depuis `assets/fonts/` :

```css
@font-face {
  font-family: 'Monument Grotesk';
  src: url('../assets/fonts/MonumentGrotesk-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```

---

## 2. Fichier `tokens.css` complet (`:root`)

```css
:root {
  /* Palette principale (variables Figma) */
  --primary-color: #090B10;
  --primary-dark: #000000;
  --primary-light: #4E495B;
  --gris: #4E495B;

  --secondary-color: #3478F6;
  --secondary-dark: #0758A9;
  --secondary-light: #4BD8FF;

  --accent-color: #B08AE8;
  --accent-dark: #8039E9;
  --accent-light: #DAC4FB;

  /* Neutres & Kit UI */
  --blanc: #FFFFFF;
  --gray-100: #F8F9FA;
  --gray-200: #E9ECEF;
  --gray-300: #DEE2E6;
  --gray-500: #ADB5BD;
  --gray-600: #6C757D;
  --gray-800: #343A40;
  --body-base: #68717A;
  --border-checkbox: #ABB5BE;
  --surface-muted: #D9D9D9;
  --footer-muted: #BDBDBD;

  /* Sémantique / statuts */
  --color-success: #28A745;
  --color-danger: #DC3545;
  --color-info: #17A2B8;
  --color-warning: #FFC107;
  --kit-purple: #7749F8;
  --kit-purple-dark: #5227CC;
  --kit-indigo: #6610F2;

  /* Typographies */
  --font-heading: 'SUSE Mono', monospace;
  --font-body: 'Golos Text', sans-serif;
  --font-ui: 'Inter', sans-serif;

  /* Tailles titres */
  --h1-pc: 40px;
  --h2-pc: 32px;
  --h3-pc: 28px;
  --h1-mobile: 32px;
  --h2-mobile: 24px;
  --h3-mobile: 20px;

  /* Rayons */
  --radius-checkbox: 2px;
  --radius-pill: 4px;
  --radius-hour-pill: 5px;
  --radius-control: 6px;
  --radius-panel: 8px;
  --radius-card: 10px;
  --radius-mobile-block: 14px;
  --radius-map-mobile: 22px;

  /* Layout */
  --navbar-height: 72px;
  --footer-height-mobile: 85px;
  --footer-height-desktop: 72px;
  --container-desktop-max: 1152px;
}
```

---

## 3. Adaptation Bootstrap 5

### Option A — Bootstrap via CDN (surcharges CSS)

Ajoutez ce bloc **après** le CSS de Bootstrap 5 pour retrouver immédiatement les couleurs, polices et composants BlaBlamU :

```css
:root {
  --bs-body-bg: var(--primary-color);
  --bs-body-color: var(--blanc);
  --bs-body-font-family: var(--font-body);
  --bs-body-font-size: 16px;
  --bs-body-line-height: 28px;

  --bs-primary: var(--accent-color);
  --bs-secondary: var(--secondary-color);
  --bs-success: var(--color-success);
  --bs-danger: var(--color-danger);
  --bs-info: var(--color-info);
  --bs-warning: var(--color-warning);
  --bs-border-color: var(--gray-300);
  --bs-border-radius: 6px;
}

body {
  background-color: var(--primary-color);
  color: var(--blanc);
  font-family: var(--font-body);
}

h1, .h1 {
  font-family: var(--font-heading);
  font-weight: 800;
  color: var(--blanc);
  line-height: 1;
}

h2, .h2, h3, .h3 {
  font-family: var(--font-heading);
  font-weight: 700;
  color: var(--secondary-color);
  line-height: 1;
}

/* Boutons CTA BlaBlamU */
.btn-bb-primary {
  --bs-btn-bg: var(--accent-color);
  --bs-btn-border-color: var(--accent-color);
  --bs-btn-color: #FFFFFF;
  --bs-btn-hover-bg: var(--accent-dark);
  --bs-btn-hover-border-color: var(--accent-dark);
  --bs-btn-hover-color: #FFFFFF;
  --bs-btn-disabled-bg: var(--accent-light);
  --bs-btn-disabled-border-color: var(--accent-light);
  --bs-btn-disabled-opacity: 0.55;
  border-radius: 6px;
  font-weight: 600;
}

/* Panneaux noirs Desktop */
.bb-panel {
  background-color: var(--primary-dark);
  border-radius: 8px;
  padding: 24px;
}

/* Cartes à bordure bleue 2px */
.bb-card {
  background-color: var(--blanc);
  border: 2px solid var(--secondary-color);
  border-radius: 10px;
  color: var(--body-base);
}

/* Pagination */
.pagination .page-link {
  color: var(--gray-600);
  border-color: var(--gray-200);
  font-family: var(--font-ui);
  border-radius: 4px;
  padding: 12px 16px;
  line-height: 16px;
}

.pagination .page-item.active .page-link {
  background-color: var(--accent-dark);
  border-color: var(--kit-purple);
  color: #FFFFFF;
}
```

### Option B — Bootstrap avec Sass (SCSS)

Déclarez ces variables **avant** `@import "bootstrap/scss/bootstrap";` :

```scss
$body-bg: #090B10;
$body-color: #FFFFFF;

$primary: #B08AE8;
$secondary: #3478F6;
$success: #28A745;
$danger: #DC3545;
$info: #17A2B8;
$warning: #FFC107;

$font-family-sans-serif: 'Golos Text', sans-serif;
$headings-font-family: 'SUSE Mono', monospace;
$font-size-base: 1rem; // 16px
$line-height-base: 1.75; // 28px

$border-radius: 6px;
$border-radius-sm: 4px;
$border-radius-lg: 8px;

$input-bg: #FFFFFF;
$input-border-color: #DEE2E6;
$input-color: #4E495B;
$input-placeholder-color: #ADB5BD;

$pagination-color: #6C757D;
$pagination-bg: #FFFFFF;
$pagination-border-color: #E9ECEF;
$pagination-active-bg: #8039E9;
$pagination-active-border-color: #7749F8;
$pagination-active-color: #FFFFFF;
$pagination-disabled-color: #ADB5BD;
```
