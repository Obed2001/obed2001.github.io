# Portfolio — Obed Brice Djegné

Site statique (HTML, CSS, JavaScript), sans installation ni serveur. Il s'ouvre aussi directement en double-cliquant sur `index.html`.

## Contenu

- `index.html` : toute la page (design, filtres, recherche, fiches projets)
- `images/` : illustrations et captures des projets, favicon, image de partage (`hero.png`)
- `.nojekyll` : indique à GitHub Pages de servir les fichiers tels quels

## Mettre en ligne sur GitHub Pages

1. Créez un compte sur github.com (gratuit).
2. Cliquez sur **New repository**. Nommez-le `VOTRE-PSEUDO.github.io` (par exemple `obeddjegne.github.io`) et laissez-le **Public**.
3. Dans le dépôt, cliquez sur **Add file → Upload files**, puis glissez **le contenu** de ce dossier : `index.html`, le dossier `images`, `.nojekyll` et ce `README.md`. Validez avec **Commit changes**.
4. Allez dans **Settings → Pages**. Sous *Build and deployment*, choisissez **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
5. Après une à deux minutes, le site est en ligne à l'adresse `https://VOTRE-PSEUDO.github.io`.

## Ajouter ou modifier un projet

Dans `index.html`, cherchez `const projects = [`. Chaque projet est une ligne `{ id: ..., title: ..., status: ..., ... }` :

- `cat` : `app` (Web & mobile), `gest` (Gestion), `design` ou `auto` (Automatisation & sites)
- `status` : `En ligne`, `Livré`, `En cours`, `En conception`, `Bientôt en ligne` ou `Confidentiel`
- `img` : nom du fichier dans `images/`
- `link` : adresse du site (laisser `''` s'il n'y en a pas)

Après une modification, renvoyez le fichier sur GitHub (Upload files) : le site se met à jour tout seul.
