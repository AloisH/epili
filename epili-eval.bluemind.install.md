# BlueMind - Installation

Indications permettant d'installer le logiciel BlueMind sur une VM Ubuntu 22.04

## Installation de BlueMind

Aller sur la [page de téléchargement de BlueMind](https://download.bluemind.net/bm-download/) et récupérer un lien de téléchargement pour Ubuntu 22.04   
Exécuter les commandes ci-dessous :

```
su -
apt-get update && apt install curl
wget <lien_telechargement>
locale-gen en_US.utf8
curl https://pkg.bluemind.net/bluemind-deb.asc | apt-key add -
add-apt-repository universe
apt update
apt upgrade
sh bluemind-installer-4.1.64887-jammy.bin
```
Suivre les consignes indiquées par la suite
