# FCSC 2025 Analyse mémoire 4/5 - Un échelon de plus dans la chaîne

Suite à votre analyse, nos équipes ont décidé de réinstaller complètement le système d’exploitation sur la machine afin de la nettoyer. Cependant, une fois le système réinstallé, le même malware que vous avez trouvé est toujours présent et continue de communiquer avec le C2 de l’attaquant. Nous pensons donc qu’une persistance plus profonde est présente sur le poste de notre utilisateur et supposons qu’un ```Device``` est enregistré pour se pré-positionner pendant le démarrage du système.

Le flag est au format ```FCSC{<device_name>}``` où :

- ```<device_name>``` est le nom du ```Device``` malveillant.

Par exemple : ```FCSC{MaSuperSourisVirtuelle}```.




Cette épreuve fait partie d’une série à faire dans l’ordre :

- [Analyse mémoire 1/5 - Exfiltration](README_1_5.md)
- [Analyse mémoire 2/5 - Origine de la menace](README_2_5.md)
- [Analyse mémoire 3/5 - Où est le pansement ?](README_3_5.md)
- **Analyse mémoire 4/5 - Un échelon de plus dans la chaîne**
- [Analyse mémoire 5/5 - Le commencement](README_5_5.md)


Fichier : 
- [analyse-memoire.tar.xz](https://hackropole.fr/filer/fcsc2025-forensics-analyse-memoire/public_filer/analyse-memoire.tar.xz)



Auteur : haxom

Origine : [Analyse mémoire 4/5 - Un échelon de plus dans la chaîne](https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-6/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-forensics-analyse-memoire.git

> cd fcsc2025-forensics-analyse-memoire


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-6/