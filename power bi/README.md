# 📈 Power BI : tableaux de bord du commerce extérieur

Ce dossier présente les tableaux de bord Power BI réalisés à partir des fichiers préparés par les jobs d'agrégation DataStage (voir le dossier `etl`). Ils permettent d'analyser les échanges commerciaux du Maroc selon plusieurs axes : produits, pays partenaires, régimes, branches d'activité et périodes.

## 🖼️ Tableaux de bord

### 1. Importations par groupement d'utilisation (2016 – 2025)
Évolution des importations, variations annuelles et poids relatif de chaque groupement d'utilisation.

![Importations par groupement d'utilisation](importations%20par%20groupement%20dutilisation.png)

### 2. Exportations par groupement d'utilisation (2016 – 2025)
Même analyse pour les exportations.

![Exportations par groupement d'utilisation](exportations_GU.png)

### 3. Importations par pays partenaires
Identification des principaux fournisseurs du Maroc et de l'évolution de leur contribution.

![Importations par pays partenaires](importations%20par%20pays%20partenaires.png)

### 4. Exportations par destination
Identification des principaux clients du Maroc.

![Exportations par destination](exportations%20par%20destination.png)

### 5. Analyse comparative 2024 / 2025
Importations, exportations, **solde commercial** et **taux de couverture**, avec la variation entre les deux années.

![Analyse comparative 2024 et 2025](commerce_exterieur_2024%20%26%202025.png)

### 6. Analyse sectorielle
Échanges par branche d'activité, arbre de décomposition (branche → sous-branche → produit) et répartition par régime commercial.

![Analyse sectorielle](analyse_sectorielle.png)

## 🧮 Mesures DAX

| Mesure | Rôle |
|---|---|
| Valeur de l'année précédente | Base de calcul des variations annuelles |
| Exportations | Total des exportations |
| Importations | Total des importations |
| Structure | Poids relatif d'une catégorie dans le total |
| Variation | Évolution par rapport à l'année précédente |
| Solde commercial | Exportations − Importations |
| Taux de couverture | Exportations / Importations |

### Valeur de l'année précédente
![Mesure valeur année précédente](mesure_DAX_valeur_annee_precedente.png)

### Exportations
![Mesure exportations](mesure_DAX_export.png)

### Importations
![Mesure importations](mesure_DAX_import.png)

### Structure
![Mesure structure](mesure_DAX_structure.png)

### Variation
![Mesure variation](mesure_DAX_variation.png)

### Solde commercial
![Mesure solde commercial](mesure_DAX_solde_commerciale.png)

### Taux de couverture
![Mesure taux de couverture](mesure_DAX_taux_couverture.png)
