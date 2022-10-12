---
sidebar_position: 1
---

# Ouvrir le launcher

Au sein de POLYAERO, nous utilisons le logiciel de réalité virtuelle SkyReal.

![logoSkyReal](/img/manuel-vr-user/open-launcher/logo_SKR.png)

Il vous faut donc ouvrir le logiciel avec la version executable `SkyReal.exe`.

Voici la la fênetre que vous devriez obtenir à la l'ouverture du logiciel :
![Logiciel](/img/manuel-vr-user/open-launcher/luncherEmpty.png)

## Vérification de la licence

Le logiciel a besoin d'avoir une licence active. On peut savoir si la licence est active ou non via le circle de couleur situé à coté du bouton `Licencing` (_rouge = inactive et vert = active_).

![LicenceOff](/img/manuel-vr-user/open-launcher/licenceOff.png) ![LicenceOn](/img/manuel-vr-user/open-launcher/licenceOn.png)

Seuls certains ordinateurs sont équipés de licence :

- GMP-AERO-SGL01 (_ordinateur portable_)
- GMP-AERO-SGL02 (_ordinateur portable_)
- GMP-AERO-SGL03 (_ordinateur portable_)
- GMP-AERO-SGL04 (_ordinateur portable_)
- GMP-AERO-SGL05 (_ordinateur portable_)
- PC-CAVE (_ordinateur fixe_)
- PC-MASTER (_ordinateur fixe_)

Dans le cas où un de ces ordinateurs n'a pas sa licence d'activée merci de prendre contact avec Nicolas BORDIN ou Cédric BAGOT

## Vérification de la detection du casque

Au sein de POLYAERO, il y a 4 casques de réalité virtuelle différent :

- HTC VIVE standard
- HTC VIVE cosmos
- META Quest 2
- VARJO XR-3

Cependant le fonctionnement des casques cités précédemment se fait via la plateforme :

- OCULUS -> _pour le META Quest 2_
- StreamVR -> _pour le HTC VIVE standard, le HTC VIVE cosmos et le VARJO XR-3_

A noter que :

- pour le HTC Vive cosmos, il est demandé en plus de lancer le logiciel VIVEPORT
- pour le VARJO XR-3, il est demandé d'ouvrir VARJO Base et de désactivé le OpenXR.

Afin de savoir si le casque est connecté, on peut le voir juste en dessous du bouton `Licencing` (_rouge = aucun casque detecté et vert + plateforme = casque détecté_).

![HMDOff](/img/manuel-vr-user/open-launcher/hmdOff.png) ![SteamVR](/img/manuel-vr-user/open-launcher/steamVR.png) ![Oculus](/img/manuel-vr-user/open-launcher/oculusHMD.png)

## La bibliothèque

Au démarrage de SkyReal, la page par défaut est la bibliothèque. Vous retrouverez toutes les expériences que vous avez déjà ouvertes avec SkyReal.

![librarySKR](/img/manuel-vr-user/open-launcher/librarySKR.png)

### Ajouter une nouvelle simulation

Le gros bouton d'ajout vous permet de choisir n'importe quelle simulation.
Un fois qu'un CAO a été converti en simulation avec SkyPrep, le fichier à charger dans SkyReal est : `[SimulationName]\SkyReal\cooked\Simulation.umap`

![librarySKRadd](/img/manuel-vr-user/open-launcher/librarySKRadd.png)

### Trier les simulations

Par défault, la bibliothèque affiche les simulation dans des étiquettes, mais vous pouvez choisir de les afficher sous forme de liste pour obtenir plus de détails.

![librarySKRsorting](/img/manuel-vr-user/open-launcher/librarySKRsorting.png)

Vous pouvez trier les cartes par :

- les plus récentes,
- les plus utilises,
- Date de préparation,
- Nom,
- Chemin d'accès (_path_)

### Ouvrir une simulation

![librarySKRopen](/img/manuel-vr-user/open-launcher/librarySKRopen.png)

**Play Loccally** : Démarrez la simulation sur cet ordinateur uniquement.

**Create Session** : Démarrez une session collaborative de SkyReal. Vous hébergez le serveur, d'autres utilisateurs peuvent rejoindre votre session en utilisant la même carte.

**Join Session** : Rejoignez une session existante sur le réseau. Vous devez entrez l'adresse IP de la session. (_Vous devez avoir exactement la même simulation_)

![librarySKRjsIP](/img/manuel-vr-user/open-launcher/librarySKRjsIP.png)
