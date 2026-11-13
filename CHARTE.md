# Charte graphique — ACP Golf

Slogan : **« Tu t'occupes du jeu, je m'occupe du score »**

Inspiration : le Golf de Valcros (La Londe-les-Maures). Vert des pins, green des fairways, or des îles d'Or, bleu de la Méditerranée, sable des bunkers. Les teintes sont **inspirées** du site golfdevalcros.com et du lieu ; ce ne sont pas des codes relevés sur le site.

## Logo

Fichier source : `logo.svg` (512 × 512). Icônes dérivées : `icon-512.png`, `icon-192.png`, `apple-touch-icon.png` (180 px).

- **A** : lettre blanche à trait arrondi.
- **C** : entoure une balle dorée (le trou, la balle qui finit dedans).
- **P** : son mât blanc dépasse et sa boucle est un drapeau doré (le drapeau du green).
- Fond vert pin avec une colline vert fairway en bas.

Usages :
- Sur fond vert pin : lettres blanches, balle et drapeau dorés (version de l'écran de lancement).
- Icône : toujours sur fond plein, sans transparence (iOS arrondit lui-même les coins).
- Ne pas changer les couleurs du logo, ne pas l'étirer, garder une marge autour d'au moins la hauteur de la balle.

## Couleurs

| Rôle | Nom | Code | Utilisation |
|---|---|---|---|
| Primaire | Vert pin | `#1F4D3A` | En-têtes, écran de lancement, fond du logo, bandeau gagnant |
| Secondaire | Vert fairway | `#2E6B4A` | Boutons principaux, colline du logo, signature |
| Accent | Or des îles | `#E3AE45` | Balle et drapeau du logo, slogan sur fond vert, liseré du gagnant |
| Fond | Sable | `#F5F1E8` | Fond des écrans |
| Fond doux | Vert tendre | `#E6EFE9` | Totaux, 1er du classement |
| Surface | Blanc | `#FFFFFF` | Cartes, tableaux |
| Texte | Ardoise | `#18211D` | Texte principal |
| Texte secondaire | Gris olivier | `#5E6A63` | Aides, détails |
| Trait | Pierre | `#DAD6CB` | Bordures des champs |
| Alerte | Rouge | `#B3261E` | Suppression, balle ramassée ✕ |
| Surlignage | Paille | `#FBF1DC` | Trou en cours, correction en cours |

Couleurs des points Approche / Chip / Putt :

| Point | Nom | Code |
|---|---|---|
| Approche | Bleu Méditerranée | `#1E5A85` |
| Chip | Terre cuite | `#B8582A` |
| Putt | Vert putt | `#2E7D4F` |

Contrastes vérifiés (norme WCAG AA, minimum 4,5) : blanc sur vert pin 9,6 ; blanc sur vert fairway 6,3 ; or sur vert pin 4,8 ; texte secondaire sur sable 5,0 ; blanc sur bleu 7,4, sur terre cuite 4,7, sur vert putt 5,1.

L'or ne s'utilise **jamais pour du texte sur fond clair** (contraste insuffisant) : seulement sur vert pin, ou en aplat décoratif.

## Typographie

Police système de l'appareil (SF Pro sur iPhone), sans police à télécharger, pour rester 100 % hors ligne.

- Titres et chiffres : gras 700 à 800.
- Texte courant : 15 à 17 px, régulier ou semi-gras.
- Aides et détails : 13 à 14 px, gris olivier.

## Écran de lancement

Au démarrage : fond vert pin, logo, nom « Approche · Chip · Putt », slogan en or. La balle tombe dans le C. L'écran s'efface seul après environ 1,8 seconde (ou au toucher). Si l'appareil demande de réduire les animations, il apparaît sans animation.

## Dans le code

Les couleurs sont dans les variables CSS en tête de `index.html` (`--green`, `--green2`, `--gold`, `--bg`, `--a`, `--c`, `--p`…). L'image de partage (canvas) reprend les mêmes codes en dur.
