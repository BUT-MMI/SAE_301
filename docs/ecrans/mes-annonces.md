# Mes annonces

<span class="node-badge">Mobile 64:244 (375×812)</span> <span class="node-badge">Desktop 120:552 (1280×720)</span>

Liste des trajets publiés par l'utilisateur connecté, avec pagination et actions de gestion.

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-mes-annonces.png" alt="Mobile Mes annonces">
    <figcaption>Mobile — 64:244 (375 × 812px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-mes-annonces.png" alt="Desktop Mes annonces">
    <figcaption>Desktop — 120:552 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 1. Structure Mobile (`64:244` · `375 × 812px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Nav Bar** | `top: 0`, `h: 72px` | Fond `#090B10` |
| **Titre `Annonces`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Compteur `00 Trajets`** | `left: 12px`, `top: 181px` (centre) | `SUSE Mono` Bold `24px`, `#3478F6` |
| **Grille 2 × 2 `Carte Annonces`** | `164 × 167px` chacune · Rangée 1 `top: 223px`, Rangée 2 `top: 417px` · Col. gauche `left: 12px`, Col. droite `left: ~199px` | Fond `#FFFFFF`, `border: 2px solid #3478F6`, `rounded: 10px`, bandeau `Description trajet`, bouton `3 points` en haut à droite |
| **`Menu 3 points`** (overlay) | `108 × 123px` | Ouvre `Modifier`, `Complet`, `Masquer`, `Supprimer` (`#FF0000`) + croix fermer |
| **`Pagination`** | `left: 49px`, `top: 679px` (`w: 284px`, `h: 40px`) | `Simple Pagination`, page `1` active en `#8039E9` |
| **Footer** | `top: 727px`, `h: 85px` | Fond `#000000` |

<figure class="mockup-single">
  <img src="assets/mockups/comp-menu-3-points.png" alt="Menu contextuel 3 points" style="max-width:140px;">
  <figcaption>Menu contextuel ouvert depuis le bouton 3 points d'une carte annonce Mobile (node 96:901)</figcaption>
</figure>

---

## 2. Structure Desktop (`120:552` · `1280 × 720px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Mes annonces` (`#DAC4FB`) |
| **Compteur `00 Trajets`** | `left: 276px`, `top: 163px` (centre) | `SUSE Mono` Bold `24px`, `#3478F6` |
| **Grille 4 × 2 cartes `164 × 167px`** | Colonnes à `x = 276, 464, 652, 840px` (gouttière `24px`) · Rangée 1 `top = 192..194px`, Rangée 2 `top = 381px` | 8 cartes `Carte Exemple trajet` (`border: 2px solid #3478F6`, `rounded: 10px`, libellé `Description trajet`) |
| **`Simple Pagination`** | `left: 498px`, `top: 588px` | Centrée sous la grille de cartes |
| **Footer** | `top: 648px`, `h: 72px` | Fond `#000000` |
