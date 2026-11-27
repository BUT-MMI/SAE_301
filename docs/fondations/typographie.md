# Typographie

<span class="node-badge">Typography Mobile (38:712)</span> <span class="node-badge">Typography PC (66:400)</span>

La hiérarchie typographique de BlaBlamU repose sur **3 familles Google Fonts** (`SUSE Mono`, `Golos Text`, `Inter`) complétées par **`Monument Grotesk`** pour les déclinaisons vectorielles du logo `amU`.

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/charte-typography-mobile.png" alt="Charte typographique Mobile">
    <figcaption>Typography Mobile (38:712)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/charte-typography-pc.png" alt="Charte typographique Desktop">
    <figcaption>Typography PC (66:400)</figcaption>
  </figure>
</div>

---

## 1. Familles de polices et rôles

| Famille | Graisses utilisées | Rôles dans l'interface |
| :--- | :--- | :--- |
| **`SUSE Mono`** | Bold (`700`), ExtraBold (`800`) | Titres principaux des écrans (`H1` blanc), titres de sections (`H2`/`H3` bleu `#3478F6`), villes Départ/Arrivée sur Fiche trajet Desktop, chevron `›` des boutons Desktop |
| **`Golos Text`** | Regular (`400`) | Corps de texte, navigation Desktop & Menu Mobile, Footer, champs `Itinéraire`, `Carte heure`, `Horaire`, cartes `Trajet`, cartes `Exemple trajet`, labels & inputs Desktop |
| **`Inter`** | Regular (`400`), SemiBold (`600`), Bold (`700`) | Composants du Kit UI : boutons `Fill`/`Outline` et `Btn Contact` (`600`), inputs Mobile (`400`), `Simple Pagination` & sélecteurs Jours/Places (`400`), labels checkboxes `Musique`/`Animaux` (`400`), `Menu 3 points` (`400`), `Carte contact` (`400`) |
| **`Monument Grotesk`** | Regular (`400`, fichiers `.ttf` dans `assets/fonts/`) | Texte `amU` et slogan `Sans frais ni pression` intégrés dans les SVG du logo |

### Chargement via Google Fonts

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Golos+Text:wght@400;500;600;700&family=Inter:wght@400;600;700;800&family=SUSE+Mono:wght@700;800&display=swap" rel="stylesheet">
```

---

## 2. Échelle Mobile (`375px`)

### Aperçu live (fond sombre `#090B10`)

<div class="typo-preview">
  <div class="typo-row">
    <span class="typo-tag">H1 ExtraBold</span>
    <span class="font-suse" style="font-size:32px;font-weight:800;line-height:1;">Bienvenue · 32px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">H1 Bold</span>
    <span class="font-suse" style="font-size:32px;font-weight:700;line-height:1;letter-spacing:-0.64px;">h1. Heading Title · 32px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">H2 Bold</span>
    <span class="font-suse" style="font-size:24px;font-weight:700;line-height:1;color:#3478F6;">Exemples de trajet · 24px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">H3 Bold</span>
    <span class="font-suse" style="font-size:20px;font-weight:700;line-height:1;color:#3478F6;">Horaire / Jours · 20px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">Body Text</span>
    <span class="font-golos" style="font-size:16px;font-weight:400;line-height:28px;">À propos - Contact - Mentions Légales · 16px / 28px</span>
  </div>
</div>

### Tableau des styles Mobile

| Style Figma | Police | Graisse | Taille | Hauteur de ligne | Interlettrage | Usage principal |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `Mobile H1 Extra-Bold` | `SUSE Mono` | `800` | `32px` | `100%` (`normal`) | `0` | Titres de pages centrés (`Bienvenue`, `Résultats`, `Fiche trajet`, `Contact`, `Inscription`, `Connexion`, `Publier un trajet`, `Modifier le trajet`, `Annonces`, `Informations`, `Préférences`) |
| `Mobile H1 Bold` | `SUSE Mono` | `700` | `32px` | `100%` (`normal`) | `-0.64px` (`-2%`) | Défini dans la planche `Typography Mobile` |
| `Mobile H2 Bold` | `SUSE Mono` | `700` | `24px` | `100%` (`normal`) | `0` | Sous-titres de sections et labels sur Mobile en `#3478F6` |
| `Mobile H3 Bold` | `SUSE Mono` | `700` | `20px` | `100%` (`normal`) | `0` | Labels `Horaire` et `Jours` sur Publier/Modifier Mobile en `#3478F6` |
| `Mobile H2 Extra-Bold` | `SUSE Mono` | `800` | `24px` | `100%` (`normal`) | `0` | Variante ExtraBold définie dans la planche |
| `Mobile H3 Extra-Bold` | `SUSE Mono` | `800` | `20px` | `100%` (`normal`) | `0` | Variante ExtraBold définie dans la planche |
| `Body Text` | `Golos Text` | `400` | `16px` | `28px` | `0` | Corps, cartes, menu, footer (`14px / 28px` pour le copyright) |
| *(Carte Trajet détails)* | `Golos Text` | `400` | `15px` / `13px` | `28px` | `0` | Horaires (`15px`) et villes (`13px`) dans la carte `Trajet` Mobile |

