# BlaBlamU — Documentation Design & UI

Documentation technique de référence pour reproduire à la main l'interface **BlaBlamU** (projet SAE 301/303 — covoiturage étudiant amU, *« Sans frais ni pression »*), fidèlement aux maquettes du fichier Figma **`BlaBlamU (copie)`**.

> **Source Figma (lecture seule) :** [BlaBlamU (copie)](https://www.figma.com/design/jiTd8OHwMBWyoyn4Wwmjwp/BlaBlamU--copie-?node-id=0-1) — FileKey `jiTd8OHwMBWyoyn4Wwmjwp` · 3 pages : `Charte graphique` (`0:1`), `Mobile` (`11:2`), `PC` (`11:3`).

---

## Synthèse rapide de l'identité visuelle

| Élément | Valeur de référence (Figma) |
| :--- | :--- |
| **Formats maquettes** | Mobile : `375px` de large (`812px` à `1128px` de haut) · Desktop (PC) : `1280 × 720px` |
| **Fond principal** | `#090B10` (`--primary-color`) |
| **Panneaux & Footer** | `#000000` (`--primary-dark`) |
| **Titres de sections & bordures** | `#3478F6` (`--secondary-color`) |
| **Boutons CTA & actions** | `#B08AE8` (`--accent-color`) · État actif / hover : `#8039E9` (`--accent-dark`) · Lien actif : `#DAC4FB` (`--accent-light`) |
| **Surface des cartes & champs** | `#FFFFFF` (`--blanc`) · Texte secondaire / champs : `#4E495B` (`--primary-light` / `--gris`) et `#68717A` |
| **Typographie** | Titres : `SUSE Mono` (Bold `700`, ExtraBold `800`) · Corps & UI : `Golos Text` (`400`) & `Inter` (`400` / `600`) |
| **Logo SVG (`amU`)** | `Monument Grotesk` · Fond `#8039E9` (`logo_normal.svg`, `favicon_normal.svg`, `logo_tag_normal.svg`) |

---

## Comment utiliser cette documentation pour coder l'interface

1. **Importer les polices et tokens** : démarrez par [Tokens CSS & Bootstrap](implementation/tokens-css-et-bootstrap.md) pour copier le bloc Google Fonts, les variables `:root` et les équivalences Bootstrap 5.
2. **Valider les fondations** : consultez [Couleurs](fondations/couleurs.md), [Typographie](fondations/typographie.md), [Grilles & espacements](fondations/grilles-et-espacements.md) et [Logos & assets](fondations/logos-et-assets.md).
3. **Construire les briques réutilisables** : assemblez la [Navigation & Footer](composants/navigation-et-footer.md), les [Boutons & actions](composants/boutons-et-actions.md), les [Formulaires & champs](composants/formulaires-et-champs.md), les [Cartes & listes](composants/cartes-et-listes.md) et la [Pagination & menus contextuels](composants/navigation-secondaire.md).
4. **Assembler les 12 écrans** : suivez chaque fiche écran (captures Mobile & Desktop zoomables au clic, mesures au pixel près et variantes responsive).

---

## Inventaire des 12 écrans

| # | Écran | Mobile (`375px`) | Desktop (`1280×720`) | Fiche détaillée |
| :-: | :--- | :--- | :--- | :--- |
| 1 | **Accueil et Recherche** | `11:246` (`375×825`) | `120:546` | [Accueil et Recherche](ecrans/accueil-et-recherche.md) |
| 2 | **Résultats** | `64:144` (`375×812`) | `120:547` | [Résultats](ecrans/resultats.md) |
| 3 | **Fiche trajet** | `64:164` (`375×1128`) | `120:548` | [Fiche trajet](ecrans/fiche-trajet.md) |
| 4 | **Contact** | `96:1144` (`375×868`) | `103:978` | [Contact](ecrans/contact.md) |
| 5 | **Inscription** | `64:184` (`375×812`) | `120:549` | [Inscription & Connexion](ecrans/authentification.md) |
| 6 | **Connexion** | `64:204` (`375×812`) | `120:550` | [Inscription & Connexion](ecrans/authentification.md) |
| 7 | **Publier un trajet** | `64:224` (`375×1007`) | `120:551` | [Publier & Modifier un trajet](ecrans/publier-et-modifier.md) |
| 8 | **Modifier le trajet** | `96:1249` (`375×1007`) | `103:1047` | [Publier & Modifier un trajet](ecrans/publier-et-modifier.md) |
| 9 | **Mes annonces** | `64:244` (`375×812`) | `120:552` | [Mes annonces](ecrans/mes-annonces.md) |
| 10 | **Profil** | `66:375` (`375×812`) | `120:553` | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |
| 11 | **Informations** | `96:1003` (`375×812`) | `103:1001` | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |
| 12 | **Préférences** | `96:1071` (`375×812`) | `103:1024` | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |
