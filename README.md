[![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black)](https://ciscotracer.wordpress.com/)

# TP-CISCO-CLEAR

## Auteurs

* **Alexandrus Brutus** _alias_ [@Alexandruuuus](https://github.com/Alexandruuuus)

## Contenu

Tu retrouveras dans ce repo, l'ensemble des configurations des équipements par TP.

Les scripts sont identifiés par phases. S'il y a un espace, c'est qu'une action est requise pour valider (soit par un "yes", soit par une action manuelle).

La solution aux TP est toujours donnée pour comparer les versions.

Le tableau ci-dessous te permettra de faire du troubleshooting et de vérifier tes informations.

### Commandes utiles à retenir pour ces TP CISCO :

| Commande                           | Description                                                                                 |
|---------------------------         |---------------------------------------------------------------------------------------------|
| show ip ospf neighbor              | Affiche les voisins OSPF détectés sur le routeur, leur état et les interfaces associées.     |
| show ip ospf                       | Donne une vue d'ensemble de la configuration OSPF, y compris les zones et les routes apprises. |
| show crypto map                    | Vérifie les configurations de mappage crypto, y compris les pairs, les transform-sets et les ACL. |
| show crypto ipsec sa               | Affiche les statistiques et l'état des associations de sécurité (SA) pour les tunnels IPsec. |
| show running-config                | Montre la configuration en cours d'exécution du routeur (utile pour valider la config actuelle). |
| wr                                 | Sauvegarde la configuration en cours d'exécution dans la configuration de démarrage.        |
| copy running-config startup-config | Sauvegarde explicitement la configuration en cours dans la mémoire non volatile.         |
| traceroute <adresse IP>            | Identifie le chemin emprunté par les paquets pour atteindre une destination donnée.         |
| show version                       | Affiche les informations sur le matériel, le logiciel et les licences du routeur.          |
| show ip route                      | Montre les routes apprises dynamiquement (via OSPF, par exemple) ou configurées statiquement. |

