# VESTA — site web

Fichier unique et autonome : `index.html` (images incluses, aucune dépendance).

## Publication via GitHub Pages

GitHub Pages ne sait servir un site que depuis la **racine du dépôt** ou depuis un dossier nommé **`/docs`** (pas depuis `/website`).

Deux options :

1. **Recommandé** — renommer ce dossier en `docs`, puis :
   Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `/docs` → Save.
2. Ou copier `index.html` à la racine du dépôt, puis Branch: `main` / `/ (root)`.

Le site est ensuite en ligne sur `https://<utilisateur>.github.io/<dépôt>/` (1 à 2 minutes).

## Domaine personnalisé

Ajouter un fichier `CNAME` contenant le domaine (ex. `vesta-services.org`) à côté de `index.html`, puis pointer le DNS vers GitHub Pages.
