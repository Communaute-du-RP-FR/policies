# Moderator - Privacy Policy

English translation below.

# Politique de confidentialité

## 0 - Intro

Attentif au respect de la vie privée de ses Utilisateurs, **Moderator** s'engage à assurer la protection des données personnelles de ses Utilisateurs et à être transparent quant à leur utilisation.

Ainsi, **Moderator** s'engage à collecter et traiter les données personnelles de ses Utilisateurs conformément à la présente Politique de Confidentialité.

## 1 - Définitions

- **données personnelles** : toute information relative à une personne identifiée ou qui peut être identifiée, directement ou indirectement.
- **Utilisateur** : toute personne membre du serveur Discord officiel de la Communauté du RP FR sur lequel le Bot opère, que ce soit en utilisant directement ses commandes (notamment le staff) ou indirectement via les salons et systèmes automatisés du Bot.
- **Bot** : Client de connexion Discord dédié à la modération et à l'administration du serveur officiel de la Communauté du RP FR, permettant au staff d'utiliser les services de modération proposés par **Moderator**.

## 2 - Traitement automatique des données personnelles

Afin d'assurer le fonctionnement des services proposés aux Utilisateurs, le Bot traite automatiquement certaines données transmises par Discord, susceptibles de contenir des données personnelles.

Les données traitées automatiquement sont les suivantes :<br/>
- Les messages envoyés dans certains salons dédiés (jeu des mots enchaînés, suggestions, salons comptabilisant l'activité RP).<br/>
- Les commandes d'application (slash commands) utilisées par le staff, notamment celles de modération.<br/>
- Les interactions liées à l'ouverture, la prise en charge et la fermeture des tickets.<br/>
- L'activité d'envoi de messages de tous les membres, à des fins de détection de spam.<br/>

La première donnée est traitée pour permettre le fonctionnement du jeu des mots enchaînés (le dernier mot joué et l'ID de son auteur sont enregistrés pour éviter les répétitions) et du salon de suggestions (le message est recopié dans un embed identifiant son auteur, puis le message original est supprimé). Dans les salons d'activité RP, l'envoi d'un message peut faire progresser un score lié à l'ID d'un propriétaire de serveur RP inscrit sur la Liste du RP FR.

La deuxième donnée est traitée pour assurer le fonctionnement des commandes de modération (`/warn`, `/mute`, `/unmute`, `/role`, etc.). Selon la commande, l'ID de la personne ciblée, la raison fournie et l'ID du modérateur sont enregistrés en base de données (pour les avertissements) ou envoyés dans un salon de logs réservé au staff (pour les autres actions de modération).

La troisième donnée est traitée pour gérer le cycle de vie d'un ticket : l'ID de la personne ayant ouvert le ticket et, le cas échéant, l'ID du membre du staff l'ayant pris en charge sont enregistrés tant que le ticket est ouvert. À la fermeture, un historique complet du salon (contenu des messages et identité des auteurs) est généré sous forme de fichier et envoyé dans un salon de logs réservé au staff.

La dernière donnée est traitée pour détecter les comportements de spam : le Bot conserve temporairement, en mémoire (et non en base de données), les horodatages des derniers messages envoyés par chaque membre, identifié par son ID. Un membre envoyant plus de 5 messages en moins de 7 secondes peut être automatiquement mis en sourdine (timeout) pendant 3 jours.

Le Bot permet également au staff d'agir sur les données liées aux serveurs de rôle-play inscrits sur la Liste du RP FR (validation, modification, suppression d'inscription). Le traitement de ces données est décrit dans la Politique de Confidentialité du bot [**Liste du RP FR**](https://github.com/Communaute-du-RP-FR/policies/blob/main/docs/privacy/liste-du-rp-fr.md), avec lequel **Moderator** partage sa base de données.

## 3 - Conservation de données collectées

Certaines données sont récoltées automatiquement et conservées temporairement (en cache) pour anticiper un éventuel traitement. C'est le cas des données du serveur sur lequel le Bot opère (et de ses membres), ainsi que des horodatages utilisés pour la détection de spam.

Certaines données sont collectées de manière explicite :<br/>
- Les avertissements (warns) : ID de la personne visée, ID du modérateur, raison et date sont enregistrés en base de données.<br/>
- L'historique du jeu des mots enchaînés : chaque mot joué est associé à l'ID de son auteur.<br/>
- Les logs de modération (mute, unmute, changements de rôle, ouverture/fermeture de ticket) : envoyés sous forme d'embeds dans un salon Discord réservé au staff.<br/>
- Les historiques (transcripts) de tickets fermés : envoyés sous forme de fichier dans un salon Discord réservé au staff.<br/>

## 4 - Suppression des données collectées

Les données traitées automatiquement qui sont stockées sont effacées dès que leur utilité pour le bon fonctionnement de notre service n'est plus réelle.

Exemples :<br/>
- L'enregistrement en base de données d'un ticket (opener, staff en charge) est supprimé dès la fermeture du ticket. L'historique (transcript) généré à cette occasion n'est en revanche pas supprimé : il reste archivé dans le salon de logs du staff.<br/>
- Les horodatages utilisés pour la détection de spam sont effacés automatiquement une fois traités, et entièrement réinitialisés à chaque redémarrage du Bot, sans historique conservé.<br/>

Les autres données collectées de manière explicite ne sont pas supprimées automatiquement :<br/>
- Un avertissement ne peut être supprimé de la base de données que par un membre du staff disposant des permissions d'administrateur, via l'interface `/warns`.<br/>
- L'historique du jeu des mots enchaînés n'est réinitialisé que manuellement par un membre du staff (`/game reset`).<br/>
- Les logs de modération et les transcripts envoyés dans les salons Discord du staff suivent la conservation propre au serveur Discord et ne peuvent être supprimés que manuellement par le staff.<br/>

Ces données peuvent être supprimées complètement de notre base de données sur simple demande de la personne concernée, dans la limite de ce qui est nécessaire à la tenue d'un historique de modération légitime.

## 5 - Contact

L'utilisateur peut entrer en contact avec **Moderator** pour toute demande relative au traitement de ces données en envoyant un mail à :
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)

---

# Privacy policy

## 0 - Introduction

Attentive to the privacy of its Users, **Moderator** is committed to ensure the protection of its Users' personal data and to be transparent about their use.

Thus, **Moderator** undertakes to collect and process the personal data of its Users in accordance with this Privacy Policy.

## 1 - Definitions

- **Personal data**: any information relating to an identified person or a person who can be identified, directly or indirectly.
- **User**: any member of the official Discord server of the Communauté du RP FR on which the Bot operates, whether they directly use its commands (in particular staff members) or interact indirectly through the Bot's automated channels and systems.
- **Bot**: Discord connection client dedicated to the moderation and administration of the official server of the Communauté du RP FR, allowing staff to use the moderation services offered by **Moderator**.

## 2 - Automatic processing of personal data

In order to ensure the functioning of the services offered to Users, the Bot automatically processes certain data transmitted by Discord that may contain personal data.

The automatically processed data are as follows:<br/>
- Messages sent in certain dedicated channels (chained-words game, suggestions, channels counting RP activity).<br/>
- Application commands (slash commands) used by staff, in particular moderation commands.<br/>
- Interactions related to opening, claiming and closing tickets.<br/>
- All members' message-sending activity, for spam-detection purposes.<br/>

The first piece of data is processed to enable the chained-words game (the last word played and its author's ID are recorded to prevent repetition) and the suggestions channel (the message is copied into an embed identifying its author, then the original message is deleted). In RP activity channels, sending a message may increase a score linked to the ID of a roleplay server owner registered on Liste du RP FR.

The second piece of data is processed to run moderation commands (`/warn`, `/mute`, `/unmute`, `/role`, etc.). Depending on the command, the targeted person's ID, the reason given and the moderator's ID are recorded in the database (for warnings) or sent to a staff-only log channel (for other moderation actions).

The third piece of data is processed to manage a ticket's lifecycle: the opener's ID and, if applicable, the staff member's ID handling it are recorded while the ticket is open. Upon closure, a full history of the channel (message content and authors' identities) is generated as a file and sent to a staff-only log channel.

The last piece of data is processed to detect spam behaviour: the Bot temporarily keeps, in memory (not in the database), the timestamps of the latest messages sent by each member, identified by their ID. A member sending more than 5 messages in under 7 seconds may automatically be muted (timed out) for 3 days.

The Bot also allows staff to act on data related to roleplay servers registered on Liste du RP FR (validating, editing, removing a listing). The processing of this data is described in the Privacy Policy of the [**Liste du RP FR**](https://github.com/Communaute-du-RP-FR/policies/blob/main/docs/privacy/liste-du-rp-fr.md) bot, with which **Moderator** shares its database.

## 3 - Retention of collected data

Some data is collected automatically and stored temporarily (cached) in anticipation of possible processing. This is the case for the data of the server on which the Bot operates (and its members), as well as the timestamps used for spam detection.

Some data is collected explicitly:<br/>
- Warnings: the targeted person's ID, the moderator's ID, the reason and the date are recorded in the database.<br/>
- The chained-words game history: each word played is linked to its author's ID.<br/>
- Moderation logs (mute, unmute, role changes, ticket opening/closing): sent as embeds to a staff-only Discord channel.<br/>
- Closed ticket transcripts: sent as a file to a staff-only Discord channel.<br/>

## 4 - Deletion of collected data

The automatically processed data that is stored is deleted as soon as its usefulness for the proper functioning of our service is no longer real.

For instance:<br/>
- A ticket's database record (opener, assigned staff) is deleted as soon as the ticket is closed. The transcript generated at that point, however, is not deleted: it remains archived in the staff log channel.<br/>
- Timestamps used for spam detection are cleared automatically once processed, and fully reset at every bot restart, with no history kept.<br/>

Other explicitly collected data is not deleted automatically:<br/>
- A warning can only be removed from the database by a staff member with administrator permissions, via the `/warns` interface.<br/>
- The chained-words game history is reset only manually by a staff member (`/game reset`).<br/>
- Moderation logs and transcripts sent to staff Discord channels follow the Discord server's own retention and can only be removed manually by staff.<br/>

This data can be completely deleted from our database upon request from the data owner, within the limits of what is necessary to maintain a legitimate moderation history.

## 5 - Contact

The User may contact **Moderator** for any request relating to the processing of this data by sending an e-mail to:
- [martin.devolder2@gmail.com](mailto:martin.devolder2@gmail.com)
- [virgile.devolder2@gmail.com](mailto:virgile.devolder2@gmail.com)
