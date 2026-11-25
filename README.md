# Le Mot Juste

Jeu de lettres en français : trouve un mot de 5 à 8 lettres en 6 essais, puis découvre sa définition.

- Vert : bonne lettre, bonne place. Orange : bonne lettre, mauvaise place. Gris : lettre absente.
- Chaque essai doit être un mot qui existe (dictionnaire dans `data/dico-N.txt`).
- Un indice par partie révèle une lettre et sa place.
- Les mots à trouver et leurs définitions sont dans `data/mots-N.json` (tableau de `["mot", "nature", "définition"]`).
- Le carnet garde les mots joués dans le navigateur (localStorage).

Site statique, aucune dépendance : il suffit de servir le dossier (GitHub Pages).

Dictionnaire de validation tiré du paquet npm `an-array-of-french-words`.
