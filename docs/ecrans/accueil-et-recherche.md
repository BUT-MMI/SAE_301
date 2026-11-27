# Accueil et Recherche

<span class="node-badge">Mobile 11:246 (375×825)</span> <span class="node-badge">Desktop 120:546 (1280×720)</span>

Page d'entrée de BlaBlamU permettant de lancer une recherche d'itinéraire ou de sélectionner un exemple de trajet prédéfini.

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-accueil.png" alt="Mobile Accueil et Recherche">
    <figcaption>Mobile — 11:246 (375 × 825px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-accueil.png" alt="Desktop Accueil et recherche">
    <figcaption>Desktop — 120:546 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 1. Structure Mobile (`11:246` · `375 × 825px`)

| Zone | Position & dimensions exactes | Détails visuels |
| :--- | :--- | :--- |
| **Nav Bar** | `top: 0`, `w: 375px`, `h: 72px` | Fond `#090B10`, logo gauche + menu burger |
| **Titre `Bienvenue`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Bloc `Itinéraire`** | `left: 12px`, `top: 132px`, `w: 352px`, `h: 105px` | Fond `#FFFFFF`, `border: 2px solid #3478F6`, `rounded: 14px` · `Point de départ : Miramas`, `Point d'arrivée : Arles`, 2 boutons POI `L` + bouton `Inversion` `#B08AE8` |
| **Champ `Carte heure`** | `left: 12px`, `top: 247px`, `w: 164px`, `h: 44px` | Fond `#FFFFFF`, `border: 2px solid #3478F6`, `rounded: 14px` · icône calendrier + `Partir:` |
| **Bouton `Rechercher`** | Centré (`w: 272px`, `h: 44px`), `top: 301px` | Fond `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px / 18px` `#FFFFFF` |
| **Sous-titre `Exemples de trajet`** | `left: 12px`, `top: 364px` (centre) | `SUSE Mono` Bold `24px`, `#3478F6` |
| **Grille 2 × 2 `Carte Exemple trajet`** | `164 × 167px` chacune · Rangée 1 `top: 389px`, Rangée 2 `top: 566px` · Col. gauche `left: 11px`, Col. droite `left: ~198px` | `#FFFFFF`, `border: 2px solid #3478F6`, `rounded: 10px` · Titres : `IUT`, `Resto Universitaire`, `Gare`, `Centre Ville` |
| **Footer** | `top: 743px`, `w: 375px`, `h: 85px` | Fond `#000000` |

---

## 2. Structure Desktop (`120:546` · `1280 × 720px`)

| Zone | Position & dimensions exactes | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Accueil et recherche` (`#DAC4FB`) |
| **Conteneur principal** | `left: 64px`, `top: 108px`, `w: 1152px`, `h: 504px` | — |
| **Titre `Bienvenue`** | `left: 0`, `top: 0` | `SUSE Mono` ExtraBold `40px`, `#FFFFFF`, aligné à gauche |
| **Panneau `Recherche de trajet`** | `left: 0`, `top: 78px`, `w: 1152px`, `h: 126px` | Fond `#000000`, `rounded: 8px` · Labels (`top: 18px`) en `Golos Text 16px` `#3478F6` |
| ↳ Champ `Point de départ` | `left: 24px`, `top: 48px`, `w: 300px`, `h: 48px` | Fond `#FFFFFF`, `rounded: 6px`, texte `#4E495B` + bouton POI `44 × 44px` (`left: 239px`, `top: 2px`) |
| ↳ Champ `Point d'arrivée` | `left: 348px`, `top: 48px`, `w: 300px`, `h: 48px` | Fond `#FFFFFF`, `rounded: 6px`, texte `#4E495B` + bouton POI `44 × 44px` (`left: 240px`, `top: 2px`) |
| ↳ Champ `Date et heure` | `left: 672px`, `top: 48px`, `w: 216px`, `h: 48px` | Fond `#FFFFFF`, `rounded: 6px`, texte `#4E495B`, label `Partir :` |
| ↳ Bouton `Rechercher` | `left: 912px`, `top: 48px`, `w: 216px`, `h: 48px` | Fond `#B08AE8`, `rounded: 6px`, `Golos Text 16px` `#FFFFFF` |
| **Sous-titre `Exemple de trajet`** | `left: 0`, `top: 240px` | `SUSE Mono` Bold `28px`, `#3478F6` |
| **Grille 4 × 1 `Exemple de trajet 1..4`** | `top: 300px`, `264 × 200px` chacune, `x = 0, 296, 592, 888` (gouttière `32px`) | `#FFFFFF`, `border: 2px solid #3478F6`, `rounded: 10px`, libellé `Description trajet` |
| **Footer** | `top: 648px`, `h: 72px` | Fond `#000000` |

<div class="note-figma">
  <strong>Différences factuelles Mobile / Desktop :</strong><br>
  • Mobile : titre <code>Bienvenue</code> centré, champ <code>Itinéraire</code> regroupé avec bouton Inversion, cartes exemples en grille 2×2 nommées (<code>IUT</code>, <code>Resto Universitaire</code>, <code>Gare</code>, <code>Centre Ville</code>).<br>
  • Desktop : titre aligné à gauche, barre de recherche horizontale sur panneau noir <code>1152 × 126px</code> (sans bouton inversion), 4 cartes exemples en ligne intitulées <code>Exemple de trajet</code> / <code>Description trajet</code>.
</div>
