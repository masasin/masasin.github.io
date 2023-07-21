# Yozakura
2014 &ndash; 2015, [Université de Kyoto](../education/kyoto.md)

??? summary "Résumé"

    - A servi de responsable du développement informatique pour le robot de secours téléopéré Yozakura au laboratoire de mécatronique de l'Université de Kyoto.
    - A développé un système client-serveur pour le contrôle du robot et a écrit le code pour les puces Raspberry Pi et mbed embarquées,
      y compris les pilotes pour divers contrôleurs et capteurs.
    - Le code était robuste face aux défaillances et bien documenté, fournissant des messages d'erreur utiles pour les erreurs matérielles, logicielles,
      et d'opérateur de divers types, et les corrigeant si nécessaire.

L'équipe [SHINOBI](https://github.com/kyoto-u-shinobi) du [laboratoire de mécatronique](http://www.mechatronics.me.kyoto-u.ac.jp/index.php?ml_lang=en) de l'Université de Kyoto
a conçu un nouveau robot de secours téléopéré appelé Yozakura pour participer à la [RoboCup Japan Open](http://robocup.or.jp/)
[Rescue League](https://sites.google.com/site/robocupjorescuerobotleague/) 2015 dans la ville de Fukui.
Nous avons également participé au RoboCup Japan Rescue Camp, une compétition d'entraînement qui a eu lieu à Tsuruga.

Yozakura avait des roues en forme d'étoile, des flippers, un bras robotique, et divers capteurs.

![Yozakura](../../assets/images/yozakura.jpg){: style="width:400px"}

J'étais le responsable du développement informatique pour Yozakura.
J'ai écrit un système client-serveur pour contrôler le robot depuis la station d'opération,
ainsi que des pilotes pour divers contrôleurs.
(Cela a finalement été remplacé par une interface rviz qui utilisait le même pilote de contrôleur.)

J'ai également écrit la plupart du code pour les puces Raspberry Pi et mbed embarquées,
ainsi que des pilotes I2C pour des capteurs de courant et un IMU 10-DOF,
des pilotes pour les servos [Dynamixel](https://github.com/masasin/dynamixel), les moteurs Maxon et une caméra à 360 degrés Ricoh.
J'ai également écrit du code qui permettait à la RPi et au mbed de communiquer en série.

La plupart du code était en Python, avec un peu de C++ sur le mbed.
Le code était bien documenté et consigné.
Il était également robuste face aux échecs.
Il fournissait des messages d'erreur utiles pour les erreurs matérielles, logicielles et d'opérateur de divers types ;
et les corrigeait si nécessaire.

!!! abstract "Code source"

    Le code source est disponible sur GitHub :

    - [Raspberry Pi](https://github.com/kyoto-u-shinobi/yozakura_raspi)
    - [mbed](https://github.com/kyoto-u-shinobi/yozakura_mbed)
    - [Station d'opérateur](https://github.com/kyoto-u-shinobi/yozakura_operator_station)
