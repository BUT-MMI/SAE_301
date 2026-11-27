# Cartes & listes

<span class="node-badge">Carte Exemple trajet (65:426)</span> <span class="node-badge">Carte Annonces (96:854)</span> <span class="node-badge">Trajet (87:847)</span> <span class="node-badge">Carte contact (86:1083)</span>

---

## 1. `Carte Exemple trajet` (`65:426`) & `Carte Annonces` (`96:854`)

Carte carrée/verticale utilisée sur **Accueil et Recherche** (`IUT`, `Resto Universitaire`, `Gare`, `Centre Ville` sur Mobile ; `Description trajet` sur Desktop) et sur **Mes annonces**.

| Propriété | Mobile (`65:426` / `96:854`) | Desktop (`81:324` Accueil / `88:1026` Annonces) |
| :--- | :--- | :--- |
| **Dimensions** | `164 × 167px` | `264 × 200px` (Accueil) · `164 × 167px` (Mes annonces) |
| **Fond & bordure** | `#FFFFFF` · `border: 2px solid #3478F6` | `#FFFFFF` · `border: 2px solid #3478F6` |
| **Rayon (`border-radius`)** | `10px` | `10px` |
| **Zone haute (visuel)** | `76.65%` de la hauteur (placeholder croix `X` diagonale) | `76.65%` de la hauteur (placeholder croix `X` diagonale) |
| **Bandeau bas (titre)** | `23.35%` de la hauteur, `border-top: 2px solid #3478F6`, texte `Golos Text 16px / 28px`, `#68717A` | Idem |
| **Spécificité `Carte Annonces`** | Bouton `3 points` verticaux en haut à droite (`inset: 2.4% 4.27% 87.43% 92.68%`) ouvrant le `Menu 3 points` | Réutilise `Carte Exemple trajet` (`164 × 167px`) sans les 3 points |

---

## 2. Carte `Trajet` — Liste des résultats

Affiche un trajet proposé dans l'écran **Résultats** avec l'avatar du conducteur, son prénom, l'horaire, la durée et les villes.

### Version Mobile (`87:847`)

| Élément | Valeur exacte |
| :--- | :--- |
| **Dimensions & conteneur** | `351 × 74px`, `#FFFFFF`, `border: 2px solid #3478F6`, `border-radius: 14px` |
| **Avatar (gauche)** | Cercle gris `#D9D9D9` (~`45 × 45px`, `inset: 18.92% 84.33% 20.27% 2.85%`) |
| **Séparateur vertical** | Trait vertical fin à `left: 18.23%` (`inset: 10.81% 81.48% 9.46% 18.23%`) |
| **Nom conducteur** | `Golos Text` `16px / 28px`, `#68717A` (ex. `Nataël`, `Conducteur`) |
| **Horaires & durée** | `7h — 30 min — 7h30` en `Golos Text` `15px`, `#68717A`, reliés par deux traits horizontaux |
| **Villes** | `Miramas` / `Arles` en `Golos Text` `13px`, `#68717A` sous les heures |
| **Action droite** | Bouton `Entrer` `44 × 44px` (`#B08AE8`, chevron blanc) |

### Version Desktop (`81:359`)

| Élément | Valeur exacte |
| :--- | :--- |
| **Dimensions & conteneur** | `824 × 80px`, `#FFFFFF`, `border: 2px solid #3478F6`, `border-radius: 8px` |
| **Avatar** | `42 × 42px` (`left: 16px`, `top: 17px`, contour cercle fin) |
| **Nom conducteur** | `left: 76px`, `top: 23px`, `Golos Text` `16px / 28px`, `#090B10` |
| **Départ** | `left: 288px` : heure (`7h`, `#090B10`, `top: 8px`) + ville (`Miramas`, `#4E495B`, `top: 38px`) |
| **Durée** | `left: 423px`, `top: 23px` : `→  30 min  →` (`#4E495B`) |
| **Arrivée** | `left: 600px` : heure (`7h30`, `#090B10`, `top: 8px`) + ville (`Arles`, `#4E495B`, `top: 38px`) |
| **Actions droite** | Icône `Point d'intérêt` `44 × 44px` (`left: 689px`, `top: 16px`) + bouton rond `Voir le trajet` `44 × 44px` (`left: 752px`, `top: 16px`, `#B08AE8`, `›` `SUSE Mono Bold 28px` `#090B10`) |

---

## 3. `Carte contact` (`86:1083`)

Carte cliquable affichant le conducteur en bas de **Fiche trajet** (Mobile & Desktop) pour accéder à la page **Contact**.

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `351 × 105px` (Mobile & Desktop) · composant source `352 × 105px` |
| **Fond & bordure** | `#FFFFFF` · `border: 2px solid #3478F6` · `border-radius: 14px` |
| **Avatar** | Cercle (`~70 × 70px`, `inset: 17.14% 76.14% 16.19% 3.98%`) |
| **Textes** | Ligne 1 : `Théo Thomas` / `Natael` · Ligne 2 : `Étudiant MMI 2` · `Inter` Regular `16px / 28px`, `#000000` (`left: 28.13%`) |
| **Bouton droite** | `Entrer` `44 × 44px` (`#B08AE8`, chevron blanc, `inset: 29.52% 8.24% 28.57% 79.26%`) |

---

## 4. Cartes de la page `Profil`

| Élément | Mobile (`66:375`) | Desktop (`120:553`) |
| :--- | :--- | :--- |
| **Carte résumé utilisateur** | `345 × 87px`, `#FFFFFF`, `border: 1px solid #3478F6`, `rounded: 10px` | `600 × 112px`, `#FFFFFF`, `border: 1px solid #3478F6`, `rounded: 8px` |
| **Avatar dans résumé** | `50 × 50px` (`left: 42px`, `top: 134px` dans le frame) | `56 × 56px` (`left: 28px`, `top: 28px` dans la carte) |
| **Textes du résumé** | `Théo Thomas` + `Voir mes annonces` (`Golos Text 16px / 28px`, `#4E495B`, `left: 118px`) | `Prénom Nom` + `voir mes annonces` (`Golos Text 16px / 28px`, `#4E495B`, `left: 112px`) |
| **Lignes `Informations` & `Préférences`** | `345 × 48px`, `#FFFFFF`, `border: 1px solid #3478F6`, `rounded: 5px`, icône `30 × 30px`, texte `#4E495B` (`left: 83px`) | `600 × 56px`, `#FFFFFF`, `border: 1px solid #3478F6`, `rounded: 4px`, icône `30 × 30px`, texte `#4E495B` (`left: 80px`) |
