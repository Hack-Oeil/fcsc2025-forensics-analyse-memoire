# FCSC 2025 Analyse mémoire 2/5 - Origine de la menace

Il y a bien un malware actif sur la machine. Nous aimerions comprendre comment l’attaquant a pu l’exécuter en mémoire. Retrouvez le processus qui a permis d’exécuter ce malware.

Le flag est au format ```FCSC{<process_name>:<process_id>}``` où :

- ```<process_name>``` est le nom du processus à l’orginie de l’exécution du malware et
- ```<process_id>``` est le numéro du processus (PID) à l’orginie de l’exécution du malwarel.


Par exemple : ```FCSC{malware.exe:42}```.


Cette épreuve fait partie d’une série à faire dans l’ordre :

- [Analyse mémoire 1/5 - Exfiltration](README_1_5.md)
- **Analyse mémoire 2/5 - Origine de la menace**
- [Analyse mémoire 3/5 - Où est le pansement ?](README_3_5.md)
- [Analyse mémoire 4/5 - Un échelon de plus dans la chaîne](README_4_5.md)
- [Analyse mémoire 5/5 - Le commencement](README_5_5.md)


Fichier : 
- [analyse-memoire.tar.xz](https://hackropole.fr/filer/fcsc2025-forensics-analyse-memoire/public_filer/analyse-memoire.tar.xz)



Auteur : haxom

Origine : [Analyse mémoire 2/5 - Origine de la menace](https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-4/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-forensics-analyse-memoire.git

> cd fcsc2025-forensics-analyse-memoire


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-4/