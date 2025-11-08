# Site de mariage — Lolia & Pieric

Ce dépôt contient un site statique (un seul fichier `index.html`).

## Publication via GitHub Pages (sans Netlify)
1. Uploadez `index.html` à la racine du dépôt (pas dans un sous-dossier).
2. Allez dans **Settings → Pages**.
3. Dans *Source*, choisissez **Deploy from a branch**.
4. Dans *Branch*, sélectionnez **main** et **/** (root), puis **Save**.
5. Après 1–2 minutes, votre site sera en ligne à l’URL :  
   `https://<votre-utilisateur>.github.io/<nom-du-depot>/`

## Mise à jour
Modifiez `index.html` et faites **Commit** (push) ; GitHub Pages republiera automatiquement.

---

### Dépannage
- Si la page 404 s’affiche, vérifiez que : `index.html` est bien **à la racine** et que **Settings → Pages** pointe sur **main / root**.
- Pas de *build command* requis. Aucune action GitHub Actions n’est nécessaire pour ce site.
