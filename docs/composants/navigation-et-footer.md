# Navigation & Footer

<span class="node-badge">Nav Bar (66:389)</span> <span class="node-badge">Menu Mobile (65:239)</span> <span class="node-badge">Navigation desktop (81:272)</span> <span class="node-badge">Footer (66:605)</span>

---

## 1. Nav Bar Mobile (`66:389`)

Barre supérieure présente sur l'ensemble des 12 écrans Mobile.

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `375 × 72px` (`top: 0`, `left: 0`) |
| **Fond** | `#090B10` (`--primary-color`) |
| **Logo (gauche)** | `41 × 41px`, position `left: 20px`, `top: 15px` (cliquable vers l'Accueil) |
| **Bouton Menu burger (droite)** | Zone droite (`inset: 33.59% 4.17% 28.13% 86.84%`, ~`33.7 × 27.6px`), 3 barres horizontales couleur `#8039E9` / `#7749F8` |

---

## 2. Menu Drawer Mobile (`65:239`)

Panneau plein écran ouvert au clic sur l'icône burger de la Nav Bar Mobile.

<figure class="mockup-single">
  <img src="assets/mockups/comp-menu-mobile.png" alt="Menu drawer Mobile Figma" style="max-width:260px;">
  <figcaption>Composants Mobile — Menu (node 65:239, 375 × 812px)</figcaption>
</figure>

| Élément | Position & style exacts |
| :--- | :--- |
| **Fond du drawer** | `#000000` (`375 × 822px`) |
| **Avatar utilisateur** | Cercle `43 × 43px` (`left: 66px`, `top: 16px`, gris clair) |
| **Lien `Connexion`** | `left: 134px`, centre vertical `38px` · `Golos Text` `16px / 28px`, `#FFFFFF` |
| **Bouton Fermer (`Close`)** | `44 × 44px` en haut à droite (`left: 307px`, `top: 15px`), croix `#FFFFFF` |
| **Séparateur** | Ligne horizontale `w: 317px` à `left: 53px`, `top: 74px` |
| **Liens verticaux** | Alignés à `left: 66px`, espacés de `50px` en hauteur (`top` des centres : `110px`, `160px`, `210px`, `260px`) · `Golos Text` `16px / 28px`, `#FFFFFF` |
| **Entrées du menu** | 1. `Profil` · 2. `Publier un trajet` · 3. `Mes annonces` · 4. `Contact` |

---

## 3. Navigation Desktop (`81:272`)

Barre horizontale de `1280 × 72px` commune aux 12 écrans Desktop.

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `1280 × 72px` (`top: 0`, `left: 0`) · conteneur interne `Nav Bar` `1192 × 72px` à `left: 44px` |
| **Fond** | `#090B10` (`--primary-color`) |
| **Logo** | `41 × 41px` à `left: 20px` dans le conteneur interne (`64px` depuis le bord gauche de la page), `top: 15px` |
| **Liens de navigation** | `Golos Text` Regular `16px / 28px`, alignés à `top: 26px` |
| **Positions X des 5 liens** | `Accueil et recherche` (`156px`) · `Publier un trajet` (`435px`) · `Mes annonces` (`686px`) · `Profil` (`885px`) · `Connexion` (`1034px`) |
| **Couleur lien actif** | `#DAC4FB` (`--accent-light`) |
| **Couleur liens inactifs** | `#FFFFFF` (`--blanc`) |

<div class="note-figma">
  <strong>Note factuelle sur l'état actif dans Figma :</strong> Sur les maquettes Desktop <code>Contact</code>, <code>Informations</code>, <code>Préférences</code> et <code>Modifier le trajet</code>, le lien actif affiché dans le composant instance reste sur <code>Accueil et recherche</code> en <code>#DAC4FB</code> ; sur <code>Inscription</code>, c'est <code>Connexion</code> qui est en <code>#DAC4FB</code>.
</div>

### Exemple de structure HTML / Bootstrap 5

```html
<header class="bb-navbar">
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container bb-container-desktop">
      <a class="navbar-brand" href="accueil.html">
        <img src="assets/logo/favicon_normal.svg" alt="BlaBlamU" width="41" height="41">
      </a>
      <button class="navbar-toggler border-0" type="button" data-bs-toggle="offcanvas" data-bs-target="#mobileMenu" aria-label="Ouvrir le menu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav flex-grow-1 justify-content-between ms-lg-5">
          <li class="nav-item"><a class="nav-link active" href="accueil.html">Accueil et recherche</a></li>
          <li class="nav-item"><a class="nav-link" href="publier.html">Publier un trajet</a></li>
          <li class="nav-item"><a class="nav-link" href="mes-annonces.html">Mes annonces</a></li>
          <li class="nav-item"><a class="nav-link" href="profil.html">Profil</a></li>
          <li class="nav-item"><a class="nav-link" href="connexion.html">Connexion</a></li>
        </ul>
      </div>
    </div>
  </nav>
</header>
```

---

## 4. Footer Mobile (`66:605`) & Desktop (`81:285`)

| Propriété | Mobile (`66:605`) | Desktop (`81:285`) |
| :--- | :--- | :--- |
| **Dimensions** | `375 × 85px` | `1280 × 72px` (`top: 648px`, conteneur interne `1192 × 72px` à `left: 44px`) |
| **Fond** | `#000000` (`--primary-dark`) | `#000000` (`--primary-dark`) |
| **Logo** | `41 × 41px`, `left: 12px`, `top: 15px` | `41 × 41px`, `left: 12px` (dans conteneur `1192px`), `top: 15px` |
| **Ligne 1 (liens)** | `À propos - Contact - Mentions Légales` · `Golos Text` `16px / 28px` · `#FFFFFF` (`left: 62px`, centre `29px`) | Idem (`left: 62px`, centre `29px`) |
| **Ligne 2 (copyright)** | `© 2026 Tous droits réservés.` · `Golos Text` `14px / 28px` · `#BDBDBD` (`left: 62px`, centre `57px`) | Idem (`left: 62px`, centre `57px`) |
