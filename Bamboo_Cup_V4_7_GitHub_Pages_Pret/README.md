# Bamboo Cup LIVE — V4.7 (hébergement web)

Version du jeu Bamboo Cup prête à être publiée comme site statique via GitHub Pages.

## Fonctionnalités disponibles sur ce site
- Course et moteur physique, sons, caméra, podium et championnat locaux.
- Vue verticale TikTok et mode de démonstration de la sélection des équipes.

## À NE PAS CONFONDRE AVEC UNE CONNEXION TIKTOK
Cette version publique **ne reçoit pas encore les vrais commentaires**. Le connecteur Python local présent dans le pack Windows V4.7.1 ne peut pas automatiquement transmettre des événements à GitHub Pages. Un pont public HTTPS/WebSocket ou SSE, authentifié et sécurisé, reste à construire et tester.

## Publication GitHub Pages
Après création du dépôt GitHub `bamboo-cup-live`, ajoutez `index.html` et `.nojekyll` à la racine. Dans Settings > Pages, choisissez Deploy from a branch, `main`, `/(root)`, Save. Le site sera accessible ensuite en HTTPS.

Aucun identifiant/mot de passe TikTok à intégrer dans ce dépôt public. N'exposez pas le serveur Python local directement à Internet.
