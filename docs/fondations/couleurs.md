# Couleurs

<span class="node-badge">Charte graphique · Color (38:142)</span>

Cette page recense l'ensemble des couleurs définies dans la planche **Colors** de la page `Charte graphique`, ainsi que les couleurs neutres et sémantiques issues des composants du kit UI utilisés sur les écrans Mobile et Desktop.

<figure class="mockup-single">
  <img src="assets/mockups/charte-colors.png" alt="Planche Colors de la charte graphique Figma">
  <figcaption>Figma — Charte graphique / Color (node 38:142, 1440 × 852px)</figcaption>
</figure>

---

## 1. Palette principale (Primary, Secondary, Accent)

### Primary Color

<div class="swatch-grid">
  <div class="swatch-card">
    <div class="swatch-color" style="background:#090B10;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Primary</p>
      <p class="swatch-hex">#090B10</p>
      <p class="swatch-var">--primary-color</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#000000;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Primary Dark</p>
      <p class="swatch-hex">#000000</p>
      <p class="swatch-var">--primary-dark</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#4E495B;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Primary Light</p>
      <p class="swatch-hex">#4E495B</p>
      <p class="swatch-var">--primary-light · --gris</p>
    </div>
  </div>
</div>

### Secondary Color

<div class="swatch-grid">
  <div class="swatch-card">
    <div class="swatch-color" style="background:#3478F6;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Secondary</p>
      <p class="swatch-hex">#3478F6</p>
      <p class="swatch-var">--secondary-color</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#0758A9;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Secondary Dark</p>
      <p class="swatch-hex">#0758A9</p>
      <p class="swatch-var">--secondary-dark</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#4BD8FF;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Secondary Light</p>
      <p class="swatch-hex">#4BD8FF</p>
      <p class="swatch-var">--secondary-light</p>
    </div>
  </div>
</div>

### Accent Color

<div class="swatch-grid">
  <div class="swatch-card">
    <div class="swatch-color" style="background:#B08AE8;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Accent</p>
      <p class="swatch-hex">#B08AE8</p>
      <p class="swatch-var">--accent-color</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#8039E9;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Accent Dark</p>
      <p class="swatch-hex">#8039E9</p>
      <p class="swatch-var">--accent-dark</p>
    </div>
  </div>
  <div class="swatch-card">
    <div class="swatch-color" style="background:#DAC4FB;"></div>
    <div class="swatch-meta">
      <p class="swatch-title">Accent Light</p>
      <p class="swatch-hex">#DAC4FB</p>
      <p class="swatch-var">--accent-light</p>
    </div>
  </div>
</div>

<div class="note-figma">
  <strong>Note factuelle sur la planche Figma Colors :</strong><br>
  • Sur la carte <em>Primary Light</em> (<code>49:1730</code>), le libellé texte affiché sous le carré indique <code>#4BD8FF</code>, mais la variable Figma et le remplissage réel du bloc et des maquettes sont <code>#4E495B</code>.<br>
  • Sur la carte <em>Accent</em> (<code>49:1787</code>), le libellé texte affiché sous le carré indique <code>#090B10</code>, mais la variable Figma et le remplissage réel du bloc et des boutons sont <code>#B08AE8</code>.
</div>

### Tableau d'usage exact dans les écrans

