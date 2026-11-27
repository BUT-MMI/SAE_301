# Boutons & actions

<span class="node-badge">Charte · Buttons (38:1506)</span> <span class="node-badge">Btn Contact (131:1797)</span> <span class="node-badge">Entrer (87:842)</span> <span class="node-badge">Inversion (82:720 · 87:731)</span>

---

## 1. Système de boutons de la Charte (`38:1506`)

La planche `Buttons` définit deux familles (`Fill` et `Outline`), six couleurs sémantiques, trois états (`Default`, `Hovered`, `Disabled`) et trois tailles (`Large`, `Medium`, `Small`).

<figure class="mockup-single">
  <img src="assets/mockups/charte-buttons.png" alt="Planche Buttons de la charte graphique Figma">
  <figcaption>Figma — Charte graphique / Buttons (node 38:1506, 1440 × 795px)</figcaption>
</figure>

### Aperçu live des variantes (fidèle au Figma)

<div class="btn-demo-box">
  <div class="btn-demo-row">
    <span class="btn-demo-label">Fill Colors</span>
    <span class="bb-btn bb-fill-primary">Primary</span>
    <span class="bb-btn bb-fill-secondary">Secondary</span>
    <span class="bb-btn bb-fill-success">Success</span>
    <span class="bb-btn bb-fill-danger">Danger</span>
    <span class="bb-btn bb-fill-info">Info</span>
    <span class="bb-btn bb-fill-warning">Warning</span>
  </div>
  <div class="btn-demo-row">
    <span class="btn-demo-label">Fill States</span>
    <span class="bb-btn bb-fill-hover">Hovered</span>
    <span class="bb-btn bb-fill-disabled">Disabled</span>
  </div>
  <div class="btn-demo-row">
    <span class="btn-demo-label">Fill Sizes</span>
    <span class="bb-btn bb-btn-lg bb-fill-primary">Large</span>
    <span class="bb-btn bb-fill-primary">Medium</span>
    <span class="bb-btn bb-btn-sm bb-fill-primary">Small</span>
  </div>
  <hr style="margin:14px 0;border:none;border-top:1px dashed #DEE2E6;">
  <div class="btn-demo-row">
    <span class="btn-demo-label">Outline Colors</span>
    <span class="bb-btn bb-outline-primary">Primary</span>
    <span class="bb-btn bb-outline-secondary">Secondary</span>
    <span class="bb-btn bb-outline-success">Success</span>
    <span class="bb-btn bb-outline-danger">Danger</span>
    <span class="bb-btn bb-outline-info">Info</span>
    <span class="bb-btn bb-outline-warning">Warning</span>
  </div>
  <div class="btn-demo-row">
    <span class="btn-demo-label">Outline States</span>
    <span class="bb-btn bb-outline-hover">Hovered</span>
    <span class="bb-btn bb-outline-disabled">Disabled</span>
  </div>
  <div class="btn-demo-row">
    <span class="btn-demo-label">Outline Sizes</span>
    <span class="bb-btn bb-btn-lg bb-outline-primary">Large</span>
    <span class="bb-btn bb-outline-primary">Medium</span>
    <span class="bb-btn bb-btn-sm bb-outline-primary">Small</span>
  </div>
</div>

### Spécifications exactes (Charte `38:1506`)

| Dimension / Propriété | Large | Medium (défaut) | Small |
| :--- | :--- | :--- | :--- |
| **Padding** | `16px 24px` | `10px 16px` | `8px 12px` |
| **Hauteur totale** | `50px` | `38px` | `32px` |
| **Typographie** | `Inter` SemiBold `16px / 18px` | `Inter` SemiBold `16px / 18px` | `Inter` SemiBold `14px / 16px` |
| **Rayon (`border-radius`)** | `6px` | `6px` | `6px` |

#### Tableau des couleurs Fill & Outline

