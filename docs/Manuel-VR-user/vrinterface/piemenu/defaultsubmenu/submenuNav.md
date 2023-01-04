---
sidebar_position: 6
---

# Sous menu du navigation

Dans ce sous-menu, les commandes vous permettent de choisir votre style de mouvement, ainsi que de créer et de naviguer dans les vues de votre simulation.

![submenuNavigation](\img\manuel-vr-user\vrinterface\piemenu\navigationDefault.png)

## ![Fly](\img\manuel-vr-user\manip-pc\icons\fly.png) Fly

La navigation Fly est le mode de navigation le plus liber. Dans ce mode, l'utilisateur n'est pas attaché au sol.

- Pour avancer, poussez le pavé de navigation vers l'avant et pointez le laser dans la direction souhaitée (_Remarque : si le laser est incliné vers le bas, l'utilisateur descendra ; si le laser est incliné vers le haut, l'utilisateur montera_).
- Pour vous déplacer latéralement, poussez le pavé de navigation vers la gauche ou vers la droite. L'utilisateur se déplacera sur le coté dans la direction sur laquelle il appuie.
- Pour faire demi-tour en VR, faites un angle de 90 degrés entre le ccontrôleur et le pavé de navigation vers l'avant/l'arrière.

## ![Footprrints](\img\manuel-vr-user\manip-pc\icons\footprints.png) Walk

La navigation Walk **attache l'utilisateur au sol** et améliore l'immersion de l'utilisateur dans la simulation.

- Pour avancer, poussez le pavé de navigation vers l'avant et pointez le laser dans la direction où vous voulez aller.
- Pour vous déplacer latéralement, poussez le pavé de navigation vers la gauche ou vers la droite. L'utilisateur se déplacera sur le côté dans la direction sur laquelle il appuie.
- Pour faire demi-tour en VR, faites un angle de 90 degrés entre le contrôleur et la tête (gauche ou droite) et poussez le pavé de navigation vers l'avant/l'arrière.
- Si l'utilisateur a un obstacle sur son chemin, il sera bloqué jusqu'à ce qu'il se déplace dans l'autre sens.
- Tous les obstacles ne bloqueront pas l'utilisateur : il pourra franchir des obstacles praticables (c'est-à-dire des obstacles d'une hauteur inférieure à 20 cm).

## ![Teleport](\img\manuel-vr-user\manip-pc\icons\teleport.png) Teleport

La navigation par téléportation est utile pour **les utilisateurs ayant des problèmes avec le mal des transports**. Il y a un petit délai avant que la commande soit prête pour éviter les téléportations accidentelles.

- Poussez le pavé de navigation dans n'importe quelle direction. Cela vous donnera la direction dans laquelle vous regardez une fois téléporté.
- Utilisez votre manette pour déplacer l'endroit où vous souhaitez vous téléporter.
- Relâchez le pavé de navigation pour vous téléporter à la position et à l'orientation que vous avez sélectionnées.

## ![SetSpeed](\img\manuel-vr-user\manip-pc\icons\speed.png) Set Speed

Lorsqu'elle est activée, cette commande permet à l'utilisateur de définir la vitesse à laquelle il se déplace en VR.

## ![Minimap](\img\manuel-vr-user\manip-pc\icons\miniMapIcon.png) Mini map

![Minimap](\img\manuel-vr-user\vrinterface\piemenu\minimap.png)

Cette commande crée un modèle réduit dynamique (MiniMap) de la simulation devant vous. Vous êtes le seul à le voir.

La MiniMap peut vous aider à savoir où vous et vos collaborateurs vous situez dans la simulation. Il vous permet également de vous téléporter auprès de vos collaborateurs (et vice-versa).

### Plan

Lorsque vous lancez cette commande, la MiniMap apparaît devant vous. Le lancement peut prendre quelques instants (~ 0,5 s), selon la taille de votre simulation. Il y a deux parties à distinguer :

- Le côté gauche (1) est un cylindre d'affichage dans lequel le modèle réduit de la simulation est rendu. Votre position et celle de tous les utilisateurs actuellement en collaboration avec vous sont affichées en temps réel par un MiniPawn.
- Le côté droit (2) est une plaque sur laquelle vous visualisez tous les MiniPions des utilisateurs actuellement en collab. Vous êtes le plus gros pion, en haut.

