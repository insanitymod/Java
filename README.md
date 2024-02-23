# miniBank

## Aperçu
miniBank est une application Java simple conçue pour illustrer des fonctionnalités bancaires de base telles que la récupération d'informations sur les comptes et l'exécution de transferts de fonds (virements). L'application est structurée en utilisant les couches DAO (Data Access Object) et Service pour gérer l'accès aux données et la logique métier de manière distincte.

## Table des matières
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Fonctionnalités](#fonctionnalités)
- [Développement](#développement)
- [Licence](#licence)

## Prérequis
Assurez-vous d'avoir les éléments suivants installés sur votre système :
- Kit de développement Java (JDK)
- Environnement de développement intégré Java (IDE), tel qu'Eclipse ou IntelliJ IDEA

## Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/insanitymod/Java/tree/main/miniBank
# Utilisation
Exécutez la classe `MyApp`, et elle lancera la méthode `testVirement`, illustrant un scénario de transfert de fonds basique.

# Fonctionnalités
## Méthode `testVirement`
1. **Récupérer les comptes** : Récupère deux comptes (`c1` et `c2`) en utilisant un `CompteDao` simulé.
2. **Afficher les valeurs des comptes (À faire en TP)** : Affiche les valeurs de `c1` et `c2` avant le transfert de fonds.
3. **Effectuer le virement** : Initie un transfert de fonds de 25,0 du compte 1 au compte 2 en utilisant le `ServiceComptes`.
4. **Afficher les valeurs des comptes (À faire en TP)** : Affiche les valeurs de `c1` et `c2` après le transfert de fonds.
5. **Gestion des erreurs (Phase 2)** : Implémentez des blocs try/catch pour gérer les transferts de fonds autorisés et non autorisés.

# Développement
Cette application sert de point de départ pour apprendre et pratiquer les concepts de programmation Java, en particulier ceux liés à l'accès aux données, aux services et à la gestion des exceptions.

# Licence
Ce projet est sous licence open source - consultez le fichier [LICENSE](LICENSE) pour plus de détails.
