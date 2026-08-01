---
layout: default
title: Modmail - Privacy Policy
---

# Modmail - Privacy Policy

English translation below.

# Politique de confidentialité

## 0 - Intro

Attentif au respect de la vie privée de ses Utilisateurs, **Modmail** s'engage à assurer la protection des données personnelles de ses Utilisateurs et à être transparent quant à leur utilisation.

Ainsi, **Modmail** s'engage à collecter et traiter les données personnelles de ses Utilisateurs conformément à la présente Politique de Confidentialité.

## 1 - Définitions

- **données personnelles** : toute information relative à une personne identifiée ou qui peut être identifiée, directement ou indirectement.
- **Utilisateur** : toute personne membre du serveur Discord officiel de la Communauté du RP FR, qu'elle contacte le staff en envoyant un message privé au Bot, ou qu'elle fasse partie du staff traitant ces messages.
- **Bot** : Client de connexion Discord dédié à la gestion des messages privés adressés au staff du serveur officiel de la Communauté du RP FR, permettant à un Utilisateur d'entrer en contact avec le staff via un système de tickets.

## 2 - Traitement automatique des données personnelles

Afin d'assurer le fonctionnement des services proposés aux Utilisateurs, le Bot traite automatiquement certaines données transmises par Discord, susceptibles de contenir des données personnelles.

Les données traitées automatiquement sont les suivantes :<br/>
- Les messages privés (DM) envoyés au Bot par un Utilisateur, ainsi que leurs modifications et suppressions.<br/>
- Le nom d'utilisateur et la photo de profil de l'Utilisateur ayant ouvert un ticket.<br/>
- Les commandes d'application utilisées par le staff pour gérer les tickets.<br/>

La première donnée est traitée pour relayer la conversation entre l'Utilisateur et le staff : le contenu du message (texte et pièces jointes) est retransmis dans un salon de ticket dédié via un webhook Discord. Si l'Utilisateur modifie ou supprime son message, la version retransmise dans le ticket est mise à jour ou marquée comme supprimée en conséquence. L'ID du message d'origine, l'ID du message retransmis, l'ID du salon de ticket et l'ID de l'auteur sont enregistrés en base de données afin de faire le lien entre les deux, y compris pour rattraper les messages envoyés pendant que le Bot était hors ligne.

La deuxième donnée est traitée pour créer, pour chaque ticket, un webhook Discord reprenant le nom et la photo de profil de l'Utilisateur, afin que ses messages apparaissent sous son identité dans le salon de ticket vu par le staff.

La troisième donnée est traitée pour assurer le fonctionnement des commandes du staff (ouverture, réponse, fermeture d'un ticket, vérification qu'un utilisateur est bien membre du serveur, modification ou suppression d'un message relayé). L'ID de l'Utilisateur concerné, ainsi que l'ID du membre du staff ayant exécuté la commande, peuvent être enregistrés ou affichés dans les journaux d'activité du staff.

Tout Utilisateur peut demander l'exclusion du contenu de ses messages de ces traitements automatiques en écrivant à l'adresse indiquée en Section 5.

## 3 - Conservation de données collectées

Certaines données sont récoltées automatiquement et conservées temporairement (en cache) pour anticiper un éventuel traitement. C'est le cas des données du serveur sur lequel le Bot opère et de ses membres.

Certaines données sont collectées de manière explicite :<br/>
- Les tickets ouverts : ID de l'Utilisateur, ID du salon, adresses des webhooks utilisés pour relayer les messages.<br/>
- Les messages relayés : lien entre le message privé d'origine et le message retransmis dans le ticket (identifiants et auteur), le temps que le ticket reste ouvert.<br/>
- Les journaux de fermeture de ticket : envoyés sous forme d'embed dans un salon Discord réservé au staff, indiquant notamment l'identité de l'Utilisateur concerné.<br/>
- Les historiques (transcripts) de tickets fermés : envoyés sous forme de fichier dans ce même salon réservé au staff.<br/>

## 4 - Suppression des données collectées

Les données traitées automatiquement qui sont stockées sont effacées dès que leur utilité pour le bon fonctionnement de notre service n'est plus réelle.

Exemples :<br/>
- Lorsqu'un membre du staff ferme un ticket avec la commande dédiée, l'enregistrement du ticket et l'ensemble des liens de messages associés sont supprimés de la base de données, et le salon de ticket (ainsi que ses webhooks) est entièrement supprimé.<br/>
- L'historique (transcript) généré à la fermeture d'un ticket n'est en revanche pas supprimé : il reste archivé, avec un résumé de la fermeture, dans le salon de logs réservé au staff.<br/>

Les journaux et historiques envoyés dans les salons Discord du staff suivent la conservation propre au serveur Discord et ne peuvent être supprimés que manuellement par le staff. Ces données peuvent être supprimées complètement sur simple demande de la personne concernée, dans la limite de ce qui est nécessaire à la tenue d'un historique légitime des échanges avec le staff.

## 5 - Contact

L'utilisateur peut entrer en contact avec **Modmail** pour toute demande relative au traitement de ces données en envoyant un mail à :
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)

