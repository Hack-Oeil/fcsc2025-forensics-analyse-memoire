# FCSC 2025 Analyse mémoire 3/5 - Où est le pansement ?

Le processus à l’origine du malware parait légitime. L’attaquant a certainement dû le modifier pour injecter son code et exécuter sa chaine de compromission. Retrouvez le Thread malveillant. À partir de là, retrouvez l’adresse virtuelle de la PTE modifiée par l’attaquant.

Le flag est au format ```FCSC{<thread_id>:<virtual_address>}``` où :

- ```<thread_id>``` est l’identifiant du ```Thread``` (TID) malveillant et
- ```<virtual_address>``` est l’adresse virtuelle (dans le contexte du processus malveillant) du début de la page mémoire (PTE) modifiée.


Par exemple : ```FCSC{420:0x0022446688aaccee}```.



Cette épreuve fait partie d’une série à faire dans l’ordre :

- [Analyse mémoire 1/5 - Exfiltration](README_1_5.md)
- [Analyse mémoire 2/5 - Origine de la menace](README_2_5.md)
- **Analyse mémoire 3/5 - Où est le pansement ?**
- [Analyse mémoire 4/5 - Un échelon de plus dans la chaîne](README_4_5.md)
- [Analyse mémoire 5/5 - Le commencement](README_5_5.md)


Fichier : 
- [analyse-memoire.tar.xz](https://hackropole.fr/filer/fcsc2025-forensics-analyse-memoire/public_filer/analyse-memoire.tar.xz)



Auteur : haxom

Origine : [Analyse mémoire 3/5 - Où est le pansement ?](https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-5/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-forensics-analyse-memoire.git

> cd fcsc2025-forensics-analyse-memoire


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-5/