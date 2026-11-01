# Carte

`index.html`, tout en un, découpé par commentaires `<!-- ============ N. … -->` (HTML) et `/* === N. … */` (script) :

- **Outils couleur** (début du script) : conversions sRGB ↔ linéaire ↔ XYZ ↔ CIELAB/LCh, `lchFit` (ramène dans le gamut), `vocab` (traduit une couleur en mots des saisons), longueur d'onde → RVB, kelvins → RVB.
- **Navigation** : `go(i)`, progression dans `localStorage` (`science-couleurs-v1`, et `sc-pont` pour les niveaux du jeu de l'étape 8), `QUIZ` (défis à choix).
- **`SEASONS`** : les 12 saisons (nom FR/EN, dominante, secondaire, profil type `p` = température/valeur/chroma, saison opposée, description, palette de 8 couleurs). `seasonOf(t,v,c)` attribue la saison.
- Étape 5 : métamérisme calculé (fonctions colorimétriques de Wyman 2013, corps noir de Planck, adaptation de Bradford).
- Étape 7 : développement photo (`devPixel`, `wbGains`, `drawScene` dessine la scène et la mire ColorChecker, `renderPhoto`).
- Étape 8 : jeu « changer de saison » (`LV` = niveaux et réglages cachés).
- Étape 9 : dictionnaire (`G`) et examen final (`FQ`).
