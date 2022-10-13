---
sidebar_position: 5
---

# Onglet de commande d'enregistrement

Dans ce sous-menu, vous pouvez enregistrer et exporter votre carte.

![InterfaceDesktopSave](/img/manuel-vr-user/manip-pc/intDeskSave.png)

Les commandes d'enregistrement et de chargement vous permettent d'enregistrer les modifications que vous apportez à votre simulation en créant différentes sauvegardes entre lesquelles vous pouvez basculer. Ils sont utiles si vous souhaitez apporter des modifications à votre simulation tout en conservant les anciennes versions qui existaient avant d'effectuer ces modifications.

La commande "Save for Back to CAD" vous permt d'exporter les modifications que vous avez apportées vers un format CAO. Il est utile si vous souhaitez alterner entre l'utilisation d'un logiciel de CAO et SkyReal pour travailler sur votre produit et votre produit, et vous permet d'exporter des conceptions et des transformations que vous avez faites en VR.

Ces commandes sont accessibles à partir de l'onget "Save" dans les commandes 2D par défaut.

## ![Save](/img/manuel-vr-user/manip-pc/icons/save.png) Save

Lorsqu'elle est utilisée, cette commande enregistrera votre expérience dans son état actuel. Toutes les modifications apportées aux pièces (position, rotation, échelle et apparence) seront enregistrées. De plus, toutes les mesures, annotations, conceptions (sphère, cube, câbles et tuyaux), symboles 3D ou mannequins statiques seront également enregistrés.

Cette sauvegarde sera chargée automatiquement au démarage.

## ![Load](/img/manuel-vr-user/manip-pc/icons/load.png) Reload last save

Chargement de la dernière sauvegarde pour remplacer vos dernières modifications.

## ![SaveCAD](/img/manuel-vr-user/manip-pc/icons/saveCAD.png) Save for back to CAD

Lorsqu'elle est utilisée, cette commande exporte un fichier .json contenant des informations sur la simulation, notamment :

- Transformations de pièces : toute modification de position, de rotation et d'échelle.
- Conceptions : tous les cube, tuyaux, câbles ou sphères qui ont été créés dans la simulation.
  Ce fichier se trouve à la racine du dossier de simulation.

Une fois que vous avez utilisé la commande, vous pouvez ouvrir votre CAO avec CATIA et la mettre à jour avec le fichier .json créé.

## ![SaveConfig](/img/manuel-vr-user/manip-pc/icons/saveConfig.png) Save/load configuration

Une configuration est une spécifique de votre maquette avec laquelle vous souhaitez travailler pendant votre session. Vous pouvez créer autant de configurations que vous le souhaitez.

Vous pouvez créer, charger et modifier des configurations à partir du panneau de droite.
