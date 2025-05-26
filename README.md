# keyboards-made-external

## État d'avancement

Les claviers sont identifiés.
La difficulté est dans le pas de 0,8mm de 2 des nappes les plus intéressantes.
Pour les autres, j'ai commandé un autre fer à souder pour être plus à l'aise et des breadboard pour prototyper. Commande en cours sur Amazon. ça arrivera le jeudi 29 mai 2025.

Idée : je pourrais voir s'il y a quelque chose de récupérable sur les cartes mères des PC dont proviennent les petits claviers ?

### Prochaines étapes

* [ ] Acheter le matériel nécessaire
* [ ] Acheter plus de matériel pour m'entrainer avant de souder les headers du teensy ...
* [ ] Ensuite, continuer à l'étape 9 du tutoriel principal.
* [x] Refaire la liste des articles et tutoriels sur lesquels je me base. là je recommence à zéro, c'est tellement de temps de perdu :(
* [x] Comparer le pas de k02 et k03 aux connecteurs FFC de 1 mm.
* [x] Commencer un projet github pour centraliser les notes et mettre des photos

## Documentation

* Sûrement le meilleur tutoriel à l'heure actuelle : <https://www.instructables.com/How-to-Make-a-USB-Laptop-Keyboard-Controller/>
* avec son github associé : <https://github.com/thedalles77/USB_Laptop_Keyboard_Controller>

## Matériel nécessaire

* Adaptateur FFC 30 pins de 0,8 mm vers headers classiques (pour k01)
* Adaptateur FFC 24 pins de 0,8 mm vers headers classiques (pour k03)

## Lexique

* FFC : Flexible Flat Cable : en gros, un cable sous forme de nappe plate.
* FPC : Flexible Printed Circuit : ça peut désigner des circuits électroniques sur une surface flexible.

## Liste des claviers

### k01

![Photo de face de k01](images/k01.jpg)

Ce clavier possède 2 nappes FFC/FPC : l'une pour les frappes clavier, et l'autre pour le rétroéclairage.

Avantages :

* rétroéclairage
* dimensions habituelles (largeur) facilitant la prise en main
* pavé numérique

Ce qui en fait un candidat idéal pour faire un clavier USB nomade ☺️

#### Première nappe de k01

![Première nappe de k01](images/k01_pins.jpg)

30 pins (dont 2 inutiles) avec un pas de 0,8 mm.

⚠️ les connecteurs FFC avec un pas de 0,8 mm sont beaucoup moins courant !

##### Seconde nappe de k01

![Seconde nappe de k01](images/k01_pins2.jpg)

4 pins avec un pas de 1 mm.

### k02

![Photo de face de k02](images/k02.jpg)

Clavier récupéré sur un vieil ordinateur portable de petite taille.

Le clavier est assez compact, réduit en largeur, donc il sera peut-être plus difficile de s'y habituer.
Mais l'avantage c'est qu'il sera assez facilement transportable.

#### Nappe de k02

![Nappe de k02](images/k02_pins.jpg)

25 pins (⁉️) avec un pas de 1 mm.

### k03

![Photo de face de k03](images/k03.jpg)

Clavier récupéré sur un vieil ordinateur portable de petite taille.

Le clavier est assez compact, réduit en largeur, donc il sera peut-être plus difficile de s'y habituer.
Mais l'avantage c'est qu'il sera assez facilement transportable.

J'aime mieux les touches de direction de k02 par rapport à k03.

#### Nappe de k03

![Nappe de k03](images/k03_pins.jpg)

24 pins avec un pas de 0,8 mm.