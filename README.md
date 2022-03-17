# TP_Client_Server

Le but de ce TP est de créer une application client serveur et de mettre en place un protocole de communication entre les deux entités.

## Installation des librairies python3
```sh
sudo apt install python3-numpy
sudo apt install python3-pip
sudo pip3 install pillow
```

## Install

Faire un git clone du depot git
```sh
git clone https://github.com/Mushtaaq2610/TP_Client_Server.git
```
## Protocole Utiliser
```sh
Le protocole tcp est utilise dans ce tp. Le protocole TCP/IP (Transmission Control Protocol/Internet Protocol) réunit les deux protocoles TCP et IP. Il s'agit donc d'une suite de protocoles associée au domaine d'Internet pour lequel elle facilite le transfert de données.
Présenté simplement, le protocole TCP/IP est un standard de communication entre deux processus. Il détermine et fixe les règles inhérentes à l'émission et à la réception de données sur un réseau. L'association des deux protocoles permet d'apporter des garanties de fiabilité dans le transfert des données. Avec le TCP/IP, vous êtes certain(e) que les informations envoyées arriveront bel et bien au bon destinataire.
```

## Comment executer le programme
```sh
1. Executez le fichier ServerSimple.py sur le serveur
2. Entrez le port que vous souhaite d'utiliser
3. Ensuite executez le fichier CLientSimple.py sur le client
4. Entrez la même adresse IP et le même port affiché sur le serveur
5. Puis le client et le serveur vont communiquer
6. Il faudra ecrire le type d'image qu'il veut telecharger(eg: img.jpeg)
```

## Télécharger une image sur le serveur
- img.jpeg

## code d'execution pour le fichier client
```sh
python3 ClientSimple.py
```

## code d'execution pour le fichier serveur
```sh
python3 ServerSimple.py
```

