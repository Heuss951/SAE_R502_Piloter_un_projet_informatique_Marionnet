# **SAE R502 – Piloter un projet informatique (Marionnet)**
Projet de la SAE R502 – Conception et pilotage d’un réseau informatique réalisé sous Marionnet, en appliquant une organisation Agile (Scrum).

## **Objectif du projet**
Ce dépôt a été créé dans le cadre de la SAE R502 – Piloter un projet informatique.
L’objectif principal est de :

* Concevoir une topologie réseau complète sous Marionnet
* Configurer les machines virtuelles
* Mettre en place les VLAN, le routage et les services réseau
* Piloter le projet selon la méthode Agile (Scrum)
* Documenter l’avancement et produire une soutenance finale

## **Équipe projet**
* Lahoucine El Merabet
* Keyane Lhamzi

Projet réalisé dans le cadre du
BUT Réseaux & Télécommunications – Parcours Cybersécurité
IUT de Villetaneuse – Université Sorbonne Paris Nord

## **Organisation du projet (Agile – Scrum)**
Le projet est structuré en quatre sprints :

| Sprint   | Objectif                                                    |
| -------- | ----------------------------------------------------------- |
| Sprint 1 | Création de la topologie Marionnet (machines + switchs)     |
| Sprint 2 | Configuration IP, VLAN et switchs                           |
| Sprint 3 | Mise en place des services réseau (DHCP, routage, firewall) |
| Sprint 4 | Documentation, rapport, soutenance                          |

## **Structure du dépôt**
```
/docs                 → Captures, schémas, tests réseau
/marionnet_project    → Projet Marionnet (topologie, câblage, VMs)
/rapport              → Rapport final, planning, backlog, livrables
README.md             → Documentation principale
```

## **Outils et technologies**
* Marionnet (émulation réseau)
* Debian / BusyBox (machines virtuelles)
* VLAN, trunk, routage statique
* DHCP et services réseau
* Git / GitHub (gestion de versions)
* Trello (méthode Agile – Scrum)
* Shell / Bash

## **État actuel du projet**
Topologie Marionnet :
* Machines M1 à M6 et MA à MF créées
* Switchs configurés
* Câblage logique terminé

VLAN :
* VLAN 10 : M1, M2, M3, M4, M5, M6
* VLAN 20 : MA, MB, MC, MD, ME, MF

Interconnexion :
* Liaisons entre switchs configurées en trunk

Prochaine étape :
* Configuration du routage et du DHCP

## Liens utiles
- Trello du projet : *https://trello.com/invite/b/69137cc0c72c7519468f0a30/ATTI39368d6616d92829a56b9d08e44afc1aCB427B90/kanban-sae-r502-piloter-un-projet-informatique*  
- IUT de Villetaneuse – Université Sorbonne Paris Nord  
```
