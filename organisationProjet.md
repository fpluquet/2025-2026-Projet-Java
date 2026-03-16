# UE2202 -- Laboratoire de programmation
## Organisation du projet

**Professeur: F. Pluquet**

Le projet sera implémenté en langage Java et l'environnement de développement qui sera utilisé est `IntelliJ`. Nous utiliserons la méthodologie Scrum pour organiser au mieux votre travail et votre équipe.

À partir de la semaine du 16/03/2026, toutes les séances de laboratoire seront entièrement dédiées au projet. Ces séances offriront des plages horaires communes à tous les membres d'un groupe, facilitant l'organisation du travail. Elles permettront également de suivre l'avancement des projets et de répondre à vos éventuelles questions.

## Organisation et conditions du travail

Nous avons décidé d'embaucher les bénévoles que vous êtes pour réaliser un projet. Chaque projet sera réalisé par des groupes de 6 développeurs.

### Méthodologie
Nous allons travailler avec la méthodologie Scrum, avec des sprints d'une semaine. Pour chaque sprint, un livrable précis sera produit. Il sera à rendre sur un dépôt Git en ligne que le professeur vous aura attribué.

### Gestion de versions
Les groupes doivent obligatoirement utiliser le système de contrôle de versions Git qui leur permet de gérer l'évolution du code source de leur application. Tout au long du projet, ce dépôt sera utilisé pour évaluer le travail et les progrès de chaque groupe d'étudiants.

### Contraintes de temps
Les livrables à rendre pour chaque sprint doivent être déposés avant l'échéance imposée. Puisque l'un des objectifs du projet consiste à apprendre à respecter les échéances imposées lors d'un projet de développement logiciel, tout retard sera lourdement pénalisé. Il est à noter que si les livrables ne nous sont pas fournis à temps pour un sprint, les notes du groupe pour cette dernière seront **nulles** (sans recours possible). Si cela arrive une deuxième fois, la note finale du groupe sera alors **nulle** (sans recours possible non plus).

### Contraintes de présence
La présence aux laboratoires organisés dans le cadre du projet sont obligatoires. Toute absence non justifiée sera sanctionnée sur la note finale.

### Composition des groupes
Nous vous laissons le soin de former vos groupes de 6 étudiants.

Pendant le projet, la composition des groupes est susceptible d'être changée à tout moment! Des membres de groupes peuvent être échangés ou en ajouter dans le but de restructurer les groupes.

