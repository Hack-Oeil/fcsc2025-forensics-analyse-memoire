# FCSC 2025 Analyse mémoire 5/5 - Le commencement

Le ```Device``` que vous avez retrouvé nous confirme que l’attaquant s’est injecté assez tôt dans la séquence de démarrage. Le démarrage ```UEFI``` et le ```SecureBoot``` étaient pourtant bien activés sur le poste. Pour s’en assurer, nous avons récupéré les métadonnées de la partition EFI du démarrage Windows (partition FAT32) grâce à l’outil [DFIR-Orc](https://dfir-orc.github.io/). Voir le fichier ```analyse-memoire-efi-fatinfo.csv```. Retrouvez la vulnérabilité qui a été exploitée par l’attaquant et le fichier contenant la charge malveillante initiale à l’attaque.

Le flag est au format ```FCSC{<CVE_number>:<file_name>}``` où :

- ```<CVE_number>``` est l’identifiant de la CVE exploitée et
- ```<file_name>``` est le nom du fichier contenant la charge malveillante initiale.

Par exemple : ```FCSC{CVE-2022-4225:payload.bin}```.




Cette épreuve fait partie d’une série à faire dans l’ordre :

- [Analyse mémoire 1/5 - Exfiltration](README_1_5.md)
- [Analyse mémoire 2/5 - Origine de la menace](README_2_5.md)
- [Analyse mémoire 3/5 - Où est le pansement ?](README_3_5.md)
- [Analyse mémoire 4/5 - Un échelon de plus dans la chaîne](README_4_5.md)
- **Analyse mémoire 5/5 - Le commencement**


Fichier : 
- [analyse-memoire.tar.xz](https://hackropole.fr/filer/fcsc2025-forensics-analyse-memoire/public_filer/analyse-memoire.tar.xz)
- [analyse-memoire-efi-fatinfo.csv](analyse-memoire-efi-fatinfo.csv)


Auteur : haxom

Origine : [Analyse mémoire 5/5 - Le commencement](https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-7/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-forensics-analyse-memoire.git

> cd fcsc2025-forensics-analyse-memoire


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-7/