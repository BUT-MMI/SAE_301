# Résultats

<span class="node-badge">Mobile 64:144 (375×812)</span> <span class="node-badge">Desktop 120:547 (1280×720)</span>

Affiche les critères de recherche en cours ainsi que la liste paginée des trajets proposés.

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-resultats.png" alt="Mobile Résultats">
    <figcaption>Mobile — 64:144 (375 × 812px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-resultats.png" alt="Desktop Résultats">
    <figcaption>Desktop — 120:547 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 1. Structure Mobile (`64:144` · `375 × 812px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Nav Bar** | `top: 0`, `h: 72px` | Fond `#090B10` |
| **Titre `Résultats`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Bloc `Itinéraire`** | `left: 12px`, `top: 132px`, `w: 352px`, `h: 105px` | Pré-rempli `Miramas` → `Arles` avec boutons POI et Inversion |
| **Champ `Carte heure`** | `left: 12px`, `top: 247px`, `w: 164px`, `h: 44px` | `Partir:` |
| **Sous-titre `Trajets proposés`** | `left: 12px`, `top: 316px` (centre) | `SUSE Mono` Bold `24px`, `#3478F6` |
| **Liste des 4 cartes `Trajet`** | `left: 12px`, `351 × 74px` chacune · `top = 346, 430, 514, 598px` (gap `10px`) | Conducteurs affichés : `Nataël`, `Conducteur`, `Conducteur`, `Nataël` · `7h — 30 min — 7h30` (`Miramas` / `Arles`) |
| **`Simple Pagination`** | `left: 46px`, `top: 686px` (`w: 284px`, `h: 40px`) | Page `1` active (`#8039E9`) |
| **Footer** | `top: 727px`, `h: 85px` | Fond `#000000` |

---

## 2. Structure Desktop (`120:547` · `1280 × 720px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Accueil et recherche` (`#DAC4FB`) |
| **Titre `Résultats`** | `left: 0`, `top: 0` (dans conteneur `1152px`) | `SUSE Mono` ExtraBold `40px`, `#FFFFFF` |
| **Colonne gauche : Panneau recherche** | `left: 0`, `top: 80px`, `w: 288px`, `h: 378px` | Fond `#000000`, `rounded: 8px`, padding interne `20px` |
| ↳ `Point de départ` (`Miramas`) | `left: 20px`, `top: 50px`, `w: 248px`, `h: 48px` | Label `#3478F6` (`top: 20px`) · input blanc + bouton POI (`left: 199px`) |
| ↳ `Point d'arrivée` (`Arles`) | `left: 20px`, `top: 146px`, `w: 248px`, `h: 48px` | Label `#3478F6` (`top: 116px`) · input blanc + bouton POI (`left: 200px`) |
| ↳ `Date et heure` (`Partir :`) | `left: 20px`, `top: 242px`, `w: 248px`, `h: 48px` | Label `#3478F6` (`top: 212px`) · input blanc |
| ↳ Bouton `Rechercher` | `left: 20px`, `top: 310px`, `w: 248px`, `h: 48px` | Fond `#B08AE8`, `rounded: 6px`, `Golos Text 16px` `#FFFFFF` |
| **Colonne droite : `Trajets proposés`** | `left: 328px` (gouttière `40px`), `w: 824px` | Sous-titre `SUSE Mono` Bold `28px`, `#3478F6` à `top: 80px` |
| ↳ 4 cartes `Trajet` | `824 × 80px`, `top = 120, 204, 288, 372px` (gap `4px`) | Conducteurs : `Raphaël`, `Natael`, `Conducteur`, `Conducteur` · `border: 2px solid #3478F6`, `rounded: 8px` · inclut bouton POI + bouton rond `›` |
| ↳ `Simple Pagination` | `left: 610px`, `top: 464px` | Centrée sous la liste de résultats |
| **Footer** | `top: 648px`, `h: 72px` | Fond `#000000` |