| Variable Figma | Code Hex | Usages observés dans les maquettes |
| :--- | :--- | :--- |
| `--primary-color` | `#090B10` | Fond de toutes les pages (Mobile & Desktop), fond de la Nav Bar, texte principal sur cartes Résultats Desktop |
| `--primary-dark` | `#000000` | Fond du Footer (Mobile & Desktop), fond du Menu drawer mobile, fond des panneaux de formulaire/cartes sur Desktop |
| `--primary-light` / `--gris` | `#4E495B` | Texte des champs & placeholders Desktop, texte des cartes Profil (`Prénom Nom`, `Informations`, `Préférences`), villes secondaires Résultats Desktop, fond pastille active `1` sur Fiche trajet Mobile |
| `--secondary-color` | `#3478F6` | Tous les titres `H2`/`H3` de sections, labels des formulaires Desktop, bordures `2px` des cartes/blocs (`Itinéraire`, `Carte heure`, `Trajet`, `Carte Exemple/Annonces`, `Carte contact`, `Carte map`), bordures `1px` des cartes Profil |
| `--secondary-dark` | `#0758A9` | Défini en variable dans la charte (`ColorPalette`) |
| `--secondary-light` | `#4BD8FF` | Défini en variable dans la charte (`ColorPalette`) |
| `--accent-color` | `#B08AE8` | Fond des boutons CTA (`Rechercher`, `Se connecter`, `S'inscrire`, `Publier`, `Modifier`, `Appliquer`, `Contacter`), boutons ronds `Inversion` et `Entrer` / `Voir le trajet`, liens textuels desktop (`Mot de passe oublié`, `S'inscrire`, `Se connecter`) |
| `--accent-dark` | `#8039E9` | État `Hovered` des boutons Fill/Outline, item actif dans `Simple Pagination`, jours (`L`, `M`, `J`) et places (`1`) sélectionnés, fond des logos `logo_normal.svg` / `favicon_normal.svg` |
| `--accent-light` | `#DAC4FB` | Lien actif dans la Navigation Desktop, bouton `Fill` état `Disabled` (avec `opacity: 0.55`), texte de la barre horaire (`7h → 30 min → 7h30`) sur Desktop Fiche trajet |

---

## 2. Couleurs neutres & Kit UI (Bootstrap)

| Nom / Token Figma | Code Hex | Usages observés |
| :--- | :--- | :--- |
| `Default/White` / `--blanc` | `#FFFFFF` | Fond des champs texte, cartes, boutons `Outline`, pagination inactive, textes principaux sur fond sombre (`#090B10`) |
| `Gray/100` | `#F8F9FA` | Fond des planches `Colors` et `Typography` de la Charte |
| `Gray/200` | `#E9ECEF` | Bordure `1px` des items de `Simple Pagination` et des pastilles Jours / Places |
| `Gray/300` | `#DEE2E6` | Bordure `1px` des inputs mobiles et zones `Description` |
| *(Sans token)* | `#D9D9D9` | Fond du composant `Horaire` (Mobile & Desktop Modifier), cercles placeholders `Point d'intérêt` et avatars |
| *(Sans token)* | `#BDBDBD` | Mention `© 2026 Tous droits réservés.` dans le Footer (`14px`) |
| `Secondary/Light Color` | `#ABB5BE` | Bordure `1px` des checkboxes non cochées |
| `Gray/500` | `#ADB5BD` | Placeholder des inputs et textarea sur Mobile, texte `Disabled` dans `Simple Pagination` |
| `Gray/600` | `#6C757D` | Texte des items normaux de `Simple Pagination`, variante `Secondary` des boutons `Outline` |
| `Body Text / Base Color` | `#68717A` | Textes internes des blocs Mobile (`Itinéraire`, `Carte heure`, `Horaire`, `Trajet`, `Carte Exemple/Annonces`) |
| `Gray/800` / `Dark` | `#343A40` | Titres de la Charte graphique, texte du bouton Fill `Warning` |
| `Heading/Title Color` | `#152536` | Titres de sections dans la planche `Color` |
| `Body Text Color` | `#6B7176` | Codes hex sous les pastilles de la planche `Color` |

---

## 3. Couleurs sémantiques & états du Kit UI

| Nom / Token Figma | Code Hex | Usage |
| :--- | :--- | :--- |
| `/Status Color / Success` | `#28A745` | Bouton `Success` (Fill & Outline) |
| `/Status Color / Danger` | `#DC3545` | Bouton `Danger` (Fill & Outline) |
| *(Action destructive)* | `#FF0000` | Texte `Supprimer` dans le composant `Menu 3 points` (`96:902`) |
| `/Status Color / Info` | `#17A2B8` | Bouton `Info` (Fill & Outline) |
| `/Status Color / Warning` | `#FFC107` | Bouton `Warning` (Fill & Outline) |
| `Primary/Color` (Kit) | `#7749F8` | Fond de checkbox cochée (`87:764`), bordure pagination active, bordure bouton `Outline Primary Disabled`, header des planches Charte |
| `Primary/Color Dark` | `#5227CC` | Bordure du bouton `Outline Primary Hovered` |
| `Indigo/500` | `#6610F2` | Texte du bouton `Outline Primary Disabled` |
