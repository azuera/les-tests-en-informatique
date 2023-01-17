# TEST INFORMATIQUE

### Définition :

- **Un test est un ensemble de cas à tester (état de l'objet à tester avant exécution du test, actions ou données en entrée, valeurs ou observations attendues, et état de l'objet après exécution), éventuellement accompagné d'une procédure d'exécution (séquence d'actions à exécuter). Il est lié à un objectif.**

- **Def smoke test : Un test de fumée (Smoke test) consiste en des tests fonctionnels ou unitaires de fonctions logicielles critiques. Les tests de fumée viennent avant d'autres tests approfondis. Un test de fumée répond aux questions comme :**

  - Est-ce que le programme démarre correctement ?
  - Est-ce que les boutons de contrôle principaux fonctionnent ?
  - Pouvez-vous enregistrer un nouveau compte d'utilisateur de test vierge ?

  **Si cette fonctionnalité de base échoue, il est inutile d'investir du temps dans un travail plus détaillé à ce stade.**

- **Def cas nominal : c'est le cas où tout fonctionne, le cas attendu**
- **Def cas d'erreurs : Le cas où l'on attend une erreur, pour empecher certains résultats**

- les boîtes blanches : Dans la théorie des systèmes, une boîte blanche (de l'anglais white box), ou boîte transparente, est un module d'un système dont on peut prévoir le fonctionnement interne car on connaît les caractéristiques de fonctionnement de l'ensemble des éléments qui le composent.

- les boîtes grises : Dans un test en boîte grise, on ignore la structure interne de l'application à tester, tandis que dans un test de boîte blanche on a accès à la structure interne de l'application. Un testeur de boîte grise connaît partiellement la structure interne : il a accès à la documentation des structures de données internes ainsi qu'aux algorithmes utilisés.

- les boîtes noires : Le test de la boîte noire, ou test de la boîte opaque, est utilisé en programmation informatique et en génie logiciel pour tester un programme en vérifiant que les sorties obtenues sont bien celles prévues pour des entrées données.

## LES CLASSIFICATIONS

---

### Classification selon la nature de l'objet :

- Test unitaire : En programmation informatique, le test unitaire (ou « T.U. », ou « U.T. » en anglais) est une procédure permettant de vérifier le bon fonctionnement d'une partie précise d'un logiciel ou d'une portion d'un programme

- Test d'intégration : le test d'intégration est une phase de teste vérifiant le bon fonctionnement d'une partie précise d'un logiciel ou d'une portion d'un programme ;dans le test d’intégration, chacun des modules indépendants du logiciel est assemblé et testé dans l’ensemble.

- Test système : Test du système signifie tester le système dans son ensemble. Tous les modules / composants sont intégrés afin de vérifier si le système fonctionne comme prévu ou non.

- Test d'acceptation : En informatique, le test d'acceptation (ou recette) est une phase de développement des projets, visant à assurer formellement que le produit est conforme aux spécifications (réponse donnée à un instant « t » aux attentes formulées).

### Classification selon l'accessibilité de la structure de l'objet :

- Technique de conception de test par boîte blanche (white box) :
- Technique de conception de test par boîte noire (black box) :

### Classification selon la propriété de l'objet :

- Test fonctionnel : Les tests fonctionnels sont définis comme une méthode permettant de tester la fonctionnalité d’une application logicielle. Le plus souvent, les tests fonctionnels sont utilisés pour vérifier des scénarios ou des modèles d’utilisation de bout en bout. Les tests fonctionnels peuvent aller du simple chargement de page et des scénarios de « happy path » jusqu’aux critères d’acceptation complets. Des documents d’exigences détaillés (qui peuvent inclure des cas d’utilisation, des user cases ou des scénarios) sont souvent nécessaires pour comprendre pleinement ce qui doit être testé. L’exécution des tests fonctionnels peut prendre plus de temps que celle des tests unitaires et peut impliquer l’utilisation de dépendances externes.

---

- Test performance : il s'agit d'un test au cours duquel on va mesurer les performances de l'application soumise à une charge d'utilisateurs. Les informations recueillies concernent les temps de réponse utilisateurs, les temps de réponse réseau et les temps de traitement d’une requête sur le(s) serveur(s). La nuance avec le type précédent réside dans le fait qu'on ne cherche pas ici à valider les performances pour la charge attendue en production, mais plutôt vérifier les performances intrinsèques à différents niveaux de charge d'utilisateurs.

---

- Test d'intrusion : Un test d'intrusion (« penetration test » ou « pentest », en anglais) est une méthode d'évaluation (« audit », en anglais) de la sécurité d'un système d'information ou d'un réseau informatique ; il est réalisé par un testeur (« pentester », en anglais). La méthode consiste généralement à analyser l'infrastructure d'un réseau informatique, afin de simuler l'attaque d'un utilisateur mal intentionné, voire d'un logiciel malveillant (« malware »).

---

- Test utilisateur :
  Un test utilisateur, ou test d’utilisabilité, est une méthode permettant d'évaluer un produit en le faisant tester par des utilisateurs. Elle est considérée comme une démarche indispensable dans la conception de produit, car la plus efficace pour évaluer l'ergonomie d'une application ou d'un site web. Il permet d’observer directement la façon dont l’utilisateur se sert d’une application et ainsi identifier concrètement les véritables difficultés qu’il rencontre, aussi appelées problèmes d'utilisabilité. L'utilisateur doit suivre des scénarios d’utilisation construits afin de vérifier les hypothèses identifiées précédemment. Ces scénarios correspondent généralement à des tâches typiques de l’utilisateur.

---

## ACTIVITÉS DE TEST

---

- Plannification :
- Analyse et conception des test :
- Implémentation et éxécution :
- Évalutation des critères de sortie et communication :
- Clôture :

## Outils

- PHP unit/ atoum
- JavaScript Unit Testing :

## SOURCES

- https://fr.wikipedia.org/wiki/Test_(informatique)
- https://mobiskill.fr/blog/conseils-emploi-tech/tests-unitaires-vs-tests-fonctionnels-quelles-differences/
- https://developer.mozilla.org/fr/docs/Glossary/Smoke_Test
