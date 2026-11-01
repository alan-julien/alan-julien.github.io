# Paris shopping — carte interactive

Carte des meilleurs coins shopping de Paris, publiée sur GitHub Pages : https://alan-julien.github.io/paris-shopping/

Lire aussi : `ETAT.md` (où on en est), `CARTE.md` (fichiers et accès), `HISTORIQUE.md` (décisions passées).

## Règles

- Tout tient dans `index.html` (HTML, CSS et JS, sans build). Leaflet et les polices viennent de CDN.
- Le style reprend celui de `perso/paris-grands-hommes` (charte d'Alan : indigo, Cormorant, Sora) : rester cohérent avec lui.
- Fond de carte : tuiles OpenStreetMap standard (pas de CARTO, qui exige une clé).
- Photos : uniquement Wikimedia Commons, via `Special:FilePath` (champ `img` = nom exact du fichier), avec le crédit affiché. Vérifier que chaque nouvelle photo répond en 200 avant de pousser.
- Pousser sur `main` publie directement la page : c'est autorisé sans redemander.
