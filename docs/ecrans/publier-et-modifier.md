# Publier & Modifier un trajet

<span class="node-badge">Publier : Mobile 64:224 · Desktop 120:551</span> <span class="node-badge">Modifier : Mobile 96:1249 · Desktop 103:1047</span>

Ces deux écrans partagent exactement la même structure fonctionnelle et visuelle : seul le titre de page et le libellé du bouton CTA final changent (`Publier` vs `Modifier`).

---

## 1. Publier un trajet

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-publier.png" alt="Mobile Publier un trajet">
    <figcaption>Mobile — 64:224 (375 × 1007px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-publier.png" alt="Desktop Publier un trajet">
    <figcaption>Desktop — 120:551 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 2. Modifier le trajet

<div class="mockup-compare">
  <figure class="mockup-card">
    <img src="assets/mockups/mobile-modifier.png" alt="Mobile Modifier un trajet">
    <figcaption>Mobile — 96:1249 (375 × 1007px)</figcaption>
  </figure>
  <figure class="mockup-card">
    <img src="assets/mockups/desktop-modifier.png" alt="Desktop Modifier le trajet">
    <figcaption>Desktop — 103:1047 (1280 × 720px)</figcaption>
  </figure>
</div>

---

## 3. Structure Mobile (`375 × 1007px`)

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Nav Bar** | `top: 0`, `h: 72px` | Fond `#090B10` |
| **Titre** | `top: 102px` (centre), `w: 351px` | `Publier un trajet` / `Modifier le trajet` · `SUSE Mono` ExtraBold `32px`, `#FFFFFF`, centré |
| **Section `Itiniéraire`** *(orthographe Figma)* | Label `left: 20px`, `top: 152px` (`SUSE Mono` Bold `24px` `#3478F6`) · Bloc `Itinéraire` `left: 11px`, `top: 183px`, `w: 352px`, `h: 105px` | `Miramas` → `Arles`, boutons POI + Inversion |
| **Section `Horaire`** | Label `left: 21px`, `top: 318.5px` (`SUSE Mono` Bold `20px` `#3478F6`) · Bloc `Horaire` `left: 11px`, `top: 339px`, `w: 352px`, `h: 41px` | Fond `#D9D9D9`, `De: 7h`, bouton inversion `31×31`, `Arr: 7h30` |
| **Section `Jours`** | Label `left: 21px`, `top: 409.5px` (`SUSE Mono` Bold `20px` `#3478F6`) · `List jours` `left: 21px`, `top: 442px` | 5 pastilles `L`, `M`, `M`, `J`, `V` (`L`, `M`, `J` actifs en `#8039E9`) |
| **Section `Nombre de place`** | Label `top: 506px` (`SUSE Mono` Bold `24px` `#3478F6`) · `List places` `left: 22px`, `top: 532px` | 5 pastilles `1`, `2`, `3`, `4`, `5` (`1` actif en `#8039E9`) |
| **Section `Autorisés`** | Label `left: 22px`, `top: 590px` (`588px` sur Modifier) (`SUSE Mono` Bold `24px` `#3478F6`) | Checkboxes `Musique` / `Animaux` encadrées d'un pointillé violet |
| **Section `Description`** | Label `left: 22px`, `top: 710px` (`708px` sur Modifier) · Textarea `left: 12px`, `top: 734px` (`732px`), `351 × 114px` | `#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, `padding: 16px` |
| **Bouton CTA** | `top: 857px`, `w: 110px`, `h: 44px` (`left: 141px` Publier / `133px` Modifier) | `Publier` / `Modifier` · `#B08AE8`, `rounded: 6px`, `Inter` SemiBold `16px` `#FFFFFF` |
| **Footer** | `top: 922px`, `h: 85px` | Fond `#000000` |

---

## 4. Structure Desktop (`1280 × 720px`)

Conteneur principal à `left: 64px`, `top: 108px`, `w: 1152px`, `h: 504px`.

| Zone | Position & dimensions | Détails visuels |
| :--- | :--- | :--- |
| **Navigation desktop** | `top: 0`, `h: 72px` | Lien actif sur `Publier un trajet` (`#DAC4FB`) sur l'écran Publier |
| **Titre** | `left: 0`, `top: 0` | `Publier un trajet` / `Modifier le trajet` · `SUSE Mono` ExtraBold `40px`, `#FFFFFF` |
| **Panneau gauche : `Itinéraire`** | `left: 0`, `top: 80px`, `w: 552px`, `h: 410px` | Fond `#000000`, `rounded: 8px`, padding `24px` |
| ↳ Sous-titre `Itinéraire` | `left: 24px`, `top: 20px` | `SUSE Mono` Bold `28px`, `#3478F6` |
| ↳ `Point de départ` | Label `top: 64px` (`#3478F6`) · Input `top: 94px`, `w: 504px`, `h: 48px` | Valeur `Miramas` (`#4E495B`), `rounded: 6px` |
| ↳ `Point d'arrivée` | Label `top: 152px` (`#3478F6`) · Input `top: 182px`, `w: 504px`, `h: 48px` | Valeur `Arles` (`#4E495B`), `rounded: 6px` |
| ↳ `Horaire` | Label `top: 244px` (`#3478F6`) · Bloc `Horaire` `top: 276px`, `w: 352px`, `h: 41px` | Fond `#FFFFFF` sur Publier · fond `#D9D9D9` sur Modifier |
| ↳ `Jours` | Label `top: 330px` (`#3478F6`) · `Jours de circulation` `top: 368px` | `L` (`24px`), `M` (`63px`), `M` (`104px`), `J` (`145px`), `V` (`186px`) — `L`, `M`, `J` actifs en `#8039E9` |
| **Panneau droit : `Préférences du trajet`** | `left: 584px` (gouttière `32px`), `top: 80px`, `w: 568px`, `h: 350px` | Fond `#000000`, `rounded: 8px`, padding `24px` |
| ↳ `Autorisés` | Label `top: 20px` (`#3478F6`) · `Musique` coché (`left: 24px`, `top: 56px`), `Animaux` non coché (`left: 220px`, `top: 56px`) | `Inter 16px` `#FFFFFF` |
| ↳ `Nombre de place` | Label `top: 112px` (`#3478F6`) · Pastilles `1..5` `top: 150px` (`x = 24, 63, 104, 145, 186px`) | `1` actif en `#8039E9` |
| ↳ `Description` | Label `top: 206px` (`#3478F6`) · Textarea `top: 244px`, `w: 520px`, `h: 82px` | `#FFFFFF`, `border: 1px solid #DEE2E6`, `rounded: 6px`, texte `#4E495B` |
| **Bouton CTA (`Publier` / `Modifier`)** | `left: 864px`, `top: 442px`, `w: 288px`, `h: 48px` | Fond `#B08AE8`, `rounded: 6px`, `Golos Text 16px` `#FFFFFF` |
| **Footer** | `top: 648px`, `h: 72px` | Fond `#000000` |