---

## 3. Échelle Desktop (`1280px`)

### Aperçu live (fond sombre `#090B10`)

<div class="typo-preview">
  <div class="typo-row">
    <span class="typo-tag">PC H1 ExtraBold</span>
    <span class="font-suse" style="font-size:40px;font-weight:800;line-height:1;">Bienvenue · 40px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">PC H2 ExtraBold</span>
    <span class="font-suse" style="font-size:32px;font-weight:800;line-height:1;">Profil · 32px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">PC H3 Bold</span>
    <span class="font-suse" style="font-size:28px;font-weight:700;line-height:1;color:#3478F6;">Trajets proposés · 28px</span>
  </div>
  <div class="typo-row">
    <span class="typo-tag">Body Text</span>
    <span class="font-golos" style="font-size:16px;font-weight:400;line-height:28px;">Accueil et recherche · Publier un trajet · 16px / 28px</span>
  </div>
</div>

### Tableau des styles Desktop (PC)

| Style Figma | Police | Graisse | Taille | Hauteur de ligne | Interlettrage | Usage principal |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `PC H1 Extra-Bold` | `SUSE Mono` | `800` | `40px` | `100%` (`normal`) | `0` | Titres principaux Desktop (`Bienvenue`, `Résultats`, `Fiche trajet`, `Contact`, `COMMENCER L'INSCRIPTION`, `SE CONNECTER`, `Publier un trajet`, `Modifier le trajet`, `Informations`, `Préférences`) |
| `PC H1 Bold` | `SUSE Mono` | `700` | `40px` | `100%` (`normal`) | `-0.8px` (`-2%`) | Défini dans la planche `Typography` |
| `PC H2 Bold` | `SUSE Mono` | `700` | `32px` | `100%` (`normal`) | `0` | Villes `Miramas` / `Arles` sur Desktop Fiche trajet |
| `PC H2 Extra-Bold` | `SUSE Mono` | `800` | `32px` | `100%` (`normal`) | `0` | Titre `Profil` sur Desktop (`98:236`) |
| `PC H3 Bold` | `SUSE Mono` | `700` | `28px` | `100%` (`normal`) | `0` | Titres de blocs (`Exemple de trajet`, `Trajets proposés`, `Départ`/`Arrivée`, `Itinéraire`, `00 Trajets` à `24px`) |
| `h4` à `h6` (Charte PC) | `SUSE Mono` | `700` / `800` | `24px` / `20px` / `16px` | `100%` (`normal`) | `0` | Échelle complète définie sur la planche `Typography` (`66:400`) |
| `Body Text` | `Golos Text` | `400` | `16px` | `28px` | `0` | Liens navbar, labels formulaires Desktop (`#3478F6`), textes boutons Desktop (`#FFFFFF`), champs et descriptions |

---

## 4. Styles `Inter` des composants UI

| Composant | Police & graisse | Taille / Line-height | Couleur |
| :--- | :--- | :--- | :--- |
| Bouton `Large` & `Medium` | `Inter` SemiBold (`600`) | `16px` / `18px` | `#FFFFFF` (ou `#343A40` Warning, couleur accent en Outline) |
| Bouton `Small` | `Inter` SemiBold (`600`) | `14px` / `16px` | `#FFFFFF` (ou couleur accent en Outline) |
| Input texte Mobile | `Inter` Regular (`400`) | `16px` / `20px` | `#ADB5BD` (placeholder) |
| `Simple Pagination` (Default) | `Inter` Regular (`400`) | `16px` / `16px` | `#6C757D` (normal), `#ADB5BD` (disabled), `#FFFFFF` (actif) |
| Sélecteurs Jours / Places (`Small`) | `Inter` Regular (`400`) | `14px` / `14px` | `#6C757D` (inactif), `#FFFFFF` (actif) |
| Checkbox label (`Musique`, `Animaux`) | `Inter` Regular (`400`) | `16px` / `28px` | `#FFFFFF` |
| `Menu 3 points` | `Inter` Regular (`400`) | `14px` / `14px` | `#000000` (`#FF0000` pour `Supprimer`) |
| `Carte contact` | `Inter` Regular (`400`) | `16px` / `28px` | `#000000` |
