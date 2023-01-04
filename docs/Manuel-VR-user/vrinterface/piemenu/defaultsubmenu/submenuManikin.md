---
sidebar_position: 5
---

# Sous menu du mannequin

Dans SkyReal, vous pouvez activer une fonction de mannequin pour vous-même et/ou d'autres personnes connectées à votre simulation.

Vous trouverez cette commande dans le sous-menu par défaut du mannequin :

![submenuManikin](\img\manuel-vr-user\vrinterface\piemenu\manikinDefault.png)

## Editer un mannequin

Cette commande propose deux options :

- Création d'un nouveau mannequin : sans aucun mannequin sélectionné, la commande lancerait "créer un mannequin" dans le bracelet.
- Modification d'un mannequin : si vous sélectionnez un mannequin avant la commande, la commande lancera l'option "créer un mannequin" dans le bracelet.

### Créer un mannequin

![CreateManikin](\img\manuel-vr-user\vrinterface\piemenu\createManikin.png)

#### Workflow de la création de mannequin

Pour créer un nouveau mannequin , cliquez sur le bouton "Créer un mannequin" , cela masquera votre bracelet et fera apparaître un mannequin dans votre pointeur lasez :

- Cliquez un fois pour placer le mannequin dans l'environnement
- Cliquez une deuxième fois pour définir l'orientation du mannequin.

Le mannequin est maintenant créé.

#### Option de création de mannequin

Vous pouvez personnaliser la création préalable du mannequin. Les options disponibles sont les suivantes :

- **Sélectionner une posture** :
  Par défaut, le mannequin apparaîtra dans une position debout normale, vous pouver également sélectionner des position assise ou allongée.
- **Remplacer la hauteur du mannequin** :
  Chaque mannequin a sa propre hauteur établie, si vous avez besoin de définir une hauteur particulière, vous pouvez activer cette option en cliquant sur le bouton de commutation pour configer une nouvelle de mannequin.
- **Activer le MSD** :
  Vous pouvez activer cette option pour afficher le MSD sur le mannequin (conformément à la norme RULA).
- **Incarner après création** :
  Vous pouvez activer cette option pour incarner le mannequin après avoir décidé de sa position et son orientation. Lorsque vous êtes satisfait de la position vous pouvez appuyer sur le troisième fois sur le bouton de déclenchement pour mettre fin à l'incatnation du mannequin et revenir à votre position d'origine.

### Editer un mannequin

![EditManikinDefault](\img\manuel-vr-user\vrinterface\piemenu\editManikindefault.png)

### Option du mannequin

- **Posture** :
  Vous pouvez modifier la posture du mannequin entre la position debout, assise ou couchée.
- **Bouton générer un rapport MSD** :
  Il génère automatiquement un rapport de score MSD de la pose du mannequin. Actuellement, le résultat est un fichier json que vous pouvez exploiter pour créer vos propres rapports.
- **Bouton dupliquer le mannequin** :
  Cliquez sur ce bouton pour masquer votre bracelet et générer une copie exacte du mannequin sélectionné dans votre pointeur laser. Vous pouvez ensuite placer le nouveau mannequin dans n'importe quelle position dans l'espace.
- **Bouton incarner le mannequin** :
  En cliquant sur ce bouton, vous incarnerez automatiquement le mannequin sélecrtionné. Pendant qye vous incarnez le mannequin, vous pouvez vous déplacer librement pour adopter la posture souhaitée.
- **Bouton supprimer le mannequin** :
  Ce bouton supprimera le mannequin sélectionné.

### Manipulation du mannequin

![EffortdManikin](\img\manuel-vr-user\vrinterface\piemenu\effortdManikin.png)

Lorqu'un mannequin est sélectionné, vous pouvez voir tous ses effecteurs représentés par des sphères bleues. Ces effecteurs ont la possibilité d'être sélectionnés, déplacés ou tournés avec votre pointeur laser. Pour déplacer rapidement un effectuer, vous pouvez sélectionner avec le bouton de déclenchement et tout en maintenant le bouton enfoncé, placer l'effectuer dans la position souhaitée. Vous pouvez également faire pivoter l'effecteur en déplaçant votre main en conséquence.

Lorsqu'un effecteur e'st sélectionné, il affichera un ensemble de propriétés dans le bracelet :

![EffectorBracelet](\img\manuel-vr-user\vrinterface\piemenu\effectorBracelet.png)

**Etat de l'effecteur** : il affiche unr liste d'états effecteurs, chaque effecteur peut avoir six états différents

1. **Free**
   La position et la rotation de l'effecteur sont contrôlées par l'utilisateur. Lorsque les effecteurs des mains sont sélectionnées, celà active les options :

   - Options d'effecteur
   - Point effecteur vers

2. **Simulated**
   Il suivrait tout mouvement qui lui est lié, à l'exception de l'entrée de l'utilisateur.

3. **Snap to Actor**
   Lorsque cette option est sélectionnée, vous pouvez choisir un objet à attacher à l'effecteur. Si cet objet bouge l'effecteur suivra. Si l'effecteur bouge, l'objet restera static.

4. **Locked local**
   L'effecteur est gelé localement, si vous déplacez le mannequin, l'effecteur ne suivera pas mais restera gelé.

5. **Locked world**
   L'effecteur est gelé en position et en rotation si le mannequin se déplace, l'effecteur restera à sa position.

6. **Disable**
   L'effecteur est désactivé (il devient gris) et il se place dans sa position par défaut.

**Options d'effecteur** : Existe pour les effecteurs des mains uniquement.
Cela ouvrirait les options de la boîte combinée de l'effecteur des mains avec 2 états de main:

- Hand grip
- Finger grip
  où vous avez la possibilité d'ouvrir/fermer/écarter la main ou le doigt du mannequin.

La troisième option **_Auto grip_** permet à la main de se mettre dans une position particulière lorsqu'elle est liée à un objet avec des prises prédéfinies.

![EffectorHandBracelet](\img\manuel-vr-user\vrinterface\piemenu\effectorHandBracelet.png)

**Point effector to** : Existe uniquement pour les effecteurs des mains.
Lorsqu'il est cliqué, l'utilisateur aura la possibilité de sélectionner n'importe quel objet dans la scène et l'effecteur va être lié à celui-ci.

## Modifier moi-même

La commande modifier Myself permettra à l'utilisateur de configuer son propre mannequin.

![MySelf](\img\manuel-vr-user\vrinterface\piemenu\myselfDefault.png)

- **Aparence**
  Cliquez sur cette option pour ouvrir la liste des mannequins disponibles parmi lesquels choisir. En survolant avec votre pointeur laser, vous pouvez voir les informations et les propriétés de chaque mannequin. Cliquer sur un mannequin particulier transformera l'avatar de l'utilisateur en celui sélectionné. Les utilisateurs auront également la possibilité de choisir deux types de robots comme avatar.
- **Edit MSDs**
  Ce bouton donne accès à tous les paramètres des Trouble Musculo-Squelettique (MSD). Ce paramètre s'applique automatiquement lorsqu'il est sélectionné dans l'avatar de l'utilisateur. Tous les autres utilisateurs de la scène verront ces paramètres.
