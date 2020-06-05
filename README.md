# Launchpad

Launchpad est un lanceur rapide d'application sous la forme d'une page web

## A propos

Launchpad est une simple page web qui comporte des liens sous la forme de cellules arrangés en grille qui permettent d'accéder à d'autres applications.

Il s'agit essentiellement d'une grille de raccourcis vers d'autres sites et applications, l'avantage par rapport à des marque-pages c'est qu'on peut plus facilement trouver une application par son logo et sa couleur plutôt qu'à son nom.

## Installation

Pour utiliser cette application, copiez simplement ces fichiers dans un dossier servi par un serveur web, comme Nginx et Apache. Cette application est entièrement statique, pas besoin de PHP ou autre logiciel côté serveur.

Par exemple, si on a un serveur Nginx qui écoute à l'adresse https://launchpad.adapei-meuse.fr et qui sert le dossier `/var/www/html`, vous devez mettre ces fichiers dans ce dossier, de sorte à ce que à ce que https://launchpad.adapei-meuse.fr/index.html pointe sur `/var/www/html/index.html`.

## Crédits des images

Cette application inclut les logos de certaines marques, dont voici les attributions & la source des images :

- GLPI, par GLPI Project (converti en svg) : https://github.com/glpi-project/glpi/blob/9.4/bugfixes/pics/logos/logo-glpi-vector-white.eps
- Centreon, par Centreon : https://www.centreon.com/societe/ressources/
- Office 365, par Microsoft (orange modifié en blanc) : https://news.microsoft.com/ofc365_rgb_orng166/
- TeamViewer Management Console : https://login.teamviewer.com/LogOn
- FOG project, Copyright © FOG Project 2012-2020 : https://github.com/FOGProject/