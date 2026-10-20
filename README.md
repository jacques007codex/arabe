# Révision arabe libanais

Petite appli de révision des cours d'arabe libanais (Heba, Preply) : vocabulaire français ↔ arabe, conjugaisons au passé, possessifs, accords, nombres et questions. Elle marche hors ligne et s'installe sur l'iPhone (Safari, Partager, « Sur l'écran d'accueil »). La progression reste dans le navigateur (localStorage).

En ligne : https://jacques007codex.github.io/arabe/

## Ajouter un cours

1. Ouvrir `index.html` et aller au bloc « DONNÉES DES COURS » en haut du deuxième `<script>`.
2. Ajouter le cours dans `LESSONS`, puis ses lignes dans `ITEMS` avec le même code de cours.
3. Dans `sw.js`, passer `arabe-v1` à `arabe-v2` (etc.) pour que les téléphones prennent la mise à jour.
4. Commit et push sur `main` : GitHub Pages republie en une minute environ.
