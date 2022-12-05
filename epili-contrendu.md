# Contrendu de l'open source experience d'Alois Heloir

J'ai pu assiter lors du 8 novembre 2022 au congrés de l'open source à Paris.
Dans ce contrendu, vous aurez mon retour d'experience quant à cette événements en ce qui concerne les exposants que j'ai pu rencrontrer ainsi que les conférences auquelle j'ai assiter.
Au travers de ma journée j'ai pu recontrer une dixaine d'intervenant ainsi qu'assiter à 4 conférences.


## Conférences

Dans cette section vous allez découvrir 4 conférences sur des domaines variées tels que le cloud, les databases ou encore une étude du marché sur l'open source en france.

### Huawai: Toward digital Autonomy - From device to cloud

La premiere conférence auquel j'ai assité est celle de Huawai sur la digital autonomy,

Dans celle-ci les présentateurs commence par faire une présentation sur ce qu'est la digital anatomy.
Puis ensuite, ils font une observations sur les problèmes de l'IOT qui sont souvent dépendant du cloud et nous présente leurs solutions pour le régler nomé : Oniro

Dans la deuxime partie de la conférence, On nous a parlé des problemes du cloud qui sont les suivants :
- Le cloud ecosysteme favorisent le lock-in dans des providers
- Nous ne métrissons pas la donée qui se trouve dans ces clouds

Pour cela, ils proposent une solution open source qui a pour objectif de décrire les services proposer par les clouds et ensuite pouvoir les utiliser dans plusieurs cloud provider. Cette solution s'appelle Open Service Cloud et elle est maintenue par la Open Cloud Fondation.


### Avant-Premiere: Présentation de l'étude 2022 sur le marché de l'open source en france et en europe

Dans cette conférence, ou notre prof d'epili était présent, nous découvrons l'études du CNLL sur l'état de l'open source en france mais aussi en europe.

On y apprend que le marché de l'open source qui certes à était impacté par le covid mais qui continue sa progressions est pése désormais plus de 6 Milliards d'euros en France soit 11% du marché de l'IT. Et ce que chiffre ne fait que d'augmenter, en effet les estimations indique qu'en 2027 le marché péssera plus de 8.7 Milliards d'euros.

Les prédictions sont que l'open source va se développer dans tous les domaines mais en particulier les logiciels SAAS. Passant de 29% en 2022 à 46%

On y apprend aussi qu'il y actuellement environt 63 000 personnes employées dans l'open source et que l'on prévoit 90 000 personnes en 2027 ceux qui possent des questions sur la futures générations d'ingénieur qui est tres peu sensibiliser à l'open source.

En ce qui concerne l'europe, nous gardons le leader dans le marché mais celui ne fait que d'augmenter, de plus, il y a de plus en plus de souhait de combiner les associations du logiciel libre pour pouvoir concurrencer les états-unis.

Cette conferences m'a parti de comprendre l'enjeux majeur qu'est l'open source dans en Europe et en quoi il est important de comprendre les mecanisme qui permet d'en créer et de les utiliser.

### Présentation de la stratégie numérique responsable du groupe Smile

Cette présentation a commencé par nous présenter la société SMILE qui est l'un des plus gros acteurs de l'open source avec pres de 2000 employées. La présentatrice nous a monté tous les rachats de la société tels que Alter Way ou encore Sensio créateur de Sympony.

Ensuite la présentatrice, nous a présenté les engagements de SMILE dans le numérique responsable qui sont axer en 5 étapes :
- Autonomie stratégique
- Inclusion
- Environement
- la sécurité
- TechForGood

Au final cette présentation ressembler plus à une publicité pour SMILE plutot qu'une reelle conférence sur les enjeux du numérique responsable.

### Managing, growing, and scaling open source databases at SAAS scale

Dans cette conférence, le présentateur spécialiser dans les database nous expliquer les erreurs à éviter lorsque l'on veut utiliser des databases en production.

Il commence par un volet sécurité avec quelques conseils:
- Ne jamais donner access au compte root
- Utiliser les roles et des passwords qui changent
- Respecter la lois sur la conservations des donnees ou la RGPD
- Encrypter la base de donée en mettant un SSL/TLS mais aussi une encryption active sur la données
- S'assurer de la stability de la DB grace par exemple au connection pooler ou au load balancer

Puis sur la gestions des backup:
- S'assurer de la replication des donnees
- S'assurer de la retention des donnes
- S'assurer qu'un systeme de restoration de la donnes est mit en place et tester le regulieremnet

Pour finir, le présentateur parle de comment s'assurer que la database est bien operationel:
- Mettre un place du monitoring
- Optimiser les query
- Ne pas avoir un schéma trop gros ou qui s'update tous le temps
- Faire des backups
- S'assurer qu'au moins une personne formé sur les databases soit toujours disponible.
- Faire attentions au cloud provider qui propose des base de données qui peuvent avoir des bugs.

Au final, cette conférence était trés intéressantes mais le présentateur n'a que tres peu parler de l'open source.

## Stand

### Projeqtor

Projeqtor est un logiciel libre qui a pour but de gérer la gestions de projets.

Il a été fondé en 2009 dans le but de répondre au problématique des chefs de projets.

Il regroupe donc les fonctionnalités que l'on peut retrouver sur MsProject, Trello, Monday et autre outils de gestions mais aussi des nouvelles fonctionnalité tels que la gestions des risques et des financements.

Le logiciel est licensié sous GPL V3, il est ecrit en Php/MySql et il est disponible sur SourceForge.

Projeqtor proposent une offre payantes pour l'hébergerment de leur logiciel, le support et le dévellopement des fonctionnalités en accélerer.


### Nodea

Nodea est un logiciel low-code qui permet de generer des sites internet.

Nodea existe depuis plus de 6 ans et il est passé en open-source récamment.

L'objectif principal de leur outil est de générer des sites internets en NodeJs pour réaliser rapidement des MVP.

Nodea a commencé par utiliser le logiciel en interne pour faire de la vente de site sur mesure mais souhaite maitenant devenir un editeur de logiciel.

L'application est gratuite 1 mois avant de devenir payante.


### Zetrax

Zetrax Carbonio est un logiciel de messagerie et de collaboration open-source.
Il est intégré avec la communauté Zibra.

La societe proposent 2 versions de leur logiciel Zetrax Carbonio Community Edition et Carbonio.

La différence sont dans les fonctionalités proposé en effet la version classque n'a pas les meme limitation que la version Community.

De plus la version classique propose un support.

Cependant cela veut dire qu'uniquement la version Community est open-source sous license AGPL-3.0 License.

La société a été créé en 2017

### Baserow

Baserow est un logiciel open source de Airtable, il a pour focation d'etre un SAAS pour eviter l'usage de feuille excel.

Le logiciel existe depuis 4 ans et open source sous la license MIT

L'entreprise proposent un service freenium de support et souhaitent etendre leur offre avec un store pour pouvoir acheter des plugins.

En ce qui concerne la communauté, Baserow a un discord regroupant 25000 membres.

## Conclusion

Pour conclure, voici mon ressenti sur le congrés Open Source Experience.
Ce salon m'a permis dans un premier temps de me rendre compte de la taille du marché de l'open-source mais aussi de voir comment les entreprises utiliser l'open-source dans un but lucratif.

Il m'a aussi permis de comprendre les enjeux derriere l'open-source pour ces entreprises et me conforte dans l'idée que l'open-source est un réel enjeux pour les entreprises et qu'il est totalement réalisable de créer des entreprises entierement open source.
