# Formulaires & champs

<span class="node-badge">Itinéraire (87:792)</span> <span class="node-badge">Carte heure (86:1035)</span> <span class="node-badge">Horaire (87:972)</span> <span class="node-badge">Checkboxes (87:761 · 87:763)</span>

---

## 1. Champs texte standard & Import fichier

### Input texte standard

| Propriété | Mobile | Desktop |
| :--- | :--- | :--- |
| **Fond** | `#FFFFFF` | `#FFFFFF` |
| **Bordure** | `1px solid #DEE2E6` | Aucune bordure sur les inputs simples (sur fond `#000000` ou `#090B10`) |
| **Rayon (`border-radius`)** | `6px` | `6px` |
| **Dimensions** | `w: 248px` (`padding: 9px 16px`, hauteur ~`40px`) | `h: 48px`, `w: 248px` (Résultats), `300px` (Accueil), `390px` (Inscription/Infos), `464px` (Connexion), `504px` (Publier/Modifier) |
| **Typographie placeholder** | `Inter` Regular `16px / 20px`, `#ADB5BD` | `Golos Text` Regular `16px / 28px`, `#4E495B` |
| **Label associé** | `SUSE Mono` Bold `24px`, `#3478F6` (au-dessus) | `Golos Text` Regular `16px / 28px`, `#3478F6` (au-dessus) |

### Bouton d'import fichier (`Image de Profil`)

- **Mobile** : largeur `172px`, même style visuel qu'un input (`#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, `padding: 9px 16px`), libellé `Importer un fichier` (`#ADB5BD`).
- **Desktop** : largeur `812px` × hauteur `48px`, `#FFFFFF`, `rounded: 6px`, libellé `Importer un fichier` (`Golos Text 16px / 28px`, `#4E495B`).

### Zone de texte (`Textarea` / `Description`)

- **Fond** : `#FFFFFF` · **Bordure** : `1px solid #DEE2E6` · **Rayon** : `6px` · **Padding** : `16px`
- **Tailles mesurées** :
  - Mobile : `351 × 114px` (Contact, Publier, Modifier, Préférences) · `351 × 143px` (Fiche trajet)
  - Desktop : `512 × 66px` (Fiche trajet) · `520 × 82px` (Publier, Modifier) · `712 × 166px` (Contact) · `764 × 142px` (Préférences)

---

## 2. Bloc `Itinéraire` Mobile (`87:792`)

Utilisé sur **Accueil**, **Résultats**, **Publier un trajet** et **Modifier un trajet** en version Mobile.

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `352 × 105px` |
| **Fond & bordure** | `#FFFFFF` · `border: 2px solid #3478F6` · `border-radius: 14px` |
| **Ligne 1** | `Point de départ : Miramas` (`Golos Text 16px / 28px`, `#68717A`) + bouton POI `44 × 44px` |
| **Séparateur** | Trait horizontal fin gris entre départ et arrivée (à ~`52.4%` de la hauteur, `left: 9.66%`, `right: 21.02%`) |
| **Ligne 2** | `Point d'arrivée : Arles` (`Golos Text 16px / 28px`, `#68717A`) + bouton POI `44 × 44px` |
| **Bouton Inversion** | `44 × 44px` cercle `#B08AE8` positionné à droite centré verticalement (`inset: 28.57% 4.55% 29.52% 82.95%`) |

Sur **Desktop**, les champs `Point de départ`, `Point d'arrivée` et `Date et heure` sont séparés en inputs individuels (`h: 48px`, `rounded: 6px`) à l'intérieur d'un panneau noir `#000000` (`rounded: 8px`), avec le bouton POI `44 × 44px` intégré à droite dans les champs départ/arrivée (sans bouton inversion sur Desktop).

---

## 3. Champ `Carte heure` Mobile (`86:1035`)

