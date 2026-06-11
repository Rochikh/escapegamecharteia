# Mission IA — L'Escape Game de la Charte

Escape game 3D dans le navigateur pour découvrir la **Charte IA de Bruxelles Formation** :
5 salles à déverrouiller (une par engagement), des énigmes tirées de la charte et de sa FAQ,
un code final **A · C · G · D** (les 4 marquages IA) et un **Permis IA BF** personnalisé à la clé.

## Jouer

Ouvrez simplement `index.html` dans un navigateur — un seul fichier, aucune installation.
Une connexion internet est nécessaire au premier chargement (moteur 3D Three.js et police
Space Grotesk chargés depuis des CDN épinglés).

- **Déplacement** : ZQSD / WASD ou flèches · regard à la souris (glisser, ou « Mode immersif »)
- **Interagir** : cliquer sur une porte, ou s'en approcher et presser `E`
- **Sans clavier / non-joueurs** : le bouton **Salles** ouvre chaque salle d'un clic
- La progression est sauvegardée automatiquement (localStorage) ; chronomètre optionnel
  pour les compétitions entre équipes.

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
