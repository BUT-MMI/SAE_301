# Logos & assets

Le dépôt fournit **9 déclinaisons SVG officielles du logo amU** (dans `assets/logo/`) ainsi que la famille de police **`Monument Grotesk`** (dans `assets/fonts/`). Les écrans Figma contiennent également plusieurs placeholders graphiques à remplacer lors de l'intégration finale.

---

## 1. Déclinaisons du logo SVG (`assets/logo/`)

Tous les logos vectoriels utilisent la police `Monument Grotesk` (`98px` pour `amU`, `31px` pour le slogan `Sans frais ni pression`).

### Logos rectangulaires (`logo_*`)

<div class="logo-grid">
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-light">
      <img src="assets/logo/logo_normal.svg" alt="logo_normal.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_normal.svg</code>
      Fond violet <code>#8039E9</code> · Traits &amp; texte <code>#FFFFFF</code> · ViewBox <code>513.722 × 382.751</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-dark">
      <img src="assets/logo/logo_blanc.svg" alt="logo_blanc.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_blanc.svg</code>
      Fond transparent · Monochrome <code>#FFFFFF</code> · ViewBox <code>474.518 × 345.816</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-light">
      <img src="assets/logo/logo_noir.svg" alt="logo_noir.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_noir.svg</code>
      Fond transparent · Monochrome noir · ViewBox <code>474.518 × 345.816</code>
    </div>
  </div>
</div>

### Favicons circulaires (`favicon_*`)

<div class="logo-grid">
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-light">
      <img src="assets/logo/favicon_normal.svg" alt="favicon_normal.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/favicon_normal.svg</code>
      Cercle <code>#8039E9</code> · Traits &amp; texte <code>#FFFFFF</code> · ViewBox <code>505.692 × 382.751</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-dark">
      <img src="assets/logo/favicon_blanc.svg" alt="favicon_blanc.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/favicon_blanc.svg</code>
      Version blanche sur fond sombre · ViewBox <code>505.692 × 382.751</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-light">
      <img src="assets/logo/favicon_noir.svg" alt="favicon_noir.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/favicon_noir.svg</code>
      Version noire sur fond clair · ViewBox <code>505.692 × 382.751</code>
    </div>
  </div>
</div>

### Logos avec slogan (`logo_tag_*`) — *« Sans frais ni pression »*

<div class="logo-grid">
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-dark">
      <img src="assets/logo/logo_tag_normal.svg" alt="logo_tag_normal.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_tag_normal.svg</code>
      Fond violet <code>#8039E9</code> + slogan blanc · ViewBox <code>513.722 × 530.336</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-dark">
      <img src="assets/logo/logo_tag_blanc.svg" alt="logo_tag_blanc.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_tag_blanc.svg</code>
      Monochrome <code>#FFFFFF</code> + slogan · ViewBox <code>513.722 × 530.336</code>
    </div>
  </div>
  <div class="logo-tile">
    <div class="logo-tile-preview logo-tile-light">
      <img src="assets/logo/logo_tag_noir.svg" alt="logo_tag_noir.svg">
    </div>
    <div class="logo-tile-caption">
      <code>assets/logo/logo_tag_noir.svg</code>
      Monochrome noir + slogan · ViewBox <code>513.722 × 530.336</code>
    </div>
  </div>
</div>

---

## 2. Polices locales (`assets/fonts/`)

Le dossier `assets/fonts/` du dépôt contient 8 fichiers `.ttf` de la famille **Monument Grotesk** :

- `MonumentGrotesk-Regular.ttf`
- `MonumentGrotesk-Italic.ttf`
- `MonumentGrotesk-Medium.ttf`
- `MonumentGrotesk-MediumItalic.ttf`
- `MonumentGrotesk-Bold.ttf`
- `MonumentGrotesk-BoldItalic.ttf`
- `MonumentGrotesk-Mono.ttf`
- `MonumentGrotesk-Semi-Mono.ttf`

---

## 3. Placeholders présents dans les maquettes Figma

Les maquettes Figma utilisent plusieurs éléments visuels temporaires (« wireframe ») qu'il faut connaître pour reproduire fidèlement le design ou les substituer par de vrais assets lors du développement :

| Élément dans Figma | Apparence dans la maquette | Emplacements |
| :--- | :--- | :--- |
| **Logo `L` violet** | Cercle violet `41 × 41px` avec lettre `L` noire | Nav Bar (Mobile & Desktop), Footer (Mobile & Desktop), avatar Profil (`50×50` Mobile, `56×56` Desktop), avatar Contact Desktop (`100×100`) |
| **Bouton `Point d'intérêt`** | Cercle gris `#D9D9D9` `44 × 44px` avec lettre `L` noire | Champs Départ/Arrivée (`Itinéraire` Mobile, `Accueil` & `Résultats` Desktop), cartes résultats Desktop |
| **Visuel `Carte Exemple trajet` / `Carte Annonces`** | Fond blanc avec croix diagonale `X` noire sur la zone haute | `Accueil et Recherche` (Mobile & Desktop), `Mes annonces` (Mobile & Desktop) |
| **Avatar vide** | Cercle gris (`#D9D9D9`) ou cercle noir (`#000000`) / contour fin | Carte `Trajet` (Résultats Mobile/Desktop), `Carte contact` (`Fiche trajet`, `Contact` Mobile), `Menu` drawer Mobile (`43×43`) |
| **Carte itinéraire** | Capture statique d'itinéraire Miramas → Arles | `Fiche trajet` (Mobile `306×276`, Desktop `600×300`) |
