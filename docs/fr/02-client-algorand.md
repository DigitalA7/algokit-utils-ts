# 2. Client Algorand et configuration

L’API publique expose notamment AlgorandClient et Config. Le client centralise la configuration réseau et fournit un point d’entrée cohérent pour les opérations d’une application.

Une DApp doit choisir explicitement le réseau ciblé, le SDK Algorand compatible et les paramètres de nœud. Le README distingue les générations v7 et v8 selon la version d’algosdk retenue : ce choix doit rester aligné avec les dépendances du projet.

La configuration devient ainsi une frontière importante entre développement local, testnet et production.

[Chapitre suivant : transactions et contrats](03-transactions-contrats.md)
