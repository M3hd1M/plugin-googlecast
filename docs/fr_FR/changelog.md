# Changelog

Liste des versions du plugin googlecast.

*[Retour à la documentation](index.md)*

## Version du 09 juin 2018 (stable)

- Passage de la beta en stable (voir les changements beta)
- Reprise du flux précédant après TTS lorsque lancé via le plugin uniquement
- Widget 'speak' par défaut
- Correction de bugs and maj doc

## Version du 09 juin 2018 (beta)

- Fix quand pas de volume
- Maintenant 'resume' est le comportement par défaut. Il faut utiliser noresume=1 pour le désactiver
- Pour le resume, un 'play' est forcé
- Fix pour failover picotts quand pas d'internet
- En cas d'erreur, 'status_text' est à 'ERROR' , 'CMD UNKNOWN' is la commande n'existe pas ou 'NOT CONNECTED' si offline

## Version du 08 juin 2018 (beta)

- Implémention fonction 'resume' pour TTS. Dsiponible que pour les applications lancées via le plugin (limitation Google)
- Fix pour retour alarme GH
- Correction de bug mineurs
- Changement d'icone du plugin (par Alois)
- Maj doc (exemple de bloc php pour scénario)

## Version du 07 juin 2018 (beta)

- Première version de la fonction 'resume' pour TTS
- Widget dédié pour TTS
- Correction de bug mineurs

## Version du 06 juin 2018

- Passage de la beta en stable (voir dessous)
- Fonctionnalités: TTS (4 moteurs), Plex, récupération config Google Cast
- Correction de bugs et maj doc

## Version du 04 juin 2018 (beta)

- Ajout du moteur Google Speech API (clé nécessaire)
- Ajout gestion PLEX
- Correction de bugs et maj doc

## Version du 29 mai 2018 (beta)

- Ajout de gestion de rapidité de parole pour TTS
- Récupération/modification de la configuration des équipements (ex: alarme/timer Google Home)
- Correction de bugs et maj doc

## Version du 25 mai 2018 (beta)

- Ajout de commandes 'info' : title, artist, player_state
- Ajout de l'option 'vol' pour chaque commande afin de modifier le volume (voir doc)
- Ajout du TextToSpeach (TTS) avec moteur Google Translate et PicoTTS (voir doc)
- Possibilité de lancer une séquence de commande (voir doc)
- Correction de bugs et maj doc

## Version du 25 avril 2018

- Fix installation des dépendances pour certain systèmes
- Fix impossibilité de (re)connection après quelques heures
- Réduction de l'tuilisation mémoire (fuite)

## Version du 23 avril 2018

- Fix installation des dépendances pour raspberry
- Fix impossibilité de (re)connection
- Ajout de possibilité de réglage de la fréquence de rafraîchissement

## Version du 18 avril 2018

Première version stable
