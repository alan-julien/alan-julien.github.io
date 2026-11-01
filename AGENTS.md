# Pages publiées d'Alan (alan-julien.github.io)

Ce dépôt réunit **toutes** les pages GitHub Pages d'Alan : le sommaire à la racine, une page par sous-dossier. Tout ce qui est poussé sur `main` est publié sur https://alan-julien.github.io/ en une minute environ.

Lire aussi : `ETAT.md` (où en est chaque page), `CARTE.md` (quelles pages, quels fichiers), `HISTORIQUE.md` (décisions communes). Chaque page a en plus ses propres `AGENTS.md`, `ETAT.md`, `CARTE.md` et `HISTORIQUE.md` dans son dossier : les lire avant d'y travailler.

## Règles

- **Nouvelle page** = un nouveau sous-dossier `<nom-de-la-page>/` avec son `index.html` et ses quatre fichiers de projet, plus une ligne dans `PAGES` du sommaire (`index.html` racine : titre, étiquette, lien, brève description). Jamais de nouveau dépôt.
- Une page = des fichiers statiques sans build (HTML, CSS, JS ; bibliothèques et polices par CDN). Charte graphique d'Alan (`perso/charte-graphique`) sauf demande contraire.
- Pousser sur `main` publie directement : c'est autorisé sans redemander.
- Les fichiers `.md` ne sont pas publiés (exclus dans `_config.yml`), mais le dépôt est **public** : rien de privé ni de secret.
- Tester une page avant de pousser : sur le VPS, navigateur pilotable décrit dans `global/vps/14-navigateur.sh` (captures d'écran, erreurs JavaScript). Supprimer les scripts et captures de test une fois fini.
