# Expérience professionnelle
Cette page contient les détails de mon expérience professionnelle après l'obtention de mon diplôme.
Pour mon expérience professionnelle pendant mes études, veuillez consulter la [page d'éducation cooperative](coop.md).

## Développeur Python Senior, [Adimian](https://www.adimian.com/)
_De janvier 2021 à octobre 2023, Belgique._

??? summary "Résumé"

    - Responsabilité de bout en bout du projet, y compris la conception initiale, le développement, le déploiement et la maintenance.
    - Développement et maintenance d'une variété d'applications Python, y compris un système de gestion de données basé sur le web et une chaîne de traitement de données.
    - Utilisation de bibliothèques Python comme Pydantic, FastAPI, SqlAlchemy, et Redis pour le développement backend et Vue pour les tâches frontend.
    - Gestion efficace des rapports de bogues et des versions, maintien de livrables de haut standard.
    - Expérience de tutorat pour encadrer les collègues, les aider à améliorer leurs compétences et à intégrer de nouveaux membres de l'équipe, avec des éloges.

Adimian est une société belge de conseil en logiciels connue pour son expertise en développement sur mesure, en cybersécurité et en big data.
Ils ont une présence marquée dans le secteur de l'énergie et auprès des institutions européennes.
Leurs services sont adaptés pour répondre à des projets de petite et grande envergure dans différents environnements,
excelle particulièrement en ingénierie des données et en déploiement de logiciels, soutenus par un engagement indéfectible en matière de sécurité et de conformité.

Travaillant à la fois sur des produits internes d'Adimian et sur des projets externes, j'ai participé à l'ensemble du processus itératif,
allant de l'analyse et de la conception initiales, au développement et enfin au déploiement et à la maintenance évolutive.
Tout le code Python a été développé en utilisant TDD avec pytest.

J'ai commencé avec un petit projet chez Adimian, où j'ai eu ma première expérience de développement web en utilisant FastAPI et VueJS.
J'ai ensuite développé un outil de génération de schémas SVG pour une entreprise de photonique,
et j'ai poursuivi en développant un autre outil qui permettait à l'utilisateur de visualiser et de naviguer dans ces schémas.

J'ai également travaillé sur un outil de vote de gouvernance utilisé par divers opérateurs de systèmes de transmission d'énergie (TSO) à travers l'Europe.
L'outil avait été développé par Adimian en utilisant FastAPI, Vue, et VueX,
et j'ai fourni un soutien crucial en résolvant les bugs et en développant de nouvelles fonctionnalités à la demande du client.

J'ai été envoyé à un Centre de Coordination Régional pour les TSO européens en avril 2022.
Mon rôle impliquait une responsabilité de bout en bout du projet, allant de la conception initiale à la finalisation,
suivi d'une maintenance proactive et réactive.

Notre flux de travail consistait en des sprints bimensuels, où je faisais du développement de code et de la documentation, ainsi que la révision et le test du code écrit par mes collègues.
La pile technologique comprenait principalement Python, où j'utilisais des bibliothèques comme
Pydantic, FastAPI, SqlAlchemy, et Redis pour le développement backend ; et Vue pour les tâches frontend.
Dans certains cas, j'ai conçu et mis en œuvre des scripts ad hoc, géré les versions, et répondu efficacement aux rapports de bugs,
maintenant le haut standard de nos livrables.

En plus du travail de projet, j'ai également assumé un rôle de mentor.
J'ai utilisé mon expérience de tutorat et mes connaissances techniques pour aider les collègues à améliorer leurs compétences et à intégrer les nouveaux membres de l'équipe,
guidant leur intégration dans notre environnement de travail dynamique.
J'ai également introduit de nouvelles techniques et méthodologies.

J'ai été très apprécié pour ma patience et ma compréhension lors de la révision, de l'explication ou de l'enseignement, ainsi que pour la rapidité et la qualité de mon propre code.

## Développeur Python Senior, [Yields.io](https://www.yields.io/)
_Décembre 2019 à août 2020, Bruxelles, Belgique._

??? summary "Résumé"

    - A été le principal développeur Python, travaillant sur le cœur de la plateforme.
    - A refactorisé et stabilisé la base de code, ajouté des tests, corrigé des bogues, et développé de nouvelles fonctionnalités.
    - A travaillé sur la migration automatique et les tests du code et des artefacts du client avec des augmentations de version, et déprécié les anciennes fonctionnalités.
    - A déplacé les tests d'intégration pour qu'ils ne dépendent plus de mocks vers des tests qui fonctionnaient avec un environnement Docker déployé.

Yields.io est la première entreprise à développer un système de gestion automatisée des risques de modèles basé sur l'IA à l'échelle de l'entreprise
avec une plateforme conçue pour soutenir le cycle de vie complet du modèle.
Ils offrent principalement leurs services au secteur financier, les petites banques régionales automatisant l'effort de validation des modèles,
et les grandes institutions rationalisant et mettant à l'échelle leurs modèles.

J'étais le développeur Python principal chez Yields.
Le cœur de la plateforme est écrit en Python, et communique avec une API backend écrite en Scala.
Jupyter est utilisé par les clients pour exécuter leurs algorithmes. J'ai refactorisé et stabilisé la base de code, ajouté des tests, corrigé des bugs,
développé de nouvelles fonctionnalités que l'entreprise ou les clients demandaient, et ajouté des notebooks Jupyter orientés client.

Par exemple, j'ai séparé ce qui était un monolithe en trois packages distincts qui pouvaient être déployés indépendamment.
Cela a également permis aux clients d'implémenter leur propre algorithme en utilisant notre plateforme comme base au cas où ils voulaient les garder propriétaires.

De plus, j'ai utilisé pytest pour écrire des milliers de tests unitaires pour du code précédemment non testé,
et refactorisé des fonctions individuelles pour les rendre plus testables.
Cela nous a permis de détecter de nouveaux bogues et d'identifier des zones où la fonctionnalité différait de la conception.

J'ai travaillé sur la migration automatique et le test du code et des artefacts du client avec des augmentations de version, et déprécié les anciennes fonctionnalités.
J'ai également aidé les collègues quand ils avaient des questions sur certaines parties de la base de code.

Vers la fin, je déplaçais les tests d'intégration pour qu'ils ne dépendent plus de mocks qui ne suivaient pas les changements de l'API,
vers des tests qui pouvaient fonctionner avec un environnement Docker déployé.

## Ingénieur en Automatisation Industrielle, [Kapernikov](https://www.kapernikov.com/)
_De mars à octobre 2019, Bruxelles, Belgique._

??? summary "Résumé"

    - Développé un système de surveillance pour une bande transporteuse en utilisant Python 3 et ROS.
    - Utilisé un profileur laser et une caméra pour l'identification d'objets et créé une représentation 3D de la bande transporteuse.
    - Détecté des objets potentiellement perturbateurs en temps réel et produit des visualisations pour le système de gestion vidéo du client.
    - Corrigé des bogues dans le code C++ et créé un nœud ROS autonome pour la communication avec la caméra.

Kapernikov est une société de conseil spécialisée en automatisation industrielle et en Industrie 4.0.
Le client avait des objets de formes irrégulières sur une longue bande transporteuse, certains d'entre eux bloquaient la bande et causaient de longs retards.

J'ai développé un système de surveillance pour la bande transporteuse, en utilisant principalement Python 3 et ROS.
J'ai utilisé un profileur laser et une caméra pour identifier les points les plus hauts dans le plan du laser,
et transformé cela en coordonnées physiques en utilisant un code de calibration personnalisé écrit en Python.

En connaissant la vitesse de la bande grâce à un encodeur connecté, j'ai pu créer une représentation 3D de la bande transporteuse.
Celle-ci a été analysée, et des objets potentiellement perturbateurs ont été détectés en temps réel.
Des visualisations ont été produites et annotées, puis envoyées au système de gestion vidéo du client.

La caméra avait des pilotes en C++, ainsi que du code C++ interne qui contenait quelques bogues que j'ai corrigés.
J'ai créé un nœud ROS autonome qui communiquait avec la caméra et ne transmettait que les données nécessaires au reste du système.
Tous les autres nœuds ROS, transformations et analyses étaient écrits en Python.

## Data Scientist, [Sentiance](https://www.sentiance.com/)
_Février à décembre 2018, Anvers, Belgique._

??? summary "Résumé"

    - A déplacé la base de code de l'entreprise de Python 2 à Python 3.
    - A refactorisé la fonctionnalité de base en composants plus modulaires, vérifié et construit des modèles d'apprentissage automatique dans numpy et scikit-learn.
    - A utilisé pyspark pour augmenter l'efficacité du code en parallélisant, ou pour ajouter de nouvelles fonctionnalités.
    - A créé plusieurs conteneurs docker et fichiers docker-compose pour automatiser la mise en place et la destruction de l'environnement.
    - A travaillé à la standardisation des contenus de l'index DevPI en utilisant Pipenv.

Sentiance transforme les données des capteurs IOT provenant par exemple de téléphones mobiles en données perspicaces,
telles que le segment de la population auquel appartient un utilisateur, ainsi que ses actions actuelles et futures prévues.
Le cœur de la base de code était écrit en Python 2, qui a atteint sa fin de vie le 1er janvier 2020.

Mon rôle principal consistait à déplacer la base de code de l'entreprise de Python 2 à Python 3.
J'ai refactorisé la fonctionnalité de base en composants plus modulaires, vérifié et construit des modèles d'apprentissage automatique dans numpy et scikit-learn,
et utilisé pyspark pour augmenter l'efficacité du code en parallélisant, ou pour ajouter de nouvelles fonctionnalités.

Séparément, j'ai amélioré la productivité des développeurs en créant plusieurs conteneurs docker et fichiers docker-compose
pour automatiser la mise en place et la destruction de l'environnement. Vers la fin, j'ai également travaillé à la standardisation des contenus de l'index DevPI en utilisant Pipenv.
