# Ontin

Site GitHub Pages du jeu de rôle **Ontin**, comprenant le livre de règles et le créateur de personnage.

## Structure

- `index.html` : créateur de personnage interactif, publié à la racine du site ;
- `rulebook/index.md` : page d’accueil et parent de navigation du livre de règles ;
- `rulebook/*.md` : un fichier par grand chapitre, affiché dans le menu gauche de Just the Docs ;
- `_config.yml` : configuration Jekyll et GitHub Pages.

## Publication

Dans les paramètres GitHub du dépôt, ouvrez **Pages**, choisissez **Deploy from a branch**, puis sélectionnez la branche `main` et le dossier `/ (root)`.

Le site sera disponible à l’adresse <https://parvenu.github.io/ontin-jdr/>.

Les liens internes utilisent le sous-chemin `/ontin-jdr` défini par `baseurl` dans `_config.yml`.
