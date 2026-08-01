---
layout: default
title: Restore - Privacy Policy
---

# Restore - Privacy Policy

English translation below.

# Politique de confidentialité

## 0 - Intro

Attentif au respect de la vie privée des personnes dont les données sont traitées, **Restore** s'engage à assurer la protection des données personnelles et à être transparent quant à leur utilisation.

Ainsi, **Restore** s'engage à collecter et traiter les données personnelles conformément à la présente Politique de Confidentialité.

## 1 - Définitions

- **Données personnelles** : toute information relative à une personne identifiée ou qui peut être identifiée, directement ou indirectement.
- **Propriétaire** : toute personne ayant soumis un serveur Discord au programme de mise en avant de la **Communauté du RP FR**, et dont les données ont été archivées dans les salons concernés.
- **Administrateur** : membre de l'équipe de la **Communauté du RP FR** autorisé à utiliser le Bot.
- **Bot** : client de connexion Discord permettant aux Administrateurs de reconstruire la base de données de la **Communauté du RP FR** à partir des archives.

## 2 - Traitement automatique des données personnelles

Afin d'assurer le fonctionnement des opérations de récupération, le Bot lit et traite certaines données transmises par Discord, susceptibles de contenir des données personnelles.

Les données lues et traitées automatiquement sont les suivantes :
- Les **messages archivés** des salons dédiés aux serveurs inscrits au programme.
- Les **fils de forum** publiés dans le salon de présentation des serveurs.
- Les **logs de votes** enregistrés dans les salons prévus à cet effet.
- La **liste des membres** des serveurs Discord concernés, pour vérifier l'attribution des rôles propriétaires.
- Les **liens d'invitation** Discord associés aux serveurs inscrits, pour identifier les guildes liées.

Ces données sont lues en temps réel au moment des opérations de récupération et ne sont pas stockées en dehors de ce qui est décrit à la section 3. Elles ne sont accessibles qu'aux Administrateurs disposant des permissions Discord nécessaires pour déclencher les commandes du Bot.

Tout Propriétaire peut demander l'exclusion du contenu de ses messages de ces traitements automatiques en écrivant à l'adresse indiquée en Section 5.

## 3 - Conservation des données collectées

Certaines données issues des archives sont extraites et enregistrées de manière permanente dans la base de données afin de reconstruire les entrées perdues. Ces données concernent exclusivement les informations que les Propriétaires avaient eux-mêmes soumises au programme de mise en avant.

Les données enregistrées sont les suivantes :
- Un nom de serveur.
- Une description de serveur.
- Un emoji représentatif du serveur.
- Un lien d'invitation vers le serveur Discord.
- Une image GIF de présentation.
- La catégorie et sous-catégorie du serveur.
- Des métadonnées RP (inspiration, niveau, type, plateforme).
- L'**ID Discord du Propriétaire** du serveur.
- L'**ID Discord de la guilde** liée au serveur, le cas échéant.
- Le nombre de votes associés au serveur.

Des données relatives au système de tickets sont également reconstruites :
- L'**ID Discord** de l'utilisateur ayant ouvert un ticket.
- L'**ID Discord** du membre du staff ayant pris en charge le ticket.

Les données mises en cache par Discord (membres, messages) sont gérées par la bibliothèque discord.py et effacées automatiquement à chaque redémarrage du Bot. Aucun historique de ces données n'est conservé par le Bot lui-même.

## 4 - Suppression des données collectées

Les données enregistrées en base de données peuvent être supprimées sur simple demande du Propriétaire concerné, en contactant l'équipe via les coordonnées indiquées à la section 5.

Des tickets de suppression de données peuvent également être ouverts par les Propriétaires sur le serveur Discord de la **Communauté du RP FR**. Dans ces tickets, une simple commande de suppression est suffisante pour que les données soient supprimées, sans nécessité de fournir des informations supplémentaires.

Certaines données sont supprimées automatiquement dans les cas suivants :
- Un serveur est incomplet (champs obligatoires manquants) : ses données sont supprimées lors des opérations de nettoyage (`/cleanup`).
- Un fil de forum est orphelin (non associé à une entrée en base) : il est supprimé lors des opérations de nettoyage.
- Un utilisateur ne détient plus le rôle de Propriétaire : son rôle est retiré lors des opérations de nettoyage, mais ses données de serveur restent en base jusqu'à suppression explicite.

## 5 - Contact

Toute demande relative au traitement de ces données peut être adressée à l'équipe de **Restore** par mail :
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)

---

# Privacy Policy

## 0 - Introduction

Attentive to the privacy of the people whose data is processed, **Restore** is committed to ensuring the protection of personal data and to being transparent about its use.

Thus, **Restore** undertakes to collect and process personal data in accordance with this Privacy Policy.

## 1 - Definitions

- **Personal data**: any information relating to an identified person or a person who can be identified, directly or indirectly.
- **Owner**: any person who submitted a Discord server to the **Communauté du RP FR** listing program, and whose data was archived in the relevant channels.
- **Administrator**: a member of the **Communauté du RP FR** team authorised to use the Bot.
- **Bot**: Discord connection client allowing Administrators to reconstruct the **Communauté du RP FR** database from archived data.

## 2 - Automatic processing of personal data

In order to carry out recovery operations, the Bot reads and processes certain data transmitted by Discord that may contain personal data.

The automatically read and processed data are as follows:
- **Archived messages** from channels dedicated to servers registered in the listing program.
- **Forum threads** published in the server showcase channel.
- **Vote logs** recorded in the dedicated channels.
- The **member list** of the relevant Discord servers, to verify owner role assignments.
- **Discord invitation links** associated with registered servers, to identify linked guilds.

This data is read in real time during recovery operations and is not stored beyond what is described in section 3. It is only accessible to Administrators with the necessary Discord permissions to trigger the Bot's commands.

Any Owner may request that the content of their messages be excluded from these automated processes by writing to the address given in Section 5.

## 3 - Retention of collected data

Some data extracted from the archives is permanently stored in the database in order to reconstruct lost entries. This data relates exclusively to information that Owners had themselves submitted to the listing program.

The stored data is as follows:
- A server name.
- A server description.
- A representative emoji for the server.
- An invitation link to the Discord server.
- A GIF presentation image.
- The server's category and sub-category.
- RP metadata (inspiration, level, type, platform).
- The **Discord ID of the server's Owner**.
- The **Discord ID of the guild** linked to the server, where applicable.
- The number of votes associated with the server.

Data relating to the ticket system is also reconstructed:
- The **Discord ID** of the user who opened a ticket.
- The **Discord ID** of the staff member who handled the ticket.

Data cached by Discord (members, messages) is managed by the discord.py library and automatically cleared each time the Bot restarts. No history of this data is retained by the Bot itself.

## 4 - Deletion of collected data

Data stored in the database may be deleted upon request from the relevant Owner, by contacting the team via the details provided in section 5.

Data deletion tickets can also be opened by Owners on the **Communauté du RP FR** Discord server. In these tickets, a simple deletion command is sufficient for the data to be deleted, without the need to provide any additional information.

Some data is deleted automatically in the following cases:
- A server entry is incomplete (missing required fields): its data is deleted during cleanup operations (`/cleanup`).
- A forum thread is orphaned (not associated with a database entry): it is deleted during cleanup operations.
- A user no longer holds the Owner role: their role is removed during cleanup operations, but their server data remains in the database until explicitly deleted.

## 5 - Contact

Any request relating to the processing of this data may be addressed to the **Restore** team by email:
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)
