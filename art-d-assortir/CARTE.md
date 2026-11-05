# Carte

`index.html`, tout en un, découpé par commentaires `<!-- ============ N. … -->` (HTML) et `/* === … */` (script) :

- **Données** : `SEASONS` (12 saisons de Nuance : palette, neutres, à éviter, métaux, motifs, noir, profil T/D/C/K), `NAMES` (noms de couleurs de la mode), `LEATHER` (cuirs).
- **Outils couleur** : CIELAB, `dE`, roue des peintres (`ryb`, `gap`), `isNeutral`, `nameOf`.
- **`PAL()`** : palette combinée des saisons cochées (rôles neutre / principale / accent, couleurs « pont », à éviter, profil moyen). Sélection gardée dans `localStorage` (`art-assortir-v1`).
- **Pièces** : `MATS` (matières), `CAT` (pièces homme / femme par emplacement), `DRAW` + `flatSVG` (dessin à plat des tenues, textures `tx-*` dans le `<svg>` caché du haut).
- **`judge(o)`** : toutes les règles (palette près du visage, 3 couleurs max, harmonie, cuirs, saisons mélangées, contraste, surface vive, formalité, matières).
- **`OCC` + `genOutfit` / `spoil`** : tenues par occasion (lookbook, jeu, cabine au hasard) et tenues fautives pour le jeu.
- Étapes : `RENDER[0..9]` (accueil, palette, basiques/capsule, harmonies, proportions, matières/motifs, règles/mythes `RULES` `MYTHS`, cabine, jeu, lookbook) ; défis dans `QUIZ`.
