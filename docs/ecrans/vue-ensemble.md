# Vue d'ensemble des écrans & parcours

Les maquettes Figma couvrent **12 écrans** déclinés intégralement en **Mobile (`375px`)** et en **Desktop (`1280 × 720px`)**.

---

## 1. Tableau récapitulatif des 12 écrans

| # | Écran | Mobile (Node ID · Taille) | Desktop (Node ID · Taille) | Lien navbar actif (Desktop) | Fiche |
| :-: | :--- | :--- | :--- | :--- | :--- |
| 1 | **Accueil et Recherche** | `11:246` · `375×825` | `120:546` · `1280×720` | `Accueil et recherche` | [Accueil et Recherche](ecrans/accueil-et-recherche.md) |
| 2 | **Résultats** | `64:144` · `375×812` | `120:547` · `1280×720` | `Accueil et recherche` | [Résultats](ecrans/resultats.md) |
| 3 | **Fiche trajet** | `64:164` · `375×1128` | `120:548` · `1280×720` | `Accueil et recherche` | [Fiche trajet](ecrans/fiche-trajet.md) |
| 4 | **Contact** | `96:1144` · `375×868` | `103:978` · `1280×720` | `Accueil et recherche` *(instance)* | [Contact](ecrans/contact.md) |
| 5 | **Inscription** | `64:184` · `375×812` | `120:549` · `1280×720` | `Connexion` | [Inscription & Connexion](ecrans/authentification.md) |
| 6 | **Connexion** | `64:204` · `375×812` | `120:550` · `1280×720` | `Connexion` | [Inscription & Connexion](ecrans/authentification.md) |
| 7 | **Publier un trajet** | `64:224` · `375×1007` | `120:551` · `1280×720` | `Publier un trajet` | [Publier & Modifier un trajet](ecrans/publier-et-modifier.md) |
| 8 | **Modifier le trajet** | `96:1249` · `375×1007` | `103:1047` · `1280×720` | `Accueil et recherche` *(instance)* | [Publier & Modifier un trajet](ecrans/publier-et-modifier.md) |
| 9 | **Mes annonces** | `64:244` · `375×812` | `120:552` · `1280×720` | `Mes annonces` | [Mes annonces](ecrans/mes-annonces.md) |
| 10 | **Profil** | `66:375` · `375×812` | `120:553` · `1280×720` | `Profil` | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |
| 11 | **Informations** | `96:1003` · `375×812` | `103:1001` · `1280×720` | `Accueil et recherche` *(instance)* | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |
| 12 | **Préférences** | `96:1071` · `375×812` | `103:1024` · `1280×720` | `Accueil et recherche` *(instance)* | [Profil, Informations & Préférences](ecrans/profil-infos-preferences.md) |

---

## 2. Parcours de navigation entre écrans

### Parcours Passager (Recherche & Contact)

1. **Accueil et Recherche** → clic sur `Rechercher` ou sur une carte `Exemple de trajet` (`IUT`, `Resto Universitaire`, `Gare`, `Centre Ville`) → **Résultats**.
2. **Résultats** → clic sur une carte `Trajet` / bouton `›` → **Fiche trajet**.
3. **Fiche trajet** → clic sur la `Carte contact` du conducteur → **Contact** (avec lien `< Retour` vers la Fiche trajet).

### Parcours Conducteur (Publication & Gestion)

1. **Navigation** (`Menu` Mobile ou `Navigation desktop`) → **Publier un trajet** → bouton `Publier`.
2. **Mes annonces** → sur Mobile, menu contextuel `Menu 3 points` (`Modifier`, `Complet`, `Masquer`, `Supprimer`) ; sur Desktop, clic sur une carte annonce → **Modifier le trajet** → bouton `Modifier`.

### Parcours Compte & Profil

1. **Navigation** → **Connexion** ↔ bascule **Inscription** (`S'inscrire` / `Se connecter`).
2. **Navigation** → **Profil** :
   - Lien `Voir mes annonces` → **Mes annonces**
   - Carte `Informations` → **Informations** (`< Retour` vers Profil)
   - Carte `Préférences` → **Préférences** (`< Retour` vers Profil)