### Fonctionnalités de base

Survolez un minipion (n'importe où dans la minicarte) pour afficher le nom de l'utilisateur associé.

Cliquez sur un MiniPion pour le sélectionner. Le nom du MiniPion sélectionné reste sur une étiquette sur le côté droit. En dessous de ce libellé, vous pouvez effectuer certaines actions à l'aide des boutons :

- **Afficher dans MiniMap** : centrez la MiniMap sur ce MiniPion. La minicarte continuera de se concentrer dessus jusqu'à ce que vous choisissiez un autre minipion ou que vous déplaciez la minicarte par vous-même.
- **Téléporter le MiniPion** : après avoir cliqué sur ce bouton, cliquez n'importe où dans le cylindre d'affichage pour téléporter le MiniPion sélectionné à l'emplacement sur lequel vous avez cliqué.
- **Téléporter vers** : vous téléporte vers le MiniPion sélectionné.
- **Inviter** : téléportez le MiniPion sélectionné à votre emplacement.

Sur le côté gauche, vous pouvez voir quelques boutons plus petits (1.1). Survolez-les pour les agrandir. Selon les paramètres douaniers que vous choisissez, vous pouvez :

- **Basculer MiniMap Opaque / Transparent** : il est plus facile de visualiser où vous et les autres vous trouvez, nous sommes avec une MiniMap opaque.
- **Basculer l'orientation relative / nord** : avec l'orientation relative, l'orientation de la minicarte correspondra à l'orientation de votre pion (cela semble plus naturel). Avec l'orientation Nord, la MiniMap restera orientée dans la même direction.
- **Basculer la vue grande/locale** : la vue grande montre toute la simulation dans la minicarte, tandis que la vue locale montre une vue plus proche de votre pion.

### Fonctionnalités avancées

Il y a un autre petit bouton sous le cylindre d'affichage. Cliquez et maintenez-le enfoncé pour déplacer toute la MiniMap (1 & 2) sur votre écran.

La hauteur du cylindre d'affichage peut être modifiée en saisissant la partie orange à l'arrière.

Le cylindre d'affichage peut être tourné en saisissant l'anneau orange.

Cliquez et maintenez sur le cylindre d'affichage pour **déplacer la MiniMap**. Le focus sur le MiniPion sélectionné s'arrêtera.

Cliquez et maintenez avec les deux mains sur le cylindre d'affichage pour **faire pivoter et redimensionner** la MiniMap.

### Paramètres personnalisés

_Is Mesh Number Dynamic_ : Si vous rencontrez des problèmes de performances avec la MiniMap, vous pouvez vérifier ceci. Il ajustera le nombre de mailles rendues en fonction de votre FPS.

_Is Default Orientation Relative_ (recommandé) : cochez cette case pour démarrer la minicarte avec une orientation relative.

_Show Orientation Button_ : cochez cette case pour afficher un bouton permettant à l'utilisateur de basculer entre les orientations de minicarte relative et fixe.

_Show Transparent Button_ : cochez cette case pour afficher un bouton permettant à l'utilisateur de basculer entre une mini-carte opaque et une mini-carte transparente.

_Show Collab Disk_ (recommandé) : cochez cette case pour accéder aux commandes de la mini-carte collaborative. Le Collab Disk (2) est nécessaire pour effectuer des actions liées à vous et à vos collaborateurs (téléportation, focus). Cependant, si vous ne souhaitez pas l'afficher, vous pouvez décocher cette option.

## ![addView](\img\manuel-vr-user\manip-pc\icons\viewAdd.png) Create view

Lorsque vous utilisez cette commande, elle crée une vue à votre emplacement actuel et orientée de sorte que la nouvelle vue corresponde à ce que vous voyez actuellement dans le casque VR.

## ![ViewChange](\img\manuel-vr-user\manip-pc\icons\viewChange.png) Navigate to view

L'utilisation de cette commande vous permettra de choisir une vue vers laquelle naviguer à partir d'une liste de vues existantes. Une fois que vous avez sélectionné la vue souhaitée, vous y serez transporté.

Ces deux commandes peuvent également être utilisées à partir de l'onglet Caméra par défaut du menu de commandes 2D.
