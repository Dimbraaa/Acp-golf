# Approche Chip Putt — PWA

Suivi des points Approche / Chip / Putt au golf (2 à 4 joueurs, 9 ou 18 trous), 100 % hors ligne.

## Publier sur GitHub Pages
1. Sur github.com : **New repository** → nom `acp-golf` → **Public** → Create.
2. **Add file → Upload files** : glisser `index.html`, `sw.js`, `manifest.webmanifest`, `README.md`, et les 3 fichiers `.png` → Commit.
   (ou en CLI : `git init && git add . && git commit -m init && git branch -M main && git remote add origin git@github.com:<user>/acp-golf.git && git push -u origin main`)
3. **Settings → Pages** → Source : *Deploy from a branch* → `main` / `(root)` → Save.
4. Une minute plus tard : `https://<user>.github.io/acp-golf/`

## Installer sur l'iPhone
1. Ouvrir l'URL dans **Safari** (avec du réseau, une fois).
2. Bouton Partager → **Sur l'écran d'accueil**.
3. Lancer l'app depuis l'icône : elle fonctionne ensuite sans réseau.

## Mettre à jour l'app
Après toute modification, incrémenter `CACHE` dans `sw.js` (`acp-v1` → `acp-v2`), pousser, puis ouvrir l'app deux fois avec du réseau.

## Données
Les parties sont stockées localement sur le téléphone (localStorage). Supprimer l'app de l'écran d'accueil efface les données.
