# Phoenix Design

Dans le monde TI depuis la fin des années 90 et celui de l'infonuagique depuis 2014, nous sommes principalement basés sur le principe de l'open source et croyons sincèrement que l'évolution des technologies se base surtout sur le partage des connaissances et de l'expérience. C'est pourquoi, lorsque possible, nous partageons nos efforts à travers la communauté!

Nous savons que rien n'est parfait... et qu'il existe plusieurs méthodologies et technologies. Notre approche pourrait peut-être vous aider. Vos avis ainsi que vos idées sont les bienvenues!

Nous remercions tous les collaborateurs, tous ceux qui de façon positive, permettent le développement et l'évolution de tout un chacun, dans cette grande communauté!

> Le maintien de cet espace s'effectue hors des heures de travail et comme plusieurs d'entre vous, nous actualisons le contenu en fonction des disponibilités. Merci pour votre compréhension.

## On travaille sur quoi?

Il n'y a que 24 h dans une journée et 7 jours par semaine! On voudrait bien tout connaître, mais bon, on doit tout de même dormir de temps en temps et même parfois avoir une vie sociale :P

### Solutions

Liste des principales solutions déployées et utilisées.

#### Azure


|Services  |Contexte  |
|---------|---------|
|App Services |Déploiement de conteneurs pour application web; [PasswordPusher](https://github.com/pglombardo/PasswordPusher), [Wordpress](https://github.com/WordPress/WordPress), [GLPI](https://github.com/glpi-project/glpi),etc.|
|Automation accounts|Déploiement des extensions Azure ARC, exécution de tâches récurrentes, etc. |
|Azure ARC |Gestion centralisée des serveurs, postes d'administration et services, incluant le déploiement des extensions de gestion (sécurité, analyse des performances, administration à distance). |
|Azure AD Conditional Access|Respect des normes de sécurité et implantation de la conformité. |
|Azure DevOps|Développement et maintien du code source privé, incluant la mise en place de pipelines. |
|Azure Monitor |Analyse centralisée du niveau de sécurité des ressources déployées, cloud et on-premise.|
|Azure Policies |Déploiement des règles de conformité pour faciliter l'audit ainsi que le déploiement des extensions requises (AMA, Security Agent, etc.). |
|Azure SQL |Intégration du service pour la gestion de data warehouse et la modélisation via Data Factory. |
|Data Factory|Importation et modélisation de données pour l'ingestion vers le data warehouse.|
|Groupe de gestion |Regroupement logique des abonnements afin de répondre à la conformité et segmenter adéquatement l'accès aux ressources. |
|DNS Zone |Gestion des DNZ publiques. |
|Key vaults |Intégration aux services cloud, ainsi qu'au développement d'application et l'exécution automatisée. |
|Landing zone |Principe basé sur les meilleures pratiques pour la migration, intégration et l'évolution des services cloud. |
|Log Analytics workspaces |Gestion des données de diagnostics et de sécurité. |
|Microsoft Sentinel |Solution SIEM/SOAR utilisée dans le cadre des opérations de sécurité.|
|Microsoft Defender 365 |Solution XDR déployée et liée à MS Sentinel afin de centraliser les opérations de sécurité. |
|Microsoft Endpoint Manager |Gestion centralisée des appareils de type poste et mobile et permettre le déploiement de politiques, logiciels et automatisation de tâches. |
|Policy |Déploiement des politiques de conformité et de sécurité pour le tenant, facilitant l'identification des améliorations et du suivi des standards. |
|Storage Accounts|Intégration aux solutions de développement, d'automatisation ainsi qu'à l'importation/exportation de journaux d'analyse. |

### Applications

![GLPI Logo](https://raw.githubusercontent.com/glpi-project/glpi/main/pics/logos/logo-GLPI-250-black.png)

Gestionnaire Libre de Parc Informatique, cette application permet la gestion de ressources et services TI. Elle propose des fonctionnalités Centre de service ITIL, gestion de licences, audit logiciel et bien plus.

> [GLPI Sur Github](https://github.com/glpi-project/glpi)

![Password Pusher Logo](https://camo.githubusercontent.com/605784bbd2101eb06dabf145df15fbce3d991c12972880c7683674aa224f7f81/68747470733a2f2f7077707573682e73332e65752d776573742d312e616d617a6f6e6177732e636f6d2f7077707573682d686f72697a6f6e74616c2d6c6f676f2e706e67)

Application web de source libre permettant l'échange sécurisé de secret, clé, mot de passe, etc. Légère et personnalisable, son utilisation est simple, intègre des fonctionnalités en ligne de commande et vous pouvez déployer votre instance privée.

> [Pasword Pusher sur Github](https://github.com/pglombardo/PasswordPusher)

### Languages

Principaux langages utilisés dans le cadre des activités.


|Language  |Contexte  |
|---------|---------|
|Powershell|Automatisation et optimisation des opérations, incluant le déploiement de ressources/services.         |
|KQL     |Analyse, recherche et création de requêtes spécifiques dans les journaux analytiques et MS Sentinel.        |
|SQL     |Déploiement et maintien des données utilisées par les services, ainsi que la planification de tâches (SP).         |
|Python  |Création de playbook et de tâches automatisées.         |
|Ruby    |Développement et maintien d'applications web.         |
