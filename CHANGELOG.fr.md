Un moyen pratique et rapide d'écouter FIP depuis votre navigateur.

Son interface simple et pratique vous permet de lancer la radio en un seul clic, de scrobbler les musiques diffusées mais aussi d'afficher les informations du direct.

Vous pouvez suivre les bugs ou l'implémentation des fonctionnalités à cette adresse :
> https://github.com/oncletom/webextension-fip/issues

# Quoi de neuf ?

## Version 1.5.4

- corrige l'affichage manquant de l'année de sortie d'un album ([#94](https://github.com/oncletom/webextension-fip/pull/94))

Merci [Geoffrey](https://github.com/geoffrey-guilbon) pour ta contribution.

## Version 1.5.3

- correction du flux de données pour afficher à nouveau l'historique des titres diffusés

Merci à Geoffrey pour avoir signalé le problème.

## Version 1.5.2

- corrige le scrobbling last.fm

## Version 1.5.0

- affiche le nom de la station
- affiche un contrôleur de volume
- affiche un temps relatif pour les morceaux passés
- compatibilité avec le nouveau flux de données de FIP

## Version 1.4.0

- affiche les liens iTunes, Amazon et YouTube s'ils sont disponibles
- les boutons de navigation utilisent des flèches en guise d'icône
- affiche le statut du scrobbling last.fm

## Version 1.3.0

- le lien 'Archives' est désormais lié à la radio sélectionné dans l'écran d'options
- l'écoute de la radio est actualisée si vous la changez dans les options (pas besoin de l'arrêter et de la lancer à nouveau)

## Version 1.2.8

- correction du scrobbling last.fm
- nouvel affichage des options last.fm
- Chrome : correction de l'affichage fluide (cassé dans 1.2.5)

## Version 1.2.5

- Firefox : correction de l'affichage lorsque l'extension est accédée depuis les _outils supplémentaires_
- correction d'une faute dans un message
- ajout d'une politique de confidentialité

## Version 1.2.3

- corrige la connexion à last.fm
- mise en conformité du code source pour la publication sur les plates-formes de distribution de l'extension

## Version 1.1.7

- corrige l'interface cassée depuis la redirection permanente de fipradio.fr vers fip.fr [#79](https://github.com/oncletom/webextension-fip/issues/79)

## Version 1.1.6

- active le débogage des requêtes réseau (pour rendre leur lecture plus aisée)

## Version 1.1.5

- règle les `permissions` du Manifeste pour autoriser les ressources `fipradio.fr`
- corriger la connexion à last.fm qui a été cassée par erreur

## Version 1.1.4

- mise à jour des dépendances (corrige un défaut d'affichage sous Firefox)

## Version 1.1.3

- ajout d'un CHANGELOG
- correction des boutons Précédent/Suivant (Firefox)

## Version 1.1.2

- correction de l'URL d'authentification pour le scrobbling last.fm et Chrome 60+

## Version 1.1.0

- le scrobbling last.fm est de retour — rendez-vous dans les options de l'extension :-)
- affichage des noms d'artiste, d'albums et de pistes en minuscules
- les liens last.fm des artistes, albums et pistes retournent des résultats plus précis

## Version 1.0.0

- sélection parmi les webradios :-)

## Version 0.9.1

- correction de bugs
- désactivation temporaire de Last.fm

## Version 0.8.0
- c'est Noël avant l'heure : le scrobbling fonctionne à nouveau !
- réduction du nombre de permissions nécessaires au fonctionnement de l'extension

## Version 0.7.7
- mise à jour de l'URL de playback (cf. http://espacepublic.radiofrance.fr/23-juin-2015-inaccessibilit-de-nos-antennes-tunein-et-itunes) /via https://github.com/cbonnissent

## Version 0.7.6
- compatibilité avec le nouveau site de FIP

## Version 0.7.5
- fonctionnalité de scrobbling rétablie

## Version 0.7.3
- scrobbling temporairement désactivé suite à un bug avec last.fm

## Version 0.7
- scrobbling automatique des musiques écoutées

## Version 0.6
- navigation dans les morceaux récents
- correction du chevauchement du titres et de la date d'un album

## Version 0.5.1
- correction du niveau de volume initial
- correction de disposition des informations affichées

## Version 0.5.0
- réglage du volume audio
- moins de bla bla, plus d'icônes

## Version 0.4.3
- meilleures icônes de lecture/pause

## Version 0.4.2
- meilleur affichage des artistes composant un groupe musical

## Version 0.4.1
- corrections d'affichage
- nettoyage d'artefacts dans les noms d'artiste et d'albums

## Version 0.4.0
- lien vers les archives de FIP
- liens vers last.fm sur le titre de la chanson, l'album et l'artiste

## Version 0.3.0
- affichage des informations du direct

## Version 0.2.0
- meilleure gestion des états du lecteur (lecture, pause, erreur)
- prise en compte de la connectivité réseau
- nettoyage du code

Prochaine étape : afficher les informations du direct.

## Version 0.1.3
- multilinguisme français / anglais

## Version 0.1.2
- réinitialisation de l'indicateur lorsque le navigateur est de nouveau ouvert
- l'indicateur d'erreur n'est plus affiché lorsque la radio est mise en pause

## Version 0.1.1
- amélioration de la stabilité en cas d'erreur/mise en sommeil d'un ordinateur portable
- indicateur de chargement tant que la radio n'est pas prête à être diffusée

## Version 0.1.0
- première version (par un nostalgique de FIP en terres anglaises)
