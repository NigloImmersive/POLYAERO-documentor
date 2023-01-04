---
sidebar_position: 8
---

# Sous menu de produit

Dans ce sous-menu, les commandes permettent de modifier certains paramètres relatifs à la position de vos objets, ainsi que d'afficher des informations sur les objets.

![submenuProduct](\img\manuel-vr-user\vrinterface\piemenu\productDefault.png)

## ![Reset](\img\manuel-vr-user\manip-pc\icons\reset.png) Reset parts position

Lorsqu'elle est utilisée, cette commande réinitialisera la position de tous les objets sélectionnés à leur position d'origine (c'est-à-dire celle dans laquelle ils se trouvaient lorsque vous avez lancé la simulation SkyReal).

⚠ Si aucun objet n'est sélectionné lors de l'activation de cette commande, les positions de TOUS les objets de la simulation seront réinitialisées.

## ![Resize](\img\manuel-vr-user\manip-pc\icons\scale.png) Resize

⚠ Cette commande ne sera utilisable que si vous avez sélectionné un ou plusieurs objets.

Lorsqu'elle est activée, cette commande vous permettra de redimensionner les objets sélectionnés à l'aide du contrôleur.

## ![SnappointAdd](\img\manuel-vr-user\manip-pc\icons\snapPointsAdd.png) Create snap point

⚠ Cette commande ne sera utilisable que si vous avez sélectionné un ou plusieurs objets.

Lorsqu'elle est utilisée, cette commande crée une entité pour chaque objet sélectionné à son emplacement actuel. Une fois les entités créées, si vous déplacez l'un des objets pour lesquels vous avez créé une entité, vous verrez qu'une version "fantôme" verte de l'objet que vous venez de déplacer reste à l'emplacement d'origine de l'objet. C'est la fonctionnalité.

Si vous souhaitez remettre l'objet dans sa position d'origine, amenez-le simplement près de l'entité et, si cela est fait correctement, il devrait revenir à sa position d'origine. Vous pouvez modifier l'angle de seuil et les positions d'accrochage dans l'onglet Fonction du menu Commande.

## ![SnappointRemove](\img\manuel-vr-user\manip-pc\icons\snapPointsRemoveAll.png) Remove snap point

⚠ Cette commande ne sera utilisable que si vous avez sélectionné un ou plusieurs objets.

Lorsqu'elle est utilisée, cette commande supprimera les fonctionnalités des objets sélectionnés.

## ![CuttingBoxCollab](\img\manuel-vr-user\manip-pc\icons\cuttingBoxCollab.png) Collab cuting box

Lorsque vous activez la commande, appuyez sur la gâchette pour définir un coin de la boîte, puis maintenez la gâchette et déplacez votre contrôleur pour créer le volume souhaité. Lorsque vous relâchez la gâchette, la Cutting Box apparaîtra.

Cette box est collaborative : vos collaborateurs la verront.

Tout le monde peut interagir avec : la boîte peut être sélectionnée, déplacée, redimensionnée et sa couleur peut être changée par tous les utilisateurs de la simulation.

Lorsque la commande Cutting Box est activée, vous pouvez générer autant de boîtes que vous le souhaitez. Les boîtes générées resteront à la sortie de la commande.

![CuttingBoxCollab](\img\manuel-vr-user\vrinterface\piemenu\cuttingCubeView.png)

## ![CuttingPlane](\img\manuel-vr-user\manip-pc\icons\cuttingPlane.png) Local cutting plane

Cette commande crée un plan de coupe infini attaché à votre contrôleur. Lorsque vous quittez la commande, l'avion disparaîtra.

Cet avion n'est pas collaboratif : vos collaborateurs ne le verront pas.

Vous pouvez choisir la distance du plan au contrôleur dans les paramètres personnalisés de la commande.

⚠ Ce plan de coupe (1) ne coupera jamais le sol sous vous (2).

![CuttingPlane](\img\manuel-vr-user\vrinterface\piemenu\cuttingPlaneView.png)

## ![PartInfo](\img\manuel-vr-user\manip-pc\icons\partInfo.png) Part information

Lorsqu'elle est utilisée, cette commande vous permettra d'écrire le nouveau nom de la pièce sélectionnée.

⚠ Si plusieurs pièces sont sélectionnées, elles auront le même nom d'affichage.
