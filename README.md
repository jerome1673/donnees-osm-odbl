# Données dérivées d'OpenStreetMap pour « Logistique France »

Ces fichiers sont utilisés par le jeu **Logistique France** (carte, réseau routier, voies ferrées, forêts, eau, zones urbaines, densité des bâtiments).
Ils sont **dérivés des données d'OpenStreetMap** : sélection, simplification et recodage des routes, des voies ferrées, des zones et des bâtiments pour les besoins du jeu.

## Licence

© les contributeurs d'OpenStreetMap — données disponibles sous la licence **Open Database License (ODbL) 1.0**.
Texte de la licence : https://opendatacommons.org/licenses/odbl/1-0/ · Plus d'informations : https://www.openstreetmap.org/copyright

Ces fichiers (« base de données dérivée ») sont mis à disposition sous la même licence ODbL : vous pouvez les copier, les distribuer, les modifier et les utiliser,
à condition de citer OpenStreetMap, de conserver cette licence et de mettre à disposition sous ODbL les bases que vous en dérivez.
Le jeu lui-même (code, graphismes, règles) n'est pas concerné : il est distribué séparément et ses fichiers ne sont pas mélangés à ceux-ci.

## Contenu

| Fichier | Contenu |
|---|---|
| reseau-routier.js | grandes routes de France (autoroutes, voies rapides, routes principales), avec le type de chaque route |
| reseau-ferre.js | voies ferrées et gares |
| carte-sol.js | forêts, lacs et fleuves, mer, zones bâties (en cases) |
| carte-detail.js et dossier detail/ | détail des formes (zooms rapprochés) |
| carte-batiments.js | trame de densité des bâtiments (une case = 50 m) |
| zones-urbaines.js | zones urbaines et noms de lieux (avec populations de l'INSEE, sous Licence Ouverte Etalab 2.0) |

Chaque fichier JavaScript commence par un commentaire qui précise sa provenance.
