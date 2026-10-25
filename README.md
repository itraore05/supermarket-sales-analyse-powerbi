# 🛒 Supermarket Sales — Analyse des performances d'une enseigne de distribution (Power BI)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-KPI-informational?style=flat)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue?style=flat)
![Excel](https://img.shields.io/badge/Excel%20%2F%20CSV-données-217346?style=flat)

> Tableau de bord Power BI pour améliorer le rendement d'une chaîne de supermarchés : suivi des ventes et de la rentabilité, comportement des clients, heures d'affluence et comparaison entre villes.
> Projet Data Analyst — février 2025.

---

## 🎯 Objectifs

- Suivre les ventes et la rentabilité des produits
- Optimiser la gestion des stocks et des promotions
- Comprendre le comportement des clients et leur fidélité (membres vs non-membres)
- Identifier les périodes creuses et les heures de forte affluence
- Comparer les performances entre magasins et villes

## 🗂️ Données

| Élément | Détail |
|---|---|
| Source | Dataset public *Supermarket Sales* (Kaggle) |
| Granularité | Transaction individuelle (facture) |
| Volume | **1 000 transactions** |
| Dimensions | Ville, ligne de produits, type de client, genre, mode de paiement, date et heure |

## 🧭 Structure du tableau de bord

1. **Performance globale** : CA, marge brute, panier moyen, nombre de transactions
2. **Analyse temporelle et géographique** : évolution du CA par jour, ventes par ville
3. **Analyse produits et clients** : top produits, ventes par type de client
4. **Rapport et synthèse** : recommandations

## 📈 Chiffres clés

| Indicateur | Valeur |
|---|---|
| Chiffre d'affaires total | **322,97 K** |
| Marge brute totale | **15,38 K** |
| Taux de marge brute | **4,76 %** |
| Panier moyen | **327,79** |
| Transactions | **1 000** |

**Insights :**
- 🥇 Les lignes **Alimentation & boissons**, **Sports & voyage** et **Accessoires électroniques** génèrent le plus de chiffre d'affaires.
- 📦 Les **accessoires électroniques** sont les produits les plus vendus en volume.
- 👥 Les ventes se répartissent de façon équilibrée entre clients **membres** et **non-membres** : le programme de fidélité peut être renforcé.
- 📅 Le CA quotidien varie fortement, ce qui justifie d'adapter les promotions et les effectifs aux pics d'affluence.

## 🖼️ Aperçu

📄 [Consulter le dashboard complet en PDF](dashboard/dashboard.pdf)

## 📁 Structure du dépôt

```
supermarket-sales-analyse-powerbi/
├── dashboard/      # dashboard Power BI et export PDF
├── data/           # données aux formats Excel et CSV
├── documentation/  # document de présentation du projet
└── README.md
```

| Élément | Lien |
|---|---|
| Dashboard Power BI | [`supermarket.pbix`](dashboard/supermarket.pbix) |
| Dashboard (PDF) | [`dashboard.pdf`](dashboard/dashboard.pdf) |
| Données | [Excel](data/supermarket_sales.xlsx) · [CSV](data/supermarket_sales.csv) |
| Présentation du projet | [`README-projet.docx`](documentation/README-projet.docx) |

> ℹ️ Les données proviennent d'un jeu de données public. L'habillage visuel du dashboard est utilisé à titre illustratif ; ce projet n'est affilié à aucune enseigne.

## 👤 Auteur

**Ismaël Traoré** — Développeur Data & IA
📧 contact.traoreimael@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/ismael-traor%C3%A9-m-4007a2225/)
