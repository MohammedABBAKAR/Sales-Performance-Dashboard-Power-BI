⸻

## 📊 Sales Performance Dashboard – Power BI

🔹 Contexte

Dans un environnement commercial en constante évolution, les entreprises génèrent aujourd’hui un volume croissant de données de ventes couvrant plusieurs dimensions (clients, produits, régions, modes de paiement, etc.).

Cependant, ces données sont souvent difficiles à exploiter efficacement en raison de leur complexité et de l’absence d’outils adaptés. L’analyse manuelle devient rapidement limitée et ne permet pas d’obtenir une vision globale ni d’identifier facilement les tendances et les opportunités.

Ce projet s’inscrit dans une démarche de transformation des données brutes en informations exploitables, grâce à un outil de Business Intelligence interactif.

⸻

🎯 Objectif du Projet

L’objectif principal est de concevoir un tableau de bord interactif avec Power BI afin d’analyser la performance commerciale de manière claire et dynamique.

Ce projet vise à :

* Suivre les indicateurs clés (chiffre d’affaires, profit, commandes, quantités)
* Analyser les ventes par catégorie, sous-catégorie, clients et régions
* Étudier l’évolution des performances dans le temps (analyse mensuelle, YoY)
* Identifier les opportunités de croissance et les segments rentables
* Aider à la prise de décision grâce à une visualisation interactive

⸻

🧩 Data Model

Le modèle de données est structuré selon les bonnes pratiques de la modélisation BI :

* Table principale : Sales / Orders
* Table dimensionnelle : Date (table de dates créée manuellement)
* Relation :
    * Date[Date] → Orders[Order Date]

👉 La table de dates permet :

* Les analyses temporelles (YoY, MoM)
* Une meilleure gestion des filtres temporels
* La continuité des périodes même sans ventes

⸻

📈 Dashboard Features

Le tableau de bord est structuré en plusieurs pages :

🔹 Overview

* KPI Cards : Sales, Profit, Quantity, Orders
* Analyse globale des performances
* Visualisation des tendances

🔹 Markets

* Analyse géographique (State, City)
* Répartition des ventes
* Analyse par mode de paiement

🔹 Customers

* Top clients
* Analyse Pareto (80/20)
* Performance par client

🔹 Time Analysis

* Évolution mensuelle
* Analyse YoY et MoM
* Identification des tendances

⸻

⚙️ Fonctionnalités clés

* 🔄 Filtres dynamiques (date, région, catégorie, client)
* 📊 Analyse de croissance (YoY %)
* 🧠 Analyse Pareto pour identifier les clients stratégiques
* 🎯 Segmentation (Sales Band, Profitability Band)
* 🌍 Visualisation géographique
* 📅 Table de dates pour analyses temporelles fiables

⸻

🧠 Insights clés

Grâce à ce tableau de bord, plusieurs insights peuvent être identifiés :

* Une petite partie des clients génère la majorité du chiffre d’affaires (loi de Pareto)
* Certaines catégories sont plus rentables que d’autres
* Des variations importantes existent entre les régions
* Les tendances mensuelles permettent d’anticiper les performances futures

⸻

🖼️ Dashboard Preview

<img width="1289" height="719" alt="Screenshot 2026-04-18 at 21 06 19" src="https://github.com/user-attachments/assets/6b5fc14b-3fef-4421-8189-e501d20201e8" />
<img width="1158" height="653" alt="Screenshot 2026-04-18 at 21 07 45" src="https://github.com/user-attachments/assets/289844cc-aeab-430b-98c8-8efd1d69ab09" />


⸻

🚀 Conclusion

Ce projet démontre l’importance de la Business Intelligence dans la prise de décision.
Le tableau de bord développé permet de transformer des données complexes en informations claires et exploitables, facilitant ainsi l’analyse et l’optimisation de la performance commerciale.

⸻

🛠️ Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization
