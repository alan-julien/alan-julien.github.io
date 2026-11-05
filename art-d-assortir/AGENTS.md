# L'art d'assortir

Atelier interactif en 10 étapes pour apprendre à assortir ses vêtements à partir de ses palettes de colorimétrie (12 saisons). En ligne : https://alan-julien.github.io/art-d-assortir/

Lire aussi : `ETAT.md`, `CARTE.md`, `HISTORIQUE.md`, et les règles communes à toutes les pages dans `../AGENTS.md`.

## Règles

- Tout tient dans `index.html` (sans build) ; polices Google Fonts, icônes Phosphor (unpkg).
- Charte d'Alan pour l'interface ; les couleurs vives sont réservées au contenu (palettes, vêtements).
- Tous les exemples viennent des palettes cochées à l'accueil : ne jamais coder une couleur d'exemple en dur dans le contenu, passer par `PAL()` / `pools()`.
- Le juge (`judge`) est la seule source des verdicts (cabine, jeu, lookbook, capsule) : une nouvelle règle de mode s'y ajoute, pas ailleurs.
- Les palettes `SEASONS` sont copiées de `perso/nuance/js/seasons.js` : si Nuance change ses palettes, recopier.
- Après toute modification : tester chaque étape dans le navigateur du VPS (aucune erreur JavaScript, captures bureau et mobile).
