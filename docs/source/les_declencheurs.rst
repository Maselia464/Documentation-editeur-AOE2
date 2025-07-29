Les déclencheurs – Notions de base
==================================

Un **déclencheur** est un événement qui va exécuter une ou plusieurs **actions** automatiquement, en boucle ou une seule fois, **lorsque certaines conditions sont remplies**.

---

🔧 Fonctionnement général
-------------------------

Le système de déclencheurs d’**Age of Empires II: Definitive Edition** est intégré directement dans l’éditeur de scénario. Il permet de créer des enchaînements **condition → effet** sans écrire une seule ligne de code.

🖱️ L’interface est entièrement **graphique**, accessible à tous, même sans aucune compétence en programmation.

Exemple :  
> *"Si un villageois entre dans une zone, alors un château apparaît."*

---

📌 Structure minimale d’un déclencheur
--------------------------------------

Un déclencheur contient :

- **Un effet** *(obligatoire)* : c’est l’action à exécuter (ex. : créer un objet, modifier un attribut, déclencher un son...).
- **Une ou plusieurs conditions** *(optionnelles)* : elles déterminent si l’effet doit être exécuté (ex. : un joueur possède un bâtiment, une unité entre dans une zone...).

⚠️ Un déclencheur sans effet **ne fera rien**, même si les conditions sont remplies cependant il y a un cas d'usage de posséder une condition sans effet.

---

🚀 Pour aller plus loin : le scripting XS
-----------------------------------------

Bien que l’éditeur soit visuel, il est possible d’aller plus loin en utilisant le **langage XS** (eXtended Scripting), notamment pour des actions plus complexes :  
- Calculs dynamiques ;
- Boucles personnalisées ;
- Modication de groupe d'unité 

📄 Un chapitre dédié abordera les bases de XS plus loin dans cette documentation.

---

📚 Origine des exemples
-----------------------

Les exemples présentés ici proviennent en grande partie des questions posées sur :

- Le Discord **AoE2 – Communauté FR**
- Le Discord **UGC**
- Des utilisateurs de **AoE2ScenarioParser**

🎯 L’objectif est de **couvrir tous les cas d’usage de base** que vous rencontrerez lors de la création de vos scénarios.

---

🔜 Prochaines sections :
- La detection de sanglier sous un forum
