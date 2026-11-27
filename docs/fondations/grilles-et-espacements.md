# Grilles & espacements

Les maquettes Figma utilisent deux cibles de mise en page : **Mobile (`375px`)** et **Desktop (`1280 × 720px`)**. Cette page regroupe toutes les dimensions de canvas, grilles de colonnes, rayons d'arrondi (`border-radius`) et épaisseurs de bordures mesurés dans les frames.

---

## 1. Formats de canvas & marges

### Mobile (`375px`)

| Écran | Node ID | Dimensions (L × H) | Marge latérale principale | Largeur utile |
| :--- | :--- | :--- | :--- | :--- |
| Accueil et Recherche | `11:246` | `375 × 825px` | `11px` – `12px` | `351px` – `352px` |
| Résultats | `64:144` | `375 × 812px` | `12px` | `351px` – `352px` |
| Fiche trajet | `64:164` | `375 × 1128px` | `12px` (carte map à `35px`) | `351px` (`306px` pour la map) |
| Contact | `96:1144` | `375 × 868px` | `12px` / `22px` | `351px` |
| Inscription | `64:184` | `375 × 812px` | `38px` | `248px` (inputs), `172px` (import) |
| Connexion | `64:204` | `375 × 812px` | `38px` | `248px` (inputs) |
| Publier un trajet | `64:224` | `375 × 1007px` | `11px` – `12px` (`20px`–`22px` labels) | `351px` – `352px` |
| Modifier un trajet | `96:1249` | `375 × 1007px` | `11px` – `12px` (`20px`–`22px` labels) | `351px` – `352px` |
| Mes annonces | `64:244` | `375 × 812px` | `12px` | Grille `2` col. de `164px` (gouttière `23px`) |
| Profil | `66:375` | `375 × 812px` | `15px` | `345px` |
| Informations | `96:1003` | `375 × 812px` | `27px` | `248px` (inputs), `172px` (import) |
| Préférences | `96:1071` | `375 × 812px` | `12px` (`22px` labels) | `351px` |

### Structure verticale Mobile

- **Header (`Nav Bar`)** : hauteur fixe `72px` (`top: 0`), pleine largeur `375px`.
- **Titre de page (`H1`)** : centré horizontalement à `top: 102px` (centre vertical).
- **Lien `< Retour`** (quand présent : Fiche trajet, Contact, Informations, Préférences) : `left: 28px`, `top: 146px` (centre vertical).
- **Footer** : hauteur `85px`, pleine largeur `375px`, positionné en bas de frame (`top: 727px` sur frames `812px`, `743px` sur Accueil, `783px` sur Contact, `922px` sur Publier/Modifier, `1043px` sur Fiche trajet).

---

### Desktop (`1280 × 720px`)

Toutes les pages Desktop partagent le gabarit `Structure desktop` (`1280 × 720px`) :

| Zone | Position & dimensions exactes |
| :--- | :--- |
| **Navigation desktop** | `top: 0`, `left: 0`, `w: 1280px`, `h: 72px` (conteneur interne `Nav Bar` à `left: 44px`, `w: 1192px`) |
| **Conteneur principal** | `top: 108px`, `left: 64px` *(sauf Fiche trajet à `left: 84px` et Connexion à `left: 39px`)*, `w: 1152px`, `h: 504px` |
| **Pied de page** | `top: 648px`, `left: 0`, `w: 1280px`, `h: 72px` (conteneur interne `Footer` à `left: 44px`, `w: 1192px`) |

#### Grilles internes par écran Desktop (dans le conteneur `1152px`)