**En cas de problème dans votre groupe (quelqu'un ne vient jamais aux rendez-vous, ne travaille pas, ou autre), vous essayez d'abord de gérer cela en interne. La gestion d'un groupe peut prendre du temps et vous devez être proactifs pour cela. Si cela n'est pas gérable en interne, vous pouvez contacter le professeur, afin de prendre une décision définitive.**

### Suivi hebdomadaire individuel

Chaque semaine, le professeur se réserve le droit d'interroger **n'importe quel étudiant** sur sa compréhension du code actuel du projet, qu'il en soit l'auteur ou non. Tout membre du groupe est censé connaître et comprendre l'entièreté du code produit par son équipe. Si un étudiant est dans l'incapacité de répondre de manière satisfaisante, il pourra être **exclu du groupe** par le professeur.

La participation de chaque étudiant sur le dépôt Git sera également évaluée **chaque semaine**. Un étudiant qui ne contribue pas activement au dépôt (commits, ...) pourra lui aussi être **exclu du groupe**.

### Exigences de qualité
Les fonctionnalités, la complétude et la qualité du code produit et des tests unitaires peuvent être évaluées par les enseignants après l'échéance imposée pour chaque étape-clé. La couverture du code par des tests unitaires pourra également être évaluée.

### Travail en groupe
Tous les étudiants d'un groupe travailleront **collectivement** pour raffiner les *User Stories* afin de réaliser un projet cohérent. Chaque membre du groupe travaillera sur la conception et l'implémentation en `Java` de l'application. Chaque étudiant devra travailler avec ses **propres identifiants Git** afin d'évaluer la part personnelle de chacun si nécessaire.

## Livrables

Pour chaque sprint, nous vous demanderons de nous fournir :

- **avant 23h59 le la veille (mercredi ou jeudi) clôturant le sprint**, tous les livrables définis plus bas sur le *repository* mis à votre disposition.
- **avant 23h59 le lendemain (vendredi ou samedi) commençant le sprint**, les User Stories du nouveau sprint en tenant compte des remarques (s'il y en a) du professeur que vous auriez reçues.

Les exigences fonctionnelles et non-fonctionnelles de l'application seront établies grâce aux "User Stories" que vous établirez en posant des questions à votre client (votre professeur). Chaque groupe travaillera **collectivement** pour raffiner les *User Stories*. Chaque groupe, de manière individuelle, classera les user stories selon leur ordre d'importance (P1, P2 et P3) et les risques (R1, R2 et R3). L'ensemble des exigences devrait former un tout cohérent.

La conception de l'application peut être modélisée en utilisant le langage de modélisation `UML 2` mais aucune documentation UML ne vous est explicitement demandée durant le projet.

Chaque groupe doit travailler individuellement à l'implémentation. Le plagiat sera lourdement pénalisé et peut mener à un échec total pour le cours ou même pour l'année d'études (cf. règlement d'études de la HELHa).

Les tests unitaires doivent être utilisés durant toute la phase d'implémentation. Nous imposerons une approche de développement dirigé par les tests : l'écriture du code doit être alternée avec l'écriture des tests, et tous les tests doivent passer avant de progresser dans l'écriture du code. Une autre bonne pratique est l'utilisation de *regression testing*. Pour chaque erreur rencontrée (ou bug), un test unitaire doit être écrit qui met en évidence l'erreur. Vous n'aurez ainsi pas à comprendre et résoudre deux fois le même problème.

Nous exigeons un code et des tests de qualité pour l'application, comme cela est détaillé en section [Critères d'évaluation](#critères-dévaluation).

**Livrables par sprint : histoires, code source, tests unitaires et autres documents**

Les éléments à rendre sont :

- Le code source Java. Cela inclut :
    - La documentation pour les programmeurs, au format Javadoc. La Javadoc doit contenir une documentation complète pour le projet; les packages; les classes, interfaces et énumérations; les méthodes publiques principales;
    - Les tests unitaires;
- Un document qui décrit :
    - le suivi de planification du projet : a-t-on implémenté toutes les fonctionnalités, comment les difficultés techniques ont-elles été contournées ? ...
    - la motivation des choix pris lors de la conception : design patterns principaux, ...
- Un fichier actualisé, au format XLS ou Markdown (.md), qui reprend la répartition des tâches développeur pour les sprints effectuées;
- Les histoires actualisées en termes du contenu et estimation des points au format XLS ou Markdown (.md);
- Le fichier exécutable `.jar` contenant la version du code que vous présenterez pendant la démonstration.

Tous ces livrables devront être stockés dans la branche `master` du dépôt Git correspondant à votre groupe.

## Contact

Les laboratoires sont le moment principal de communication entre votre client et votre équipe. Durant les autres moments, si vous avez une question d'ordre fonctionnelle, non fonctionnelle ou technique, vous pouvez m'envoyer une demande via Teams.

## Critères d'évaluation

Le projet ne sera considéré comme viable qu'uniquement lorsque les différents points techniques seront présents dans votre code :

### MVC
Votre architecture doit être construite sur l'architecture Modèle-Vue-Contrôleur vue au cours. Elle doit comporter plusieurs couches de contrôleurs d'application et plusieurs contrôleurs de vues. Votre modèle doit être assez complexe pour y inclure des hiérarchies de classes afin d'utiliser le polymorphisme de manière intelligente et approfondie. Ce polymorphisme doit vraiment être une clé de voûte dans votre code (par exemple, dans un programme d'édition graphique, une classe `Forme` peut être une classe abstraite et elle aurait des sous-classes comme `Cercle`, `Rectangle`, etc. Il y aura alors un certain nombre de méthodes surchargées qui permettront de gérer plus facilement l'édition et rendre le code plus extensible et maintenable). Les types abstraits doivent être utilisés comme type de variables, paramètres, ...

### Design pattern
Votre code doit comporter au moins 1 design pattern connu. L'utilisation de ce design pattern doit être justifiée (n'en mettez pas n'importe lequel juste pour en mettre un...). Si vous utilisez le design pattern de Singleton, il faut alors également en faire un second (car il est très simple).

### Réseau
Votre programme doit être capable de communiquer avec un autre programme via un réseau. Vous devez donc implémenter au moins un serveur et un client dans votre projet. Le serveur doit être capable de gérer plusieurs clients en même temps. Vous devez également implémenter un protocole de communication entre le client et le serveur. Ce protocole peut être simple mais clair et bien pensé. Vous devez également gérer les erreurs de communication entre le client et le serveur. Vous devez utiliser des sockets pour la communication entre le client et le serveur.

### Multi-threading
Votre programme doit être capable de gérer plusieurs threads en même temps. Vous devez donc implémenter au moins 2 threads différents. Vous devez également gérer les problèmes de synchronisation entre les threads. Vous devez utiliser les classes de la librairie standard de Java pour gérer les threads.

### Base de données
Votre programme doit être capable de stocker des données dans une base de données. Vous devez donc implémenter une base de données qui stocke les données de votre programme. Vous devez également être capable de lire et d'écrire des données dans cette base de données. Vous devez utiliser une base de données relationnelle pour stocker les données de votre programme (comme SQLite par exemple). Vous pouvez utiliser JDBC pour communiquer avec la base de données mais aussi d'autres librairies si vous le souhaitez.

### Repositories et Services
Afin d'alléger l'architecture MVC, vous allez ajouter des couches de repositories et de services. Les repositories gèrent l'accès aux données (base de données, fichiers, etc.) et servent d'interface entre l'application et la source de données, tandis que les Services contiennent la logique métier et coordonnent les interactions entre les Repositories et les contrôleurs pour maintenir une séparation claire des responsabilités. Dans cette architecture, les modèles représentent les données et la structure de l'application (par exemple, les entités comme User, Product, etc.), tandis que les Services contiennent la logique métier qui manipule ces modèles (par exemple, calculer un total, valider des données, etc.). Les modèles définissent **ce que** l'application manipule, et les services définissent **comment** elle les manipule.

### Fichier
Votre programme doit être capable de lire et d'écrire des données dans un fichier. Vous devez donc implémenter des classes qui permettent de lire et d'écrire des données dans un fichier. Vous devez également gérer les erreurs de lecture et d'écriture de fichier. Vous devez utiliser les classes de la librairie standard de Java vues au cours théorique pour lire et écrire des fichiers. Ce fichier peut, par exemple, être un fichier de configuration pour votre programme.

La qualité de votre travail **d'implémentation** sera évaluée selon les critères suivants :

### Conformité au cahier des charges
Toutes les fonctionnalités requises durant un sprint par vos clients doivent être implémentées.

### Style
Le code doit être bien structuré (en packages, classes, méthodes, ...). Le code doit suivre les principes de la *programmation orientée objet*, en utilisant le mécanisme de typage, héritage, polymorphisme, liaison tardive, interfaces, classes et méthodes abstraites, ... Le code doit suivre un *style de programmation défensive* : afin de réduire les erreurs lors de l'exécution du programme, le programme doit utiliser au maximum les mécanismes de typage (p.e. les types génériques), d'exceptions et d'assertions. Le code doit suivre proprement le pattern d'architecture Model-View-Controller (MVC). Les *design patterns* doivent être utilisés lors de l'implémentation quand il est possible de les utiliser. Les *conventions de nommage* doivent être respectées. Du *code dupliqué*, *code commenté* et du *code obsolète* doivent être évités.

### Compilation
Il doit y avoir un minimum de (voire aucun) problèmes ou warnings lors de la compilation.

### Complexité
Le code ne doit pas être inutilement complexe. À tout moment, il faut éviter un style procédural avec des méthodes complexes et beaucoup d'instructions conditionnelles. Les méthodes courtes avec des noms bien choisis seront à privilégier.

### Lisibilité
Le code doit être facile à lire et à comprendre et doit être bien documenté.

### Indépendance de la plate-forme
Le code produit doit être indépendant du système d'exploitation. Le code produit sera testé sur trois systèmes d'exploitation différents (`MacOS X`, `Linux` et `Windows`).

### Absence de plagiat
Le code produit ne peut être distribué entre différents groupes.

Les tests unitaires seront évalués selon les critères suivants :

### Processus
Le processus de test-driven development a-t-il été suivi ?

### Couverture
Les tests unitaires couvrent-ils toutes les fonctionnalités requises ? Y a-t-il des tests superflus ? Toutes les classes et méthodes importantes sont-elles couvertes par des tests ?

### Exactitude
Les tests sont-ils corrects ? Tous les tests unitaires fonctionnent-ils sans échec ou erreur ?

### Qualité
Les tests sont-ils de bonne qualité (pas de tests trop simples, des tests avec un comportement trivial, ...) ?

### Automatisation
Est-il possible d'exécuter tous les tests unitaires en une seule fois ? Y a-t-il une suite de tests permettant d'exécuter tous les tests unitaires en une seule fois ?

La documentation sera évaluée selon les critères suivants :

### JavaDoc
La documentation JavaDoc est-elle présente et est-elle suffisamment complète ? Est-elle de bonne qualité ? Les informations qu'on y trouve sont-elles pertinentes et utiles pour quelqu'un qui veut comprendre ou modifier le code ?

## Grille d'évaluation

### Projet (60%)

*Important* : la quantité pondère la qualité. La note finale du projet sera donc calculée comme suit : quantité * qualité. Si vous avez 50% des fonctionnalités demandées et une qualité de 80%, vous aurez 50% * 80% = 40% pour le projet. Si vous avez 100% des fonctionnalités demandées et une qualité de 50%, vous aurez 100% * 50% = 50% pour le projet.

1. **Conformité au cahier des charges (quantité) (100%)**
  - Respect des fonctionnalités requises.
  - Implémentation des exigences fonctionnelles et non-fonctionnelles.

2. **Qualité du code (100%)**
  - **Architecture MVC (20%)**
    - Séparation claire des responsabilités entre les couches.
    - Utilisation appropriée des contrôleurs.
    - Implémentation correcte d'au moins 2 threads différents.
    - Gestion appropriée de la synchronisation.
  - **Réseau (12%)**
    - Communication client-serveur fonctionnelle.
    - Gestion de multiples clients.
    - Protocole de communication clair.
  - **Fichier (8%)**
    - Lecture/écriture fonctionnelle.
    - Gestion des erreurs.
  - **Repositories et Services (12%)**
    - Séparation claire des responsabilités.
    - Encapsulation de la logique métier dans les services.
    - Abstraction de l'accès aux données dans les repositories.
  - **Base de données (12%)**
    - Structure de base de données appropriée.
    - Opérations CRUD fonctionnelles.
    - Gestion des erreurs de connexion.
  - **Design Patterns (12%)**
    - Utilisation justifiée d'au moins un design pattern.
    - Implémentation correcte.
  - **Général (12%)**
    - Respect des conventions de nommage.
    - Absence de code obsolète ou dupliqué.
    - Structure et organisation générale.
  - **Tests unitaires (8%)**
    - Couverture des fonctionnalités par les tests.
    - Exactitude et qualité des tests.
    - Automatisation des tests.
  - **Documentation (4%)**
    - Présence et qualité de la documentation JavaDoc.
    - Pertinence et utilité des informations fournies.

Si une des exigences est absente (réseau, tests, design pattern, ...), la note sera de moins de 10/20 pour le projet.

### Défense orale (40%)

  - Capacité à répondre individuellement aux questions sur le code, le design, la méthodologie, les tests, ...
  - Connaissance approfondie des aspects techniques du projet.


Pour rappel, la note finale sera calculée de la manière suivante:
- en cas de note à la défense orale strictement inférieure à 8, cette note sera la note finale (note absorbante);
- sinon, la note finale sera calculée selon la pondération donnée ci-dessus.

## Outils

### Outil de planification
Si besoin est, le choix des outils utilisés pour réaliser la planification et des diagrammes `Gantt` et `PERT` est à votre discrétion. De nombreux outils commerciaux ou open source existent (p.e. `Microsoft Project`, `Gnome Planner`, `TaskJuggler`, ...).

### Outil de modélisation
Si besoin est, comme outil de modélisation `UML`, vous avez le libre choix. Beaucoup d'autres outils commerciaux sont disponibles en version gratuite "Community Edition" sous la forme de stand-alone ou de plugin pour IntelliJ. Il existe également plusieurs outils open source de modélisation `UML` sous la forme de stand-alone ou de plugin pour `IntelliJ`.

### Outils de développement
Les outils suivants doivent être utilisés :

- La version 23 de Java (ou supérieure).
- L'IDE `IntelliJ 2024.3.2`, ou version supérieure.
- Pour vos fenêtres graphiques, vous devez utiliser la librairie graphique `JavaFX` (avec du FXML et des contrôleurs de vue).
- Pour les tests unitaires, l'outil `JUnit` (version 5 ou supérieure) doit être utilisé. Vous pouvez le trouver sur son site officiel [http://www.junit.org/](http://www.junit.org/).

### Outil de gestion de versions
L'utilisation de Git est imposée. Chaque groupe recevra un accès à un dépôt ; un groupe n'aura pas accès aux dépôts des autres groupes. Votre professeur aura constamment accès aux dépôts fournis. Utilisez-les intelligemment.

### Système d'exploitation
Vous pouvez utiliser n'importe quel système d'exploitation pour développer l'application. La seule contrainte est que tous les livrables après la phase d'implémentation (c.-à-d. le code source, les tests unitaires et la documentation) doivent être indépendants de la plateforme choisie.

## Objectifs du projet

Il n'y a pas de document de spécification donné par le professeur. Vous devrez discuter avec celui-ci et déterminer les User Stories, décrivant ce que l'application doit faire selon le point de vue de différents types d'utilisateurs. Les étudiants doivent raffiner ces "User Stories", en interagissant de manière continue avec le professeur qui, en tant que *client*, est demandeur de l'application.

Le client pourra éclaircir certains points restés ambigus ou incomplets. Sur cette base, chaque groupe doit établir un cahier des charges plus complet qu'il devra respecter tout au long du développement.

## La fin du projet

La fin du projet arrive lors de l'échéance du dernier sprint. Tous les livrables devront être déposés sur votre dépôt pour maximum le **vendredi 29 mai 2026 à 18h00** à 18h00. Attention: ne passez pas votre temps sur le projet pendant vos examens. Je vous laisse du temps pour ceux qui en auraient besoin mais prenez en compte que vous devez aussi vous préparer pour vos examens. Il est donc préférable de finir le projet avant le début de la session d'examen.

Vous défendez alors votre projet durant la session. Une vidéo de présentation de toutes les fonctionnalités présentes, des fonctionnalités non finalisées (par rapport à ce qui a été prévu) et de l'architecture du projet vous est demandée pour la même date (le vendredi 29 mai 2026 à 18h00). Cette vidéo doit être d'une durée de 10 minutes maximum (faites concis mais complet) et doit être déposée sur Youtube. Le lien sera mis dans un fichier nommé "video.txt" sur la racine du dépôt Git de votre groupe.

Lors de cette défense, vous passerez groupe par groupe. Vous présenterez en moins de 10 minutes les fonctionnalités de votre programme et les différents points techniques de qualité demandés dans l'énoncé (design patterns implémentés, architecture générales, ...). La présentation doit être préparée et professionnelle. La présentation peut être la même que celle de la vidéo (elle peut donc aussi être différente). Tout le monde ne doit pas forcément parler durant la présentation : soit un seul membre parle et une autre gère l'affichage sur son PC (montrer le code, ...), soit chaque membre présente une partie. Vous pouvez utiliser un support visuel pour la partie qualité (p.e. un PowerPoint). Vous pouvez aussi utiliser le code source de votre projet pour montrer les fonctionnalités implémentées et les points techniques de qualité demandés dans l'énoncé.

Le professeur posera ensuite des questions **individuellement** à chaque membre du groupe. Ces questions peuvent porter sur le code, le design, la méthodologie, les tests, ... Il sera donc nécessaire que chaque membre du groupe connaisse ces quatre aspects du projet pour pouvoir répondre correctement aux questions. Normalement, nous aurons des ordinateurs pour vous permettre de répondre à mes questions. Prenez cependant votre ordinateur avec vous pour pouvoir montrer .

La cote finale sera calculée en fonction de la qualité de tous les livrables et les fonctionnalités réalisées (60%), ainsi qu'en fonction de la cote obtenue lors de la défense finale (pendant la session) (40%). **Attention : si la note de défense est strictement plus petite que 8/20, nous oublions la note du projet et la note de défense devient la note finale pour le cours.**

Pour la **seconde session** pour les projets, un nouveau projet sera à effectuer seul et à rendre pour une semaine avant l'examen (donc si l'examen a lieu le 25 août 2026, vous devez rendre votre projet le 18 août à 23h59 maximum). Un examen pratique durant la seconde session, incluant des modifications à faire dans un temps imparti, permettra de montrer vos capacités à développer en Java. Tout se déroulera sur votre PC. Prenez donc le avec et préparez-le afin qu'il soit efficace. Des questions orales peuvent être également posées. La répartition sera la même : 60% pour le projet et 40% pour l'examen. **Attention : si la note de défense est strictement plus petite que 8/20, nous oublions la note du projet et la note de l'examen devient la note finale pour le cours.**

Les modalités de l'examen (vidéo, ordre de passage, ...) seront envoyées via Connected en temps voulu.
