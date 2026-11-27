# Fiche trajet

<span class="node-badge">Mobile 64:164 (375×1128)</span> <span class="node-badge">Desktop 120:548 (1280×720)</span>

Vue détaillée d'un trajet sélectionné : carte géographique de l'itinéraire, horaires, nombre de places disponibles, conditions autorisées, description et carte conducteur.

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-fiche-trajet.png" alt="Mobile Fiche trajet">
    <figcaption>Mobile — 64:164 (375 × 1128px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-fiche-trajet.png" alt="Desktop Fiche trajet">
    <figcaption>Desktop — 120:548 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 1. Structure Mobile (`64:164` · `375 × 1128px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Nav Bar** | `top: 0`, `h: 72px` | Fond `#090B10` |
| **Titre `Fiche trajet`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Lien `< Retour`** | `left: 29px`, `top: 146px` (centre) | `Golos Text 16px / 28px`, `#FFFFFF` |
| **Carte itinéraire** | `left: 35px`, `top: 189px`, `w: 306px`, `h: 276px` | `border: 2px solid #3478F6`, `rounded: 22px`, capture Miramas–Arles |
| **Bloc `Départ` / `Arrivée`** | `top: 491px` (titres), `527px` (heures), `559px` (villes) | Titres `Départ` / `Arrivée` en `SUSE Mono` Bold `24px` `#3478F6` · Ligne `7h` — `30 min` — `7h30` + villes `Miramas` / `Arles` en `Golos Text 16px` `#FFFFFF` |
| **`Nombre de place`** | Label `top: 606px` (`SUSE Mono` Bold `24px` `#3478F6`) · Pastilles `top: 631px` | Boutons `1` à `5` (`Small`, `rounded: 4px`) · `1` actif fond `#4E495B` texte `#FFFFFF`, `2..5` fond `#FFFFFF` texte `#6C757D` |
| **`Infos` (`Musique`, `Animaux`)** | Label `top: 696px` (`SUSE Mono` Bold `24px` `#3478F6`) | Checkboxes encadrées par un contour pointillé violet |
| **Zone `Description`** | `left: 12px`, `top: 788px`, `w: 351px`, `h: 143px` | `#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, `padding: 16px`, placeholder `Description` `#ADB5BD` |
| **`Carte contact` conducteur** | `left: 12px`, `top: 941px`, `w: 351px`, `h: 105px` | `Théo Thomas` · `Étudiant MMI 2`, `border: 2px solid #3478F6`, `rounded: 14px`, bouton `Entrer` `#B08AE8` |
| **Footer** | `top: 1043px`, `h: 85px` | Fond `#000000` |

---

## 2. Structure Desktop (`120:548` · `1280 × 720px`)

Conteneur principal positionné à `left: 84px`, `top: 108px`, `w: 1152px`, `h: 504px`.

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Accueil et recherche` (`#DAC4FB`) |
| **Titre `Fiche trajet`** | `left: 0`, `top: 0` | `SUSE Mono` ExtraBold `40px`, `#FFFFFF` |
| **Lien `< Retour`** | `left: 0`, `top: 64px` (centre) | `Golos Text 16px / 28px`, `#FFFFFF` |
| **Colonne gauche (`w: 600px`)** | `left: 0` | — |
| ↳ Carte itinéraire | `top: 80px`, `w: 600px`, `h: 300px` | `border: 2px solid #3478F6`, `rounded: 8px` |
| ↳ `Conducteur à contacter` | `left: 124px`, `top: 396px`, `w: 351px`, `h: 105px` | `Natael` · `Étudiant MMI 2` (centrée sous la carte) |
| **Colonne droite (`left: 640px`, `w: 512px`)** | Gouttière `40px` | — |
| ↳ `Informations du trajet` | `top: 80px`, `w: 512px`, `h: 130px` | Panneau `#000000`, `rounded: 8px` · Labels `Départ` / `Arrivée` (`SUSE Mono` Bold `28px` `#3478F6`) + `Miramas` / `Arles` (`SUSE Mono` Bold `32px` `#FFFFFF`) |
| ↳ `Horaires du trajet` | `top: 226px`, `w: 512px`, `h: 64px` | Panneau `#000000`, `rounded: 8px` · `7h  →  30 min  →  7h30` (`Golos Text 16px` `#DAC4FB` à `left: 24px`, `top: 18px`) |
| ↳ `Nombre de place` | Label `top: 306px` (`Golos Text 16px` `#3478F6`) · Pastilles `top: 344px` | `1` actif en `#8039E9` texte `#FFFFFF` ; `2..5` en `#FFFFFF` texte `#6C757D` |
| ↳ `Infos` | `top: 390px` | Label `Infos` (`#3478F6`, `w: 90px`) + `Musique` coché (`#7749F8`) à `left: 740px` + `Animaux` non coché à `left: 950px` |
| ↳ `Description du trajet` | `top: 438px`, `w: 512px`, `h: 66px` | Fond `#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, `padding: 16px`, texte `Description` (`#4E495B`) |
| **Footer** | `top: 648px`, `h: 72px` | Fond `#000000` |