| Écran Desktop | Organisation des colonnes |
| :--- | :--- |
| **Accueil et recherche** | Barre recherche pleine largeur `1152 × 126px` · Grille `4` cartes `264 × 200px` avec gouttière `32px` (`x = 0, 296, 592, 888`) |
| **Résultats** | `2` colonnes asymétriques : panneau recherche `288 × 378px` + gouttière `40px` + liste `824px` (`4` cartes de `80px`, espacement vertical `4px`, pagination à `top: 464px`) |
| **Fiche trajet** | `2` colonnes : gauche `600px` (carte map `600 × 300px` + carte conducteur `351 × 105px` centrée en dessous) + gouttière `40px` + droite `512px` |
| **Contact** | `2` colonnes : profil gauche `352 × 340px` + gouttière `40px` + infos droite `760 × 350px` + CTA `288 × 48px` aligné à droite (`left: 864px`) |
| **Inscription / Informations** | Formulaire `2` colonnes centré (`w total: 812px`, `left: 170px`) : `2` inputs `390 × 48px` avec gouttière `32px` + champ fichier pleine largeur `812 × 48px` + CTA `464 × 48px` |
| **Connexion** | Panneau noir centré `528 × 418px` (`left: 312px`), champs et CTA `464 × 48px` (`padding` horizontal `32px`) |
| **Publier / Modifier** | `2` panneaux côte à côte : gauche `Itinéraire` `552 × 410px` + gouttière `32px` + droite `Préférences` `568 × 350px` + CTA `288 × 48px` aligné à droite (`top: 442px`) |
| **Mes annonces** | Grille `4 × 2` cartes `164 × 167px` centrée (`left: 276px`, gouttière horizontale `24px`, verticale `22px`–`24px`) + pagination centrée en dessous |
| **Profil** | Colonne centrée `600px` (`left: 340px`, `top: 94px`) |
| **Préférences** | Panneau noir centré `812 × 326px` (`left: 170px`) + CTA `288 × 48px` centré en dessous |

---

## 2. Rayons d'arrondi (`border-radius`)

| Rayon | Composants concernés |
| :--- | :--- |
| `2px` | Checkboxes `Musique` / `Animaux` (`16 × 16px`) |
| `4px` | Items de `Simple Pagination`, sélecteurs Jours (`L M M J V`) et Places (`1..5`), lignes `Informations` & `Préférences` sur Profil Desktop |
| `5px` | Champs internes `7h` / `7h30` de `Horaire`, lignes `Informations` & `Préférences` sur Profil Mobile |
| `6px` | Tous les boutons CTA (`Fill`/`Outline`/`Btn Contact`), inputs standard (`h: 48px` Desktop, `py: 9px` Mobile), zones `Description` |
| `8px` | Panneaux noirs Desktop (`Recherche`, `Connexion`, `Itinéraire`, `Préférences`, `Profil à contacter`, `Informations de contact`, `Informations du trajet`, `Horaires du trajet`), cartes `Trajet` Résultats Desktop, carte map Desktop (`600×300`), carte résumé Profil Desktop |
| `10px` | Cartes `Exemple trajet` et `Annonces` (`164×167` / `264×200`), carte résumé Profil Mobile |
| `14px` | Blocs et cartes Mobile : `Itinéraire`, `Carte heure`, `Trajet` (Résultats), `Carte contact`, `Horaire` |
| `22px` | Cadre carte map Mobile (`306×276`), bouton circulaire `Voir le trajet` Desktop (`44×44` = `50%`) |
| `50%` (`full`) | Avatars circulaires, boutons ronds `Inversion Itinéraire` (`44×44`), `Inversion Horaires` (`31×31`), `Entrer` (`44×44`), `Point d'intérêt` (`44×44`) |

---

## 3. Bordures mesurées

| Bordure | Éléments concernés |
| :--- | :--- |
| `1px solid #DEE2E6` | Inputs texte Mobile, zones `Description` (Mobile & Desktop) |
| `1px solid #E9ECEF` | Items `Simple Pagination`, sélecteurs Jours & Places |
| `1px solid #7749F8` | Item actif de `Simple Pagination`, bouton `Outline Primary Disabled` |
| `1px solid #ABB5BE` | Checkbox non cochée |
| `1px solid #3478F6` | Cartes de la page `Profil` (Mobile & Desktop) |
| `2px solid #3478F6` | `Itinéraire` Mobile, `Carte heure` Mobile, carte `Trajet` (Mobile & Desktop), `Carte Exemple trajet`, `Carte Annonces`, `Carte contact`, cadre carte map (Mobile & Desktop) |