---

# Privacy policy

## 0 - Introduction

Attentive to the privacy of its Users, **Modmail** is committed to ensure the protection of its Users' personal data and to be transparent about their use.

Thus, **Modmail** undertakes to collect and process the personal data of its Users in accordance with this Privacy Policy.

## 1 - Definitions

- **Personal data**: any information relating to an identified person or a person who can be identified, directly or indirectly.
- **User**: any member of the official Discord server of the Communauté du RP FR, whether they contact staff by sending a direct message to the Bot, or are a staff member handling those messages.
- **Bot**: Discord connection client dedicated to managing private messages addressed to the staff of the official server of the Communauté du RP FR, allowing a User to get in touch with staff through a ticket system.

## 2 - Automatic processing of personal data

In order to ensure the functioning of the services offered to Users, the Bot automatically processes certain data transmitted by Discord that may contain personal data.

The automatically processed data are as follows:<br/>
- Direct messages (DMs) sent to the Bot by a User, as well as their edits and deletions.<br/>
- The username and profile picture of the User who opened a ticket.<br/>
- Application commands used by staff to manage tickets.<br/>

The first piece of data is processed to relay the conversation between the User and staff: the content of the message (text and attachments) is forwarded to a dedicated ticket channel via a Discord webhook. If the User edits or deletes their message, the forwarded version in the ticket is updated or marked as deleted accordingly. The original message's ID, the forwarded message's ID, the ticket channel's ID and the author's ID are recorded in the database to link the two, including to catch up on messages sent while the Bot was offline.

The second piece of data is processed to create, for each ticket, a Discord webhook reproducing the User's name and profile picture, so that their messages appear under their identity in the ticket channel seen by staff.

The third piece of data is processed to run staff commands (opening, replying to, closing a ticket, checking that a user is a server member, editing or deleting a relayed message). The ID of the User concerned, as well as the ID of the staff member who ran the command, may be recorded or displayed in staff activity logs.

Any User may request that the content of their messages be excluded from these automated processes by writing to the address given in Section 5.

## 3 - Retention of collected data

Some data is collected automatically and stored temporarily (cached) in anticipation of possible processing. This is the case for the data of the server on which the Bot operates and its members.

Some data is collected explicitly:<br/>
- Open tickets: the User's ID, the channel's ID, and the webhook addresses used to relay messages.<br/>
- Relayed messages: the link between the original direct message and the message forwarded in the ticket (IDs and author), for as long as the ticket stays open.<br/>
- Ticket-closing logs: sent as an embed to a staff-only Discord channel, including the identity of the User concerned.<br/>
- Closed ticket transcripts: sent as a file to that same staff-only channel.<br/>

## 4 - Deletion of collected data

The automatically processed data that is stored is deleted as soon as its usefulness for the proper functioning of our service is no longer real.

For instance:<br/>
- When a staff member closes a ticket using the dedicated command, the ticket's record and all associated message links are deleted from the database, and the ticket channel (along with its webhooks) is entirely deleted.<br/>
- The transcript generated when a ticket is closed, however, is not deleted: it remains archived, along with a closing summary, in the staff-only log channel.<br/>

Logs and transcripts sent to staff Discord channels follow the Discord server's own retention and can only be removed manually by staff. This data can be completely deleted upon request from the data owner, within the limits of what is necessary to maintain a legitimate history of exchanges with staff.

## 5 - Contact

The User may contact **Modmail** for any request relating to the processing of this data by sending an e-mail to:
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)
