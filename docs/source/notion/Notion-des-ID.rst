La notion des ID
================

📌 **Définition d’un ID :**

Le terme *ID* vient de l’anglais *identifier*, soit un identifiant unique.  
Selon **Wikipédia**, un identifiant est utilisé pour repérer de manière unique un élément dans un système :  
- en **programmation**, pour distinguer les objets ou lignes d’une base de données,  
- en **électronique**, pour désigner un courant dans un transistor (*anecdote technique*),  
- ou encore comme abréviation du mot latin *idem*, signifiant « le même ».

---

Pourquoi les ID sont-ils importants dans l’éditeur ?
-----------------------------------------------------

Parce que **l’éditeur de scénarios d’Age of Empires II utilise des identifiants pour tout.**  
Chaque élément du jeu possède un ou plusieurs ID :

- 🧍 **Unités**
- 🏰 **Bâtiments**
- 💰 **Ressources**
- 🧱 **Objets placés sur la carte**
- ⚔️ **Groupes d’unités**
- 🏛️ **Architectures visuelles**
- 🧠 **Effets personnalisés via XS ou scripts Python**

---

Visualiser les ID dans l’éditeur
--------------------------------

Vous pouvez voir certains ID directement dans l’éditeur, notamment dans les effets suivants :

- **Créer un objet**
- **Modifier un attribut**
- **Définir une unité ou un bâtiment précis**

.. image:: image/id_visuel.png
   :alt: Visualisation des ID via un effet
   :width: 891px
   :align: center
---

Groupes d’unités
----------------

Certaines catégories du jeu possèdent des **ID de groupe**. Par exemple :

- Toutes les unités d’**infanterie** appartiennent au groupe `901`.
- Les unités de **cavalerie** ou d’**archerie** ont aussi leurs propres ID de groupe.

Cela permet de **filtrer ou affecter des effets à des familles entières d’unités**, sans devoir toutes les sélectionner individuellement.

---

ID d’apparence (Architecture)
-----------------------------

L’apparence d’un bâtiment change selon la **civilisation** ou le **type d’architecture** :

- Une caserne asiatique n’a pas le même ID qu’une caserne européenne ou mésoaméricaine.
- Ces ID permettent de créer des **effets de transformation visuelle**, ou de personnaliser les civilisations dans vos scénarios.

---

ID de référence des objets placés
---------------------------------

Chaque élément que vous **placez sur la carte** (ex: maison, marché, moulin…) se voit attribuer un **ID de référence unique**, appelé parfois *reference_id*.

Cela permet, notamment avec des outils avancés comme **AoE2ScenarioParser**, de :

- Suivre un objet précis
- Le modifier dynamiquement
- Créer des effets ciblés sans ambiguïté

🎯 *Important* : si vous n’utilisez pas d’outils de script, cette notion est **moins essentielle**, mais utile à connaître pour gagner en précision.

---

Quand les ID deviennent essentiels
----------------------------------

Les ID sont **indispensables** si vous voulez :

- Créer des mécaniques complexes (ex: changement de skin, évolution d’un objet, effets dynamiques)
- Faire du **tracking** d’unité (suivre un héros sur la carte)
- Utiliser des **scripts XS**
- Automatiser via des outils comme **AoE2ScenarioParser** (Python)

.. image:: image/util_avance_a.png
   :alt: Exemple d’utilisation avancée des ID, ici j'impose que toute les unités d'infanterie du jeu on 500 PV pour le joueur 1
   :width: 1126px
   :align: center

.. image:: image/id_B.png
   :alt: Demonstration du résultat au démarage de la partie
   :width: 891px
   :align: center


.. image:: image/id_c.png
   :alt: Demonstration du résultat au démarage de la partie
   :width: 891px
   :align: center


.. image:: image/id_d.png
   :alt: Demonstration du résultat au démarage de la partie
   :width: 891px
   :align: center


.. image:: image/id_e.png
   :alt: Demonstration du résultat au démarage de la partie
   :width: 891px
   :align: center


.. image:: image/id_f.png
   :alt: Demonstration du résultat au démarage de la partie
   :width: 891px
   :align: center
---

Vous voilà désormais informé du fonctionnement des ID dans Age of Empires II: Definitive Edition.
Cette notion constitue une étape essentielle pour passer du statut de créateur débutant à celui de créateur avancé.

Les ID sont indispensables non seulement pour modifier les attributs des éléments du jeu, mais aussi pour récupérer certaines informations clés dans votre scénario.



🔗 **Aller plus loin** :  
:doc:`Voir comment visualiser et manipuler les ID <visualiser_id>`