Utilisé sur **Accueil** et **Résultats** Mobile juste sous le bloc `Itinéraire`.

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `159 × 44px` (composant source) · `164 × 44px` (sur Accueil & Résultats) |
| **Fond & bordure** | `#FFFFFF` · `border: 2px solid #3478F6` · `border-radius: 14px` |
| **Contenu** | Icône `calendar4` `16 × 16px` à gauche + libellé `Partir:` (`Golos Text 16px / 28px`, `#68717A`) |

---

## 4. Composant `Horaire` (`87:972`)

Utilisé sur **Publier un trajet** et **Modifier le trajet** (Mobile & Desktop).

| Propriété | Valeur exacte |
| :--- | :--- |
| **Dimensions** | `352 × 41px` |
| **Rayon** | `14px` |
| **Fond du conteneur** | `#D9D9D9` (Mobile Publier/Modifier & Desktop Modifier) · `#FFFFFF` (Desktop Publier `103:861`) |
| **Labels** | `De:` (gauche) et `Arr:` (droite) en `Golos Text 16px / 28px`, `#68717A` |
| **Champs heures** | 2 pilules blanches `#FFFFFF`, `rounded: 5px`, valeurs `7h` et `7h30` (`Golos Text 16px`, `#68717A`) |
| **Inversion centrale** | `Bouton Inversion Horaires` `31 × 31px` cercle `#B08AE8` (`inset: 12.2% 45.45% 12.2% 45.74%`) |

---

## 5. Sélecteurs discrets : Jours (`L M M J V`) & Places (`1 2 3 4 5`)

Ces deux groupes de sélection réutilisent le composant `Pagination` en taille `Small` :

| État | Fond | Bordure | Texte |
| :--- | :--- | :--- | :--- |
| **Inactif** | `#FFFFFF` | `1px solid #E9ECEF` | `#6C757D` (`Inter 14px / 14px`) |
| **Sélectionné** | `#8039E9` (`--accent-dark`) | `1px solid #E9ECEF` | `#FFFFFF` (`Inter 14px / 14px`) |

- **Dimensions d'une case** : `padding: 8px 12px`, `border-radius: 4px`.
- **Espacement** : `4px` – `7px` entre chaque bouton (`List jours` : `L`, `M`, `M`, `J`, `V` ; `List places` : `1`, `2`, `3`, `4`, `5`).

<div class="note-figma">
  <strong>Note factuelle :</strong> Sur l'écran Mobile <code>Fiche trajet</code> (<code>64:164</code>), la pastille sélectionnée <code>1</code> (<code>82:478</code>) utilise le fond <code>#4E495B</code> (<code>--primary-light</code>) au lieu de <code>#8039E9</code> utilisé sur les autres écrans.
</div>

---

## 6. Checkboxes `Autorisés` (`Musique`, `Animaux`)

Utilisées sur **Fiche trajet** (`Infos`), **Contact**, **Publier**, **Modifier** et **Préférences**.

| État | Node ID | Dimensions & style |
| :--- | :--- | :--- |
| **Non cochée** | `87:761` | Carré `16 × 16px`, fond `#FFFFFF`, `border: 1px solid #ABB5BE`, `border-radius: 2px` |
| **Cochée** | `87:763` | Carré `16 × 16px`, fond `#7749F8`, `border-radius: 2px`, icône coche blanche `12 × 12px` centrée (`top: 2px`, `left: 2px`) |
| **Label** | `87:950` | `Inter` Regular `16px / 28px`, `#FFFFFF`, padding de `8px` autour de l'icône |

<div class="note-figma">
  <strong>Note factuelle :</strong> Sur les écrans Mobile (<code>Fiche trajet</code>, <code>Contact</code>, <code>Publier</code>, <code>Modifier</code>, <code>Préférences</code>), le groupe de checkboxes est entouré d'un cadre pointillé violet issu du conteneur de variante Figma (<code>border-dashed</code>). Sur Desktop, les checkboxes sont directement alignées sur le fond noir sans cadre pointillé.
</div>
