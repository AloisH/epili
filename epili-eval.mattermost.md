# Mattermost

## Auteur

- Loup Dallier

## Introduction

Mattermost est un logiciel de messagerie instantanée. Il peut être considéré comme une alternative à Slack.

Il supporte l'envoie de messages, les appels vocaux, le partage de fichiers, la création de salons de discussion, etc. par défaut. Certaines fonctionnalités sont extensibles grâce à des plugins.

Il propose aussi un système de tableaux qui permet de suivre des tâches et un autre de gestion de processus qui permet l'automatisation de tâches en fonction de l'avancement dans ceux-ci.

Des clients sont disponibles sur les plateformes Windows, Mac, Linux ainsi qu'Android et iOS.

Le projet était à l'origine propriétaire puis a été ouvert en 2015.

## Entreprise

Le projet est aujourd’hui maintenu par Mattermost Inc. C'est une entreprise américaine qui se consacre au développement de ce produit.

## Communauté

Mattermost ne représente que moins d'un pourcent des parts de marché dans son domaine. Cependant, les quatre principaux repositories du service regroupent plus de 30 stars sur Github, et les 2 plus importants regroupent plus de 700 contributeurs chacun.

## Modèle économique

La version Community du service est disponible gratuitement et l'éditeur propose de l'héberger gratuitement.

Des versions Professional et Enterprise sont aussi proposées sous format d'abonnement avec des fonctionnalités supplémentaires qui sont derrière une license propriétaire ainsi que du support. 

Chacune de ces versions peut également être self-hosted.

## Mise en place

Une image Docker permettant de tester l'application est disponible. Il suffit juste de la télécharger et de la lancer pour avoir une instance de Mattermost disponible, mais sans toutes les fonctionnalités qu'un véritable déploiement permet.

Pour un déploiement en production, le processus est globalement similaire. Des fichiers docker-compose sont disponibles permettant de setup les différents services et variables d'environnements nécessaires, comme le choix de l'URL par lequel le server sera accessible.

Nous arrivons sur la page de création de compte lors de la première ouverture de l'application. Une fois inscrit, l'utilisation est directement possible.

## Qualité

L'application est relativement simple d'utilisation. Certaines fonctionnalités ne sont cependant pas intégrées par défaut telle que les appels en visio. Il est possible de les ajouter en activant un plugin, ce qui se fait pas le simple clic sur un bouton, mais il faut quand même aller explorer un peu l'application pour les trouver.

## Ressenti

Mattermost est un système relativement simple à mettre en place et agréable à utiliser. Cependant, l'application peut sembler manquer de certaines fonctionnalités, en tout cas, par défaut. De plus, l'édition Community complètement Open Source peut aussi manquer de certaines possibilités pour une utilisation assez poussée comme la gestion de rôles pour les utilisateurs.

## Récapitulatif

| Mattermost        | Note sur 10 | Commentaire                                                                                                                                                                 |
| ----------------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| License           |             | MIT et Apache                                                                                                                                                               |
| Ressenti global   | 6           | Agréable à utiliser, mais manque de certaines fonctionnalités qui peuvent sembler essentielles pour ce genre de produit                                                     |
| Qualité           | 9           | Design et utilisation très semblables à Slack et donc dans les standards moderne                                                                                            |
| Installation      | 8           | La possibilité de tester très facilement l'application est agréable. Le déploiement se fait simplement comme pour le test, mais la configuration prend un peu plus de temps |
| Modèle économique | 8           | Open Source avec self-host possible, version entreprise avec des fonctionnalités supplémentaires et support disponible                                                      |

