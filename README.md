 Solidity Auction Project – Blockchain Specialization
Ce projet est un contrat intelligent écrit en Solidity dans le cadre du cours Smart Contracts, dispensé par l'Université de Buffalo 
(The State University of New York) via la plateforme Coursera.

 À propos du cours
Ce cours fait partie de la spécialisation Blockchain et est enseigné par Bina Ramamurthy, professeure en informatique et chercheuse en systèmes distribués.
Elle est reconnue pour son expertise dans les technologies blockchain et l’enseignement des contrats intelligents.

 Fichier principal
Auction.sol : Contrat d'enchères permettant à plusieurs utilisateurs de miser des jetons sur des objets et de révéler les gagnants.

 Fonctionnalités du contrat
- Enregistrement des enchérisseurs (`register`)
- Mise de jetons sur des objets (`bid`)
- Révélation des gagnants (`revealWinners`)
- Sécurité renforcée avec `modifier onlyOwner`

 Tests réalisés
- Enregistrement de 4 enchérisseurs
- Mises sur différents objets
- Vérification des jetons restants
- Révélation des gagnants avec contrôle d'accès

 Comment tester le contrat dans Remix
1. Ouvrir [Remix IDE](https://remix.ethereum.org)
2. Importer le fichier Auction.sol
3. Compiler avec Solidity 0.4.17
4. Déployer avec le compte 0
5. Utiliser  register() avec les comptes 1 à 4
6. Utiliser  bid()` pour miser des jetons
7. Appeler   revealWinners() avec le compte 0
8. Vérifier les gagnants avec winners(0), winners(1), winners(2)
   
[Démo Remix](remix-demo.png)

 Technologies utilisées
- Solidity 0.4.17
- Remix IDE
- Ethereum Virtual Machine (EVM)

 Contexte académique
Ce projet a été réalisé dans le cadre du module Meilleures pratiques du cours sur les contrats intelligents. Il illustre la conception, le déploiement et l’exécution de contrats intelligents dans un environnement sécurisé et transparent.

 Auteur du dépôt
- Nom : Mike Alladoum
- Pays : Togo 🇹🇬
- LinkedIn : https://www.linkedin.com/in/mike-alladoum-a557102a1?  
  
- Projet réalisé 14/09/2025


