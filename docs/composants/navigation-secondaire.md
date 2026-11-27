# Pagination & menus contextuels

<span class="node-badge">Simple Pagination (86:1067)</span> <span class="node-badge">Menu 3 points (96:901)</span> <span class="node-badge">Menu point d'intérêt (150:1137 · 150:1247)</span>

---

## 1. `Simple Pagination` (`86:1067`)

Utilisée en bas des écrans **Résultats** et **Mes annonces** (Mobile & Desktop).

<figure class="mockup-single">
  <img src="assets/mockups/comp-pagination.png" alt="Composant Simple Pagination Figma" style="max-width:300px;">
  <figcaption>Composants Mobile — Simple Pagination (node 86:1067, 284 × 40px)</figcaption>
</figure>

| Propriété | Valeur exacte |
| :--- | :--- |
| **Conteneur** | `display: flex`, `gap: 4px`, largeur totale `284px`, hauteur `40px` |
| **Padding & rayon d'un item** | `padding: 12px 16px`, `border-radius: 4px` |
| **Item Normal** | Fond `#FFFFFF`, `border: 1px solid #E9ECEF`, texte `#6C757D` (`Inter` Regular `16px / 16px`) |
| **Item Actif (`1`)** | Fond `#8039E9` (`--accent-dark`), `border: 1px solid #7749F8`, texte `#FFFFFF` |
| **Item Disabled (`Prev`)** | Fond `#FFFFFF`, `border: 1px solid #E9ECEF`, icône / texte `#ADB5BD` |
| **Icônes chevrons** | `chevron-left` et `chevron-right`, `16 × 16px` |

---

## 2. `Menu 3 points` (`96:901`)

Menu contextuel affiché au clic sur les 3 points verticaux d'une `Carte Annonces` dans l'écran **Mes annonces** (Mobile).

<figure class="mockup-single">
  <img src="assets/mockups/comp-menu-3-points.png" alt="Composant Menu 3 points Figma" style="max-width:140px;">
  <figcaption>Composants Mobile — Menu 3 points (node 96:901, 108 × 123px)</figcaption>
</figure>

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `108 × 123px` |
| **Fond** | `#FFFFFF` |
| **Bouton fermer (`Croix Fermer`)** | `17 × 17px` en haut à droite (`left: 87px`, `top: 3px`) |
| **Actions (de haut en bas)** | `Modifier` (`top: 20px`, `#000000`) · `Complet` (`top: 47px`, `#000000`) · `Masquer` (`#000000`) · `Supprimer` (`#FF0000`) |
| **Typographie** | `Inter` Regular `14px / 14px` (`left: 7px`) |

---

## 3. `Menu point d'intérêt` (`150:1137` / `150:1247`)

Menu déroulant rapide associé au bouton circulaire `Point d'intérêt` (`L`) des champs Départ / Arrivée pour choisir directement un point d'intérêt fréquent.

<figure class="mockup-single">
  <img src="assets/mockups/comp-menu-poi.png" alt="Composant Menu point d'intérêt Figma" style="max-width:140px;">
  <figcaption>Composants — Menu point d'intérêt (Mobile 150:1137 : 108 × 129px · Desktop 150:1247 : 112 × 129px)</figcaption>
</figure>

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `108 × 129px` (Mobile) · `112 × 129px` (Desktop) |
| **Fond** | `#FFFFFF` |
| **Typographie** | `Golos Text` Regular `16px / 28px`, `#000000`, `left: 7px` |
| **Liste des options** | 1. `IUT` (`top: 10px`) · 2. `Gare` (`top: 38px`) · 3. `Crous` (`top: 66px`) · 4. `Centre ville` (`top: 94px`) |
