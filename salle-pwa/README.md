# Salle – par énergie

Petite app (PWA) pour suivre ses séances de salle selon son niveau d’énergie : 🔥 pleine, ⚡ moyenne, 🌿 repos actif. Fonctionne hors ligne, les coches sont gardées sur le téléphone.

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (ex. `salle`), en public.
2. Envoie tous les fichiers de ce dossier à la racine du dépôt.
3. Dans le dépôt : **Settings → Pages**.
4. Source : **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis Save.
5. Après 1-2 minutes, l’app est sur `https://TON-PSEUDO.github.io/salle/`.

## L’installer sur iPhone

1. Ouvre le lien dans **Safari**.
2. Bouton Partager → **Sur l’écran d’accueil**.

## Modifier les séances

Les exercices sont dans la variable `L` en haut du script de `index.html`.
Après un changement, passe `CACHE = "salle-v1"` à `"salle-v2"` dans `sw.js` pour que le téléphone récupère la nouvelle version.
