# Outils

- Serveur Discord: https://discord.gg/U2gWAf4p
- Planning = AirTable, accessible depuis Outline wiki > Planning, filtrer > CDA
- Replay = AirTable, accessible depuis Outline wiki > Lien des replay
- ...

# S01 - Eval

- MCD = Modèle Conceptuel des Données
- MLD = Modèle Logique des Données
- MPD = Modèle Physique des Données

Projet = extension d'une application de réseau social  

## ER Diagram (Entity-Relationship) 

https://lucid.app/lucidchart/fb934b16-25b2-4bc2-9011-f784da1a94f6/edit?viewport_loc=-161%2C288%2C2217%2C1243%2C0_0&invitationId=inv_a9c935ec-5c65-455a-b630-734c33e08229  

## Mockups des différentes fonctionnalités 

- seul le créateur d'un groupe peut ajouter des membres

### Partage de Ressources

- on peut partager avec une personne ou tout un groupe
- taille max configurable selon le type de fichier
- date d'expiration des fichiers partagés
- la gestion des accès se fait soit au niv user, soit au niveau d'un groupe
- par défaut, un fichier privé est uniquement visible par la personne qui l'a partagé
- les fichiers auxquels on a accès sont visibles comme sur un drive
- rech par nom, par type, contenu indexé

### Evènements

- onglet dédié à création d'events
- par défaut, personne ne participe à un event nouvellement créé
- éléments obligatoires à la création: nom, description, type, lieu, date début évènement
- limite du nb de participants configurable
- pouvoir annuler sa participation
- pouvoir cancel l'event
- impossible de s'inscrire à compter du début de l'event
- évènement public par défaut
- évènement modifiable post-création > notification aux participants
- accès aux détails de l'event avant d'accepter ou de refuser de participer
- réponses possibles : oui ou non

### Notifications

- peut être utilisé pour inviter des gens à un event ou pour informer d'un nouveau partage de fichiers
- aussi pour prévenir de la modif d'un event
- code couleur ou icônes pour identifier facilement l'importance de la notif
- une notif n'expire pas tant qu'elle n'a pas été lue
- permettre une action contextuelle en fonction du type de notif (pour limiter le tps consacré par l'utilisateur)

## MCD vs MLD vs MPD

Le MCD est élaboré en premier, pour comprendre et formaliser les besoins métier.  
Le MLD est construit à partir du MCD, pour préparer l’implémentation dans un SGBD, en tenant compte des règles d’intégrité et des structures logiques.

### MCD

Niveau le plus abstrait de la partie conception, comme une carte géographique générale, sans détails techniques.  

### MLD

Niveau intermédiaire, plus détaillé, introduisant des éléments techniques (tables, clés), mais sans être encore un schéma physique

Traduit le MCD en une structure plus détaillée et adaptée à une future implémentation informatique, sans être encore liée à une technologie spécifique.  
Sert de pont entre la conception et la réalisation technique, facilitant la transition vers la création de la base de données réelle.  

### MPD



---
EOF
