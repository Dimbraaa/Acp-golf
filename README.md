# Approche Chip Putt — PWA

Suivi des points Approche / Chip / Putt au golf (2 à 4 joueurs, 9 ou 18 trous), 100 % hors ligne.

## Installer sur l'iPhone
1. Ouvrir l'URL dans **Safari** (avec du réseau, une fois).
2. Bouton Partager → **Sur l'écran d'accueil**.
3. Lancer l'app depuis l'icône : elle fonctionne ensuite sans réseau.

## Mettre à jour l'app
Après toute modification, incrémenter `CACHE` dans `sw.js` (`acp-v1` → `acp-v2`), pousser, puis ouvrir l'app deux fois avec du réseau.

## Données
Les parties sont stockées localement sur le téléphone (localStorage). Supprimer l'app de l'écran d'accueil efface les données.
