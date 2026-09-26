# HBDGLO

Une surprise d'anniversaire pour Gloria 💌 — un site d'une seule page, sans build.

## Contenu
- `index.html` — tout le site (HTML, CSS, JS).
- `musique.mp3` — la musique de fond.
- `photos/` — photos (`.jpg`) et vidéos (`.mp4`) du diaporama.

## Personnaliser
Tout se règle dans l'objet `CONFIG` en haut du `<script>` de `index.html` :
- `volume` — volume de la musique (0 à 1).
- `musiqueDebut` — secondes à sauter au début de la chanson.
- `photosPlage` — médias de la scène de la plage.
- `videoHero` — la vidéo mise en avant avant la lettre.
- `photos` — le diaporama final (photos et vidéos mélangées, dans l'ordre).
- `lettre` — la lettre qui s'écrit à la fin.

## Voir en local
Ouvrir `index.html`, ou servir le dossier :

    python -m http.server 8000

## Déploiement
Hébergé sur Netlify : site statique, `publish = "."`, aucune commande de build (voir `netlify.toml`).
