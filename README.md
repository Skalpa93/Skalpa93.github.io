# Neon Maze V6

Jeu de labyrinthe arcade inspiré des jeux de poursuite classiques, livré comme PWA installable sur iPhone.

## Installation sur iPhone

1. Héberger ce dossier sur une URL HTTPS, par exemple GitHub Pages, Netlify ou Vercel.
2. Ouvrir l’URL dans **Safari** sur l’iPhone.
3. Appuyer sur **Partager**, puis **Sur l’écran d’accueil**.
4. Ouvrir l’icône **Neon Maze** depuis l’écran d’accueil.

Le jeu fonctionne hors connexion après le premier chargement grâce au service worker.

## Fichiers

- `index.html`, jeu complet responsive avec commandes tactiles et clavier.
- `manifest.webmanifest`, configuration d’installation PWA.
- `sw.js`, cache hors connexion.
- `icon-180.png` et `icon.svg`, icônes.
