# Tableau de bord des performances commerciales (Power BI)

## 📌 Aperçu du projet
Ce projet présente un **tableau de bord interactif** développé avec **Power BI Desktop**, permettant d’analyser les performances commerciales d’une entreprise à travers différents indicateurs clés (KPI).  
L’objectif est de fournir une vue claire et dynamique sur les ventes, les profits et les performances régionales.

🔗 **[Voir le dashboard en ligne](https://app.powerbi.com/groups/me/reports/d3e52880-ff57-4188-b1a1-c2ba04533c04/0669a4f1c02e4ccec927?experience=power-bi)**

---

## 🎯 Objectifs
- Suivre les **KPI clés** : ventes totales, profit, ratio de profit, nombre de commandes.  
- Visualiser l’évolution des ventes dans le temps.  
- Identifier les zones géographiques les plus performantes.  
- Fournir des filtres dynamiques (année, segment, région, catégorie).

---

## 📂 Contenu du dépôt
- `dashboard.pbix` — Fichier Power BI complet.  
- `Tableau_de_bord_Perfor.png` — Capture d’écran du dashboard.  
- `README.md` — Documentation du projet.

---

## ⚙️ Comment utiliser
1. Télécharger ou cloner le dépôt.  
2. Ouvrir `dashboard.pbix` dans **Power BI Desktop**.  
3. Explorer les KPI, utiliser les slicers, naviguer dans les graphiques.

---

## 📊 Indicateurs et mesures DAX
- **Total ventes** : somme des ventes.  
- **Total Profit** : somme des profits.  
- **Nombre comandes** : nombre de commandes distinctes.  
- **Ratio Profit (%)** = `[Total Profit] / [Total Sales] * 100`.  
- **Sales Last Year** : ventes de l’année précédente.  
- **Sales Growth %** : taux de croissance par rapport à l’année passée.  
- **Top 5 Products** : filtre sur les produits les plus vendus.

---

## 🖼️ Aperçu du dashboard
![Aperçu du tableau de bord](Tableau_de_bord_Perfor.png)

---

## 📈 Conclusion business
- Les ventes globales atteignent **2,14M** avec un profit total de **257,68K**, représentant un **ratio de profit de 12,03%**.  
- Les tendances montrent une croissance progressive au fil de l’année, avec des pics notables en milieu et fin d’année.  
- L’Amérique du Nord, l’Europe et l’Asie concentrent la majorité du chiffre d’affaires.  
- Le segment **Consumer** domine les ventes, ce qui suggère un potentiel de croissance dans les segments **Corporate** et **Home Office**.  

---

## 🚀 Améliorations possibles
- Connexion à une **source de données en direct** pour mise à jour automatique.  
- Ajout de pages pour analyser plus en détail les performances produits/régions.  
- Intégration de nouveaux KPI financiers comme la marge ou le coût d’acquisition.
