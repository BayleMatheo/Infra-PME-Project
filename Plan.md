# Plan Projet Infra

## Rappel du contexte : le projet

> Ce projet a été initié parce qu'une **PME** (Petite et Moyenne Entreprise) commence ses activités et a besoin d'une infrastructure informatique efficace avec peu de ressources. La PME a besoin d'une solution rapide et évolutive, adaptée aux pratiques modernes, d'où le choix de mettre en place cette infrastructure dans le CLOUD. L'objectif principal est de créer une infrastructure informatique simple mais solide, permettant à l'entreprise de fonctionner efficacement dès le début.

## Les bénifices attendus

Les principaux bénéfices attendus de ce projet incluent
- Flexibilité et évolutivité : 
>Grâce à l'infrastructure CLOUD, l'entreprise pourra facilement ajuster ses ressources en fonction de ses besoins sans gros investissements en matériel.


- Efficacité opérationnelle : 
>Une infrastructure bien conçue et mise en place permettra à l'entreprise de commencer ses opérations  rapidement, optimisant le temps et les ressources.

- Sécurité renforcée : 
>L'installation d'un firewall et des règles d'accès strictes protégera les données de l'entreprise contre les menaces internes et externes.

- Meilleure collaboration : 
>Les serveurs dédiés pour différentes fonctions (AD/DHCP, fichiers, applicatif) faciliteront la collaboration entre les départements (Direction, Commerce, Commande, Vie d’entreprise), en offrant un accès rapide et sécurisé aux ressources.

- Évaluation et amélioration continue : 
>Le projet inclut une phase de vérification avant la mise en production, pour s'assurer que toutes les exigences sont remplies. Cela garantit que l'infrastructure est prête à soutenir les opérations de l'entreprise.

### Les exigences fonctionnelles

Infrastructure CLOUD
    
    
 Serveur général :

>Fonctionnalités :
> - AD/DHCP
> - Partage de fichiers
> - Serveur applicatif


**Sécurité**

Firewall : 
>Mise en place d'un firewall pour gérer la sécurité du réseau, incluant la segmentation par VLAN et l'ouverture de flux nécessaires.
    
Règles d'accès : 
>Définition et application de règles d'accès aux différents dossiers pour assurer la confidentialité et l'intégrité des données.

Dossiers et Accès :

DIRECTION : 
>Accès complet (R/W) pour le Chef.

COMMERCE : 
>Accès complet (R/W) pour le Chef et le Commercial, accès en lecture seule (R)pour l’Administratif.

COMMANDE : 
>Accès complet (R/W) pour le Chef,le Commercial et l’Assistant, accès enlecture seule (R) pour l’Administratif.

VIE D’ENTREPRISE : 
>Accès complet (R/W) pour 
tous sauf le Chef.

**Performance et disponibilité**

Temps de réponse : 
>S’assurer que les temps de réponse pour les services hébergés dans le CLOUD sont acceptables pour tous les utilisateurs.

Disponibilité : 
>Garantir une disponibilité de l’infrastructure de 99,9% pendant les heures de travail (9h-18h, du lundi au vendredi).

### Principaux Livrables

1. Plan d’exécution (Plan projet)
2. Schéma d’architecture
3. Serveur AD/DHCP
4. Serveur de fichiers
5. Serveur applicatif
6. Postes clients
7. Firewall et règles de sécurité
8. Documentation de l’infrastructure

### Planification

[Diagramme de Gantt](./image.png)

### Raci

| Tâche / Rôle  | Responsible | Accountable | Consulted   | Informated          |
| ------------- | ----------- | ----------- | ----------- | ------------------- |
| Analyse       | Fournisseur | Client      | Fournisseur | Client/Fournisseur  |
| Planification | Fournisseur | Client      | Fournisseur | Client/Fournisseur  |
| Realisation   | Fournisseur | Client      | Fournisseur | Client/Fournisseur  |
| Validation    | Client      | Client      | Fournisseur | Client/Fournisseur  |

### Architectture Réseaux

[Architecture Réseaux](./Archi.png)
