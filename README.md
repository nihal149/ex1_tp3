

Application de Gestion de Produits - Hibernate  

Cette application Java permet de gérer des produits en utilisant Hibernate comme ORM et MySQLcomme base de données. L’objectif est d’implémenter les opérations CRUD (Create, Read, Update, Delete) et de manipuler des données via une interface Java connectée à une base de données relationnelle.

---

Fonctionnalités 
- Ajouter des produits dans la base de données.  
- Afficher la liste complète des produits.  
- Rechercher un produit par son identifiant.  
- Modifier les informations d’un produit existant.  
- Supprimer un produit.  
- Afficher les produits dont le prix est supérieur à 100 DH.  
- Afficher les produits commandés entre deux dates fournies par l'utilisateur.  

---

Technologies Utilisées 
-Java 8+ 
-Hibernate ORM (JPA)  
- MySQL  
- NetBeans 

---

Installation et Configuration
1. Créer la base de données MySQL nommée `H1`.  
2. Ajouter les bibliothèques nécessaires :  
   - Hibernate Core et JPA.  
   - Driver JDBC MySQL (`mysql-connector-java`).  
3. Configurer le fichier `hibernate.cfg.xml` avec les informations de connexion à la base de données.  
4. Implémenter les classes d’entité et de service pour la gestion des produits.  

---

Exécution du Programme  
- Créez au moins 5 produits.  
- Affichez tous les produits disponibles.  
- Recherchez un produit par ID = 2.  
- Supprimez le produit avec ID = 3.  
- Modifiez les informations du produit avec ID = 1.  
- Affichez les produits avec un prix supérieur à 100 DH.  
- Affichez les produits commandés entre deux dates fournies au clavier.

---