| Variante / État | Fill (Fond · Texte) | Outline (`1px solid`, Fond · Bordure · Texte) |
| :--- | :--- | :--- |
| **Primary** | `#B08AE8` · `#FFFFFF` | `#FFFFFF` · `#B08AE8` · `#B08AE8` |
| **Secondary** | `#3478F6` · `#FFFFFF` | `#FFFFFF` · `#6C757D` · `#6C757D` |
| **Success** | `#28A745` · `#FFFFFF` | `#FFFFFF` · `#28A745` · `#28A745` |
| **Danger** | `#DC3545` · `#FFFFFF` | `#FFFFFF` · `#DC3545` · `#DC3545` |
| **Info** | `#17A2B8` · `#FFFFFF` | `#FFFFFF` · `#17A2B8` · `#17A2B8` |
| **Warning** | `#FFC107` · `#343A40` | `#FFFFFF` · `#FFC107` · `#FFC107` |
| **Hovered (Primary)** | `#8039E9` · `#FFFFFF` | `#8039E9` · `#5227CC` · `#FFFFFF` |
| **Disabled (Primary)** | `#DAC4FB` · `#FFFFFF` · `opacity: 0.55` | `#FFFFFF` · `#7749F8` · `#6610F2` · `opacity: 0.55` |

---

## 2. Boutons CTA sur les écrans

Sur les écrans de l'application, les boutons d'action principaux reprennent le fond `#B08AE8` et le rayon `6px`, avec des hauteurs fixes adaptées au support :

| Support | Composant / Écrans | Dimensions | Typographie |
| :--- | :--- | :--- | :--- |
| **Mobile** | `Btn Contact` (`131:1797`) : Contact, Inscription, Connexion, Publier, Modifier, Informations, Préférences | `110 × 44px` (`padding: 10px 16px`) | `Inter` SemiBold `16px / 18px` `#FFFFFF` |
| **Mobile** | `Rechercher` (Accueil `66:397`) | `272 × 44px` (`padding: 10px 16px`) | `Inter` SemiBold `16px / 18px` `#FFFFFF` |
| **Desktop** | `Rechercher` (Accueil) | `216 × 48px` | `Golos Text` Regular `16px / 28px` `#FFFFFF` |
| **Desktop** | `Rechercher` (Résultats) | `248 × 48px` | `Golos Text` Regular `16px / 28px` `#FFFFFF` |
| **Desktop** | `Contacter`, `Publier`, `Modifier` (trajet), `Appliquer` | `288 × 48px` | `Golos Text` Regular `16px / 28px` `#FFFFFF` |
| **Desktop** | `Se connecter`, `S'Inscrire`, `Modifier` (informations) | `464 × 48px` | `Golos Text` Regular `16px / 28px` `#FFFFFF` |

---

## 3. Boutons icônes circulaires & lien Retour

| Composant | Node ID | Dimensions & forme | Apparence & rôle |
| :--- | :--- | :--- | :--- |
| **`Bouton Inversion Itinéraire`** | `82:720` | `44 × 44px` (`rounded: 50%`) | Cercle `#B08AE8`, doubles flèches verticales blanches (`↑↓`) pour permuter départ et arrivée |
| **`Bouton Inversion Horaires`** | `87:731` | `31 × 31px` (`rounded: 50%`) | Cercle `#B08AE8`, doubles flèches horizontales blanches (`⇄`) dans le composant `Horaire` |
| **`Entrer` / `Voir le trajet`** | `87:842` · `81:367` | `44 × 44px` (`rounded: 50%`) | Cercle `#B08AE8` avec chevron droit : chevron blanc sur Mobile, caractère `›` (`SUSE Mono Bold 28px`, `#090B10`) sur Desktop Résultats |
| **`Point d'intérêt`** | `150:1115` · `150:1235` | `44 × 44px` (`rounded: 50%`) | Cercle gris `#D9D9D9` avec lettre `L` noire (ouvre `Menu point d'intérêt`) |
| **Lien `< Retour`** | `112:1565` · `150:1266` | `73 × 28px` | Texte `< Retour` en `Golos Text` Regular `16px / 28px`, `#FFFFFF` |
