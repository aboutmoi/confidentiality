# Oollen — Politique de confidentialité

*Dernière mise à jour : 3 octobre 2026*

Oollen est une application iPhone qui affiche l'indice pollen de votre commune, publié par Atmo France et les associations agréées de surveillance de la qualité de l'air (AASQA), et qui vous permet de noter chaque jour comment vous vous sentez. Cette page décrit, sans détour, les données que l'application traite, pourquoi, combien de temps, et ce que vous pouvez en faire.

En résumé : pas de publicité, pas de traceur, pas de revente. Les données servent à votre propre suivi et à rien d'autre.

## Qui est responsable

Le responsable du traitement est **Baptiste Leclercq**, éditeur de l'application Oollen.

Contact pour toute question relative à vos données : **support@ooples.fr**.

## Les données traitées

| Donnée | D'où elle vient | À quoi elle sert |
|---|---|---|
| Identifiant de compte Apple (identifiant technique fourni par « Se connecter avec Apple ») | Apple, à la connexion | Reconnaître votre compte d'une connexion à l'autre |
| Adresse e-mail (le plus souvent une adresse de relais anonyme fournie par Apple si vous avez choisi de masquer la vôtre) | Apple, à la première connexion | Identifier le compte ; elle n'est ni affichée ni utilisée pour vous écrire |
| Prénom | Vous, à l'inscription (ou Apple si vous l'avez partagé) | Vous saluer dans l'application |
| Commune suivie (code INSEE et nom) | Vous, par recherche ou géolocalisation | Afficher ses indices pollen et vous envoyer les alertes qui la concernent |
| Réglages d'alerte (alertes activées ou non, niveau de déclenchement) | Vous, dans les réglages | Décider si et quand une notification vous est envoyée |
| Check-ins quotidiens : date et ressenti (de « très bien » à « très gêné »), accompagnés de l'indice pollen de votre commune ce jour-là | Vous, depuis le tableau de bord | Vous montrer l'évolution de votre ressenti dans l'onglet Analyses |
| Jeton de notification de l'appareil (jeton APNs), état de l'autorisation de notification | Votre iPhone | Vous délivrer les notifications ; ne pas en envoyer si vous les avez refusées |
| Adresse IP | Votre connexion, à chaque requête | Sécurité du service : limitation des tentatives de connexion, journaux techniques |

**Position géographique.** L'application ne la demande que si vous touchez « Utiliser ma position », pour retrouver votre commune. Les coordonnées sont envoyées une fois à notre serveur pour cette recherche et **ne sont pas enregistrées dans votre compte** ; comme toute requête, elles peuvent figurer quelques jours dans les journaux techniques du serveur, puis sont effacées. L'application ne suit jamais vos déplacements et ne demande pas l'accès à la position en arrière-plan.

**Âge, taille et poids.** Les versions antérieures d'Oollen (jusqu'à la 2.0) proposaient, à titre facultatif, de renseigner ces trois informations. Elles n'ont jamais servi à aucun traitement et **ne sont plus demandées**. Celles qui ont été saisies restent attachées au compte jusqu'à sa suppression ; vous pouvez en demander l'effacement immédiat à l'adresse de contact.

**Données de santé.** Votre ressenti quotidien est une information sur votre état de santé. Il n'est utilisé que pour votre propre suivi, dans l'application, et n'est jamais croisé avec d'autres données, partagé ou analysé à d'autres fins.

## Ce que nous ne faisons pas

- Aucun outil de mesure d'audience, aucun traceur publicitaire, aucun SDK tiers de suivi.
- Aucune vente, location ou cession de données.
- Aucune prospection : l'adresse e-mail n'est pas utilisée pour vous écrire.
- Aucun profilage ni décision automatisée.

## Fondements juridiques

- **Exécution du service** que vous avez demandé en créant un compte : identifiant, e-mail, prénom, commune, réglages, check-ins, jeton de notification.
- **Votre consentement**, que vous donnez ou refusez dans les réglages d'iOS, pour la position et les notifications. Vous pouvez le retirer à tout moment, sans conséquence sur le reste de l'application.
- **Notre intérêt légitime** à sécuriser le service : adresse IP dans les journaux techniques.

## Durées de conservation

| Donnée | Durée |
|---|---|
| Compte, prénom, e-mail, commune, réglages, jeton de notification | Tant que le compte existe ; effacés dès la suppression du compte |
| Check-ins | Tant que le compte existe sur le serveur ; les 90 derniers jours sur votre iPhone |
| Position géographique | Jamais enregistrée dans le compte ; au plus quelques jours dans les journaux techniques |
| Sauvegardes de la base de données | 7 jours glissants, puis effacement automatique |
| Journaux techniques du serveur | Durée limitée, rotation automatique (de l'ordre de quelques jours à quelques semaines) |

## Où sont les données

Les données sont enregistrées sur votre iPhone et sur un serveur hébergé par **OVH** en **France**, administré par l'éditeur. Les échanges entre l'application et le serveur sont chiffrés (HTTPS).

Trois prestataires interviennent, chacun pour une fonction précise :

- **Apple** — connexion avec Apple et acheminement des notifications (APNs). Apple reçoit le jeton de votre appareil et le contenu des notifications (commune et niveau de pollen).
- **Cloudflare** — protection et acheminement du trafic vers notre serveur. Cloudflare voit l'adresse IP de votre connexion.
- **OVH** — hébergement du serveur et de ses sauvegardes.

Les indices pollen proviennent d'**Atmo France / AASQA** (données ouvertes, licence ODbL). C'est notre serveur qui les interroge ; votre iPhone ne contacte jamais Atmo France directement et aucune donnée vous concernant ne leur est transmise.

## Vos droits

Vous disposez des droits d'accès, de rectification, d'effacement, de limitation, d'opposition et de portabilité prévus par le Règlement général sur la protection des données (RGPD) et la loi Informatique et Libertés.

- **Supprimer votre compte et toutes vos données** : dans l'application, *Réglages → Confidentialité → Supprimer mon compte et mes données* (ou *Réglages → Supprimer mon compte*). La suppression est immédiate sur le serveur et sur l'iPhone, et irréversible.
- **Changer de commune, modifier ou couper les alertes** : directement dans l'application.
- **Retirer l'accès à la position ou aux notifications** : dans les Réglages d'iOS, rubrique Oollen.
- **Toute autre demande** (accès à l'ensemble de vos données, rectification, effacement de données anciennes comme l'âge, la taille ou le poids) : écrivez à **support@ooples.fr**. Nous répondons dans un délai d'un mois.

Si vous estimez que vos droits ne sont pas respectés, vous pouvez saisir la CNIL (www.cnil.fr).

## Mineurs

Oollen n'est pas destinée aux enfants de moins de 15 ans. Nous ne collectons pas sciemment de données les concernant ; si c'était le cas, écrivez-nous et elles seront supprimées.

## Ce qu'Oollen n'est pas

Oollen est un outil d'information. Les indices affichés sont calculés à l'échelle d'une commune et ne remplacent ni un diagnostic ni l'avis d'un médecin ou d'un allergologue.

## Modifications

Cette politique peut évoluer avec l'application. La date en tête de page indique la dernière version ; les changements notables seront signalés dans l'application.
