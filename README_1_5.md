# FCSC 2025 Analyse mémoire 1/5 - Exfiltration

Un agent du FCSC démarre son ordinateur pour réfléchir et noter des idées de challenges pour l’année prochaine. Il nous a cependant alerté que lors du démarrage, un étrange écran rouge est apparu à peine une seconde, puis le poste a démarré normalement.

Il a pu commencé son travail sans souci, mais afin de s’assurer que le problème ne vienne pas d’un potentiel malware, nous lui avons fait capturer la mémoire du poste avec l’outil DumpIt. Analysez la mémoire et retrouvez le malware qui tente d’exfiltrer le document :

- le processus exécutant le malware
- l’adresse et le port du serveur contrôlé par l’attaquant
Le flag est au format ```FCSC{<process_name>:<process_id>:<adresse_ip_distante>:<port_distant>:<protocole utilisé>}``` où :

- ```<process_name>``` est le nom du processus exécutant le malware,
- ```<process_id>``` est le numéro du processus (PID) exécutant le malware,
- ```<adresse_ip_distante>``` est l’adresse IP du serveur controlé par l’attaquant,
- ```<port_distant>``` est le port utilisé sur le serveur controlé par l’attaquant et
- ```<protocole utilisé>``` est le protocole utilisé pour la communication avec le serveur de l’attaquant (```TCP``` ou ```UDP```).


Par exemple :``` FCSC{malware.exe:512:51.255.68.182:21:UDP}```.


Cette épreuve fait partie d’une série à faire dans l’ordre :

- **Analyse mémoire 1/5 - Exfiltration**
- [Analyse mémoire 2/5 - Origine de la menace](README_2_5.md)
- [Analyse mémoire 3/5 - Où est le pansement ?](README_3_5.md)
- [Analyse mémoire 4/5 - Un échelon de plus dans la chaîne](README_4_5.md)
- [Analyse mémoire 5/5 - Le commencement](README_5_5.md)


Fichier : 
- [analyse-memoire.tar.xz](https://hackropole.fr/filer/fcsc2025-forensics-analyse-memoire/public_filer/analyse-memoire.tar.xz)



Auteur : haxom

Origine : [Analyse mémoire 1/5 - Exfiltration](https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-3/)



-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-forensics-analyse-memoire.git

> cd fcsc2025-forensics-analyse-memoire


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2025-forensics-analyse-memoire-3/