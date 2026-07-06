# Mission IA — L'Escape Game de la Charte

Escape game 3D dans le navigateur pour découvrir la **Charte IA de Bruxelles Formation** :
5 salles à déverrouiller (une par engagement), des énigmes tirées de la charte et de sa FAQ,
un code final **A · C · G · D** (les 4 marquages IA) et un **Permis IA BF** personnalisé à la clé.

## Jouer

Ouvrez simplement `index.html` dans un navigateur — un seul fichier, aucune installation,
**aucune connexion internet nécessaire** : le moteur 3D (Three.js), la police Space Grotesk
et les sons (synthétisés) sont embarqués dans le fichier. Il se partage donc aussi en pièce
jointe Teams/mail.

- **Avancer / reculer** : `Z`/`S` (ou `W`/`S`, flèches haut/bas) · **pas de côté** : `Q`/`D` (ou `A`/`D`)
- **Tourner** : flèches gauche/droite, souris (glisser), ou « Mode immersif »
- **Interagir** : cliquer sur une porte (le joueur s'y rend tout seul), ou presser `E` à proximité
- **Sans clavier / non-joueurs** : le bouton **Salles** ouvre chaque salle d'un clic
- Progression sauvegardée automatiquement (localStorage), énigmes mélangées à chaque partie
- **Mode compétition** : chronomètre optionnel (actif aussi pendant les énigmes), score,
  niveaux Or/Argent/Bronze, bouton « Copier mon résultat » pour le chat Teams
- **À la fin** : Permis IA BF nominatif téléchargeable en image ou imprimable
- Accessible : navigation clavier complète, lecteurs d'écran, `prefers-reduced-motion` respecté

## Les 5 salles = les 5 engagements

| Salle | Engagement | Slogan |
|---|---|---|
| 1 | Responsabilité et esprit critique | « L'IA propose, l'humain décide. » |
| 2 | Protection des données | « Interne sécurisé ≠ externe public. » |
| 3 | Transparence des usages | « Si l'IA a vraiment contribué, ça se dit. » |
| 4 | Usage responsable et proportionné | « Tout faire avec l'IA est aussi absurde que ne rien faire avec. » |
| 5 | Droits, inclusion et valeurs | « L'IA n'est pas une zone grise. » |

## Déployer sur GitHub Pages

1. **Settings → Pages**
2. Source : **Deploy from a branch** → branche principale → dossier **/ (root)** → **Save**
3. Après 1–2 minutes, le jeu est accessible sur `https://<votre-pseudo>.github.io/escapegamecharteia/`

La charte complète reste consultable sur [rochikh.github.io/charte-ia-bf](https://rochikh.github.io/charte-ia-bf/).
