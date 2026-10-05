# Rando Matcher

Application web qui classe des parcours de randonnée selon les préférences de l'utilisateur.

## Fonctionnement
L'utilisateur règle son niveau, la durée maximale, le dénivelé maximal et ses paysages préférés.
Chaque parcours reçoit un score sur 100 : on retire des points selon l'écart avec les préférences
(paysage, niveau, durée, dénivelé). Le meilleur parcours est mis en avant, les autres sont triés
avec l'explication du score.

## Lancer
Ouvrir `index.html` dans un navigateur, ou activer GitHub Pages sur la branche `main`.

## Limites et suite
Les données sont des exemples approximatifs. Prochaines étapes : charger de vraies données
(OpenStreetMap / API Rando), carte interactive (Leaflet), filtre par distance depuis l'utilisateur.
