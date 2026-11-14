# ACP Golf — Approche Chip Putt

*Tu t'occupes du jeu, je m'occupe du score.*

Carte de score golf, 100 % hors ligne, 9 ou 18 trous. Trois formules au choix à la création de la partie :
- **Approche / Chip / Putt** (2 à 4 joueurs)
- **4-2-0 (la Chouette)** à 3 joueurs, **6-4-2-0** à 4 joueurs, en brut ou en net.
- **Wolf** (4 joueurs, règles par défaut sans variante), en brut ou en net : sur chaque trou, le Loup joue avec un partenaire (2 pts chacun s'ils gagnent, 3 pts pour chaque adversaire s'ils perdent), en Loup solitaire (4 pts / 1 pt pour chacun des autres) ou en Loup aveugle (le double). Rotation du Loup sur 16 trous (8 sur 9 trous), puis le dernier au classement est le Loup.

Le net utilise les parcours intégrés (Valcros, Valgarde, Barbaroux) ; « Autre golf » se joue en brut.

## Installer sur l'iPhone
1. Ouvrir l'URL dans **Safari** (avec du réseau, une fois).
2. Bouton Partager → **Sur l'écran d'accueil**.
3. Lancer l'app depuis l'icône : elle fonctionne ensuite sans réseau.

## Mettre à jour l'app
Après toute modification, incrémenter `CACHE` dans `sw.js` (`acp-v1` → `acp-v2`), pousser, puis ouvrir l'app deux fois avec du réseau.

## Données
Les parties sont stockées localement sur le téléphone (localStorage). Supprimer l'app de l'écran d'accueil efface les données.

## Charte graphique
Logo, couleurs et typographie : voir [CHARTE.md](CHARTE.md).
