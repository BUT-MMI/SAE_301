# Déploiement GitHub Pages & Prévisualisation

La documentation est propulsée par **Docsify** directement depuis le dossier `docs/` : elle ne nécessite aucun build Node/Python côté serveur et fonctionne nativement sur GitHub Pages.

---

## 1. Activer GitHub Pages sur le dépôt

1. Poussez les modifications du dossier `docs/` sur la branche `main` du dépôt `BUT-MMI/SAE_301`.
2. Sur GitHub, ouvrez **Settings** → **Pages**.
3. Dans **Build and deployment** :
   - **Source** : `Deploy from a branch`
   - **Branch** : `main`
   - **Folder** : `/docs`
4. Cliquez sur **Save**.
5. Après 1 à 2 minutes de déploiement, la documentation est accessible à l'adresse :
   `https://but-mmi.github.io/SAE_301/`

<div class="note-figma">
  <strong>Points techniques déjà configurés :</strong><br>
  • Le fichier <code>docs/.nojekyll</code> empêche Jekyll d'ignorer les fichiers commençant par un underscore (<code>_sidebar.md</code> et <code>_navbar.md</code>).<br>
  • Tous les liens et chemins d'images sont relatifs à la racine <code>docs/</code> (aucun chemin commençant par <code>/</code>), garantissant le bon chargement sous le sous-dossier <code>/SAE_301/</code>.
</div>

---

## 2. Prévisualiser en local

Depuis la racine du dépôt `SAE_301` :

```bash
python -m http.server 3000 -d docs
```

Puis ouvrez `http://localhost:3000` dans votre navigateur.

*(Alternative si `docsify-cli` est installé : `npx docsify-cli serve docs`.)*

---

## 3. Mettre à jour la documentation

1. Modifiez ou ajoutez les fichiers `.md` dans `docs/`.
2. Si vous ajoutez une nouvelle page, ajoutez son lien relatif dans `docs/_sidebar.md`.
3. Faites un `commit` et `push` sur `main` : GitHub Pages mettra automatiquement le site à jour.
