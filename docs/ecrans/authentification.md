# Inscription & Connexion

<span class="node-badge">Inscription : Mobile 64:184 · Desktop 120:549</span> <span class="node-badge">Connexion : Mobile 64:204 · Desktop 120:550</span>

Écrans d'authentification et de création de compte étudiant.

---

## 1. Inscription

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-inscription.png" alt="Mobile Inscription">
    <figcaption>Mobile — 64:184 (375 × 812px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-inscription.png" alt="Desktop Inscription">
    <figcaption>Desktop — 120:549 (1280 × 720px)</figcaption>
  </figure>
</div>

### Structure Mobile (`64:184` · `375 × 812px`)

| Élément | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Titre `Inscription`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Champs (`left: 38px`, `w: 248px`)** | 4 inputs empilés + 1 import fichier (`w: 172px`) | Labels (`SUSE Mono` Bold `24px`, `#3478F6`) · Inputs (`#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, `Inter 16px` `#ADB5BD`) |
| ↳ `Votre prénom :` | Label `top: 166px` · Input `top: 187px` (`Prénom`) | — |
| ↳ `Votre nom :` | Label `top: 246px` · Input `top: 266px` (`Nom`) | — |
| ↳ `Votre E-mail :` | Label `top: 326px` · Input `top: 347px` (`exemple@etu.univ-amu.com`) | — |
| ↳ `Votre mot de passe :` | Label `top: 406px` · Input `top: 426px` (`Mot de passe`) | — |
| ↳ `Image de Profil :` | Label `top: 486px` · Bouton `top: 506px`, `w: 172px` (`Importer un fichier`) | — |
| **Bouton `S'inscrire`** | `left: 133px`, `top: 574px`, `w: 110px`, `h: 44px` | `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px` `#FFFFFF` |
| **Texte bascule** | `left: 82px`, `top: 661px` | `Vous avez déjà un compte ?` (`Golos Text 16px`, `#FFFFFF`) |
| **Bouton `Se connecter`** | Centré, `top: 695px`, `w: 110px`, `h: 44px` | `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px` `#FFFFFF` |
| **Footer** | `top: 727px`, `h: 85px` | Fond `#000000` |

### Structure Desktop (`120:549` · `1280 × 720px`)

| Élément | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Connexion` (`#DAC4FB`) |
| **Titre `COMMENCER L'INSCRIPTION`** | `left: 300px`, `top: 0` (dans conteneur `1152px`) | `SUSE Mono` ExtraBold `40px`, `#FFFFFF` |
| **Grille formulaire (`w total: 812px`)** | `left: 170px` | Labels `Golos Text 16px` `#3478F6`, champs `h: 48px` `#FFFFFF` `rounded: 6px`, texte `#4E495B` |
| ↳ Ligne 1 (`top: 100px`) | `Votre prénom :` (`left: 170px`, `w: 390px`) + `Votre nom :` (`left: 592px`, `w: 390px`) | Gouttière `32px` |
| ↳ Ligne 2 (`top: 200px`) | `Votre E-mail :` (`exemple@email.com`, `w: 390px`) + `Votre mot de passe :` (`w: 390px`) | Gouttière `32px` |
| ↳ Ligne 3 (`top: 300px`) | `Image de Profil :` (`Importer un fichier`, `left: 170px`, `w: 812px`, `h: 48px`) | Pleine largeur de la grille |
| **Bouton `S'Inscrire`** | `left: 344px`, `top: 378px`, `w: 464px`, `h: 48px` | `#B08AE8`, `rounded: 6px`, `Golos Text 16px` `#FFFFFF` |
| **Bascule compte (`top: 450px`)** | `Vous avez déjà un compte ?` (`left: 407.5px`, `#FFFFFF`) + lien `Se connecter` (`left: 642.5px`, `#B08AE8`) | `Golos Text 16px` |

---

## 2. Connexion

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-connexion.png" alt="Mobile Connexion">
    <figcaption>Mobile — 64:204 (375 × 812px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-connexion.png" alt="Desktop Connexion">
    <figcaption>Desktop — 120:550 (1280 × 720px)</figcaption>
  </figure>
</div>

### Structure Mobile (`64:204` · `375 × 812px`)

| Élément | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Titre `Connexion`** | `top: 102px` (centre), `w: 351px` | `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **`Votre E-mail :`** | Label `top: 196px` · Input `left: 38px`, `top: 217px`, `w: 248px` | Placeholder `exemple@etu.univ-amu.com` (`#ADB5BD`) |
| **`Votre mot de passe :`** | Label `top: 276px` · Input `left: 38px`, `top: 296px`, `w: 248px` | Placeholder `Mot de passe` (`#ADB5BD`) |
| **Lien `Mot de passe oublié`** | `left: 38px`, `top: 339px` | `Golos Text 16px / 28px`, `#FFFFFF` |
| **Bouton `Se connecter`** | Centré, `top: 381px`, `w: 110px`, `h: 44px` | `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px` `#FFFFFF` |
| **Texte bascule** | `left: 78px`, `top: 589px` | `Vous n'avez pas de compte ?` (`Golos Text 16px`, `#FFFFFF`) |
| **Bouton `S'inscrire`** | `left: 135px`, `top: 627px`, `w: 110px`, `h: 44px` | `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px` `#FFFFFF` |
| **Footer** | `top: 727px`, `h: 85px` | Fond `#000000` |

### Structure Desktop (`120:550` · `1280 × 720px`)

Conteneur principal à `left: 39px`, `top: 108px`, `w: 1152px`, `h: 504px`.

| Élément | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif : `Connexion` (`#DAC4FB`) |
| **Titre `SE CONNECTER`** | `left: 432px`, `top: 0` | `SUSE Mono` ExtraBold `40px`, `#FFFFFF` |
| **Panneau `Connexion au compte`** | `left: 312px`, `top: 80px`, `w: 528px`, `h: 418px` | Fond `#000000`, `rounded: 8px`, padding interne `32px` |
| ↳ `Votre E-mail :` | Label `top: 28px` (`#3478F6`) · Input `top: 58px`, `w: 464px`, `h: 48px` | Placeholder `exemple@email.com` (`#4E495B`) |
| ↳ `Votre mot de passe :` | Label `top: 134px` (`#3478F6`) · Input `top: 164px`, `w: 464px`, `h: 48px` | Placeholder `Mot de passe` (`#4E495B`) |
| ↳ `Mot de passe oublié` | Aligné à droite (`right: 32px`, `top: 214px`) | `Golos Text 16px / 28px`, `#B08AE8` |
| ↳ Bouton `Se connecter` | `left: 32px`, `top: 250px`, `w: 464px`, `h: 48px` | Fond `#B08AE8`, `rounded: 6px`, `Golos Text 16px` `#FFFFFF` |
| ↳ Bascule compte (`top: 334px`) | `Vous n'avez pas de compte ?` (`left: 32px`, `#FFFFFF`) + lien `S'inscrire` (`left: 330px`, `#B08AE8`) | `Golos Text 16px` |
