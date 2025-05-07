# SpaceHack 2024 – Migration environnementale en Afrique sahélienne

## Équipe 

*premier hackathon* pour relever un défi réel et multidisciplinaire.

*Membres de l’équipe* :
 *Wiame*, *Sagana*, *Hajar*, *Sanem*, *Bouchra* et *Samia*

---

## Contexte du projet

L’Afrique sahélienne est une région semi-aride, particulièrement vulnérable au *changement climatique*, à la **désertification* et à la *raréfaction des ressources*.  
Ces dégradations environnementales entraînent des *déplacements de populations* et des *tensions sociales*.

---

## Objectif

Utiliser les *données satellitaires* pour :
- Suivre l’évolution de l’environnement (végétation, eau, sécheresse, précipitations)
- Comprendre leurs liens avec les *mouvements de population*
- Proposer des pistes d’action pour une *résilience climatique* locale

---

## Données et outils utilisés

Plateforme principale : *Google Earth Engine (GEE)*

Données traitées :
- NDVI (MODIS)
- Précipitations (GPM, CHIRPS)
- Eau de surface (JRC)
- Humidité des sols (ERA5)
- Température de surface (MODIS)
- Densité de population (GPWv4)
- Urbanisation (GHSL)

> Les traitements ont été réalisés directement sur GEE via des scripts non conservés.  
> Voir le fichier sources.md pour le détail des jeux de données utilisés.

---

## Résultats clés

- *Perte de végétation* dans certaines zones du Sahel
- *Baisse des précipitations* entre 2000 et 2020
- *Augmentation paradoxale de l’eau de surface*, liée à des phénomènes physiques (érosion, montée du niveau marin…)
- Corrélation partielle entre *sécheresse, perte de végétation* et *flux migratoires*

---

## Limites

- Les résultats ne peuvent pas être interprétés sans *contexte historique et social*.
- Les scripts GEE n’ont pas été archivés, seule la méthodologie est décrite.
- Les corrélations environnement/migration doivent être analysées avec prudence.

---

## Recommandations

- Mieux croiser données satellitaires et *données humaines (recensements, conflits, enquêtes)*
- Développer des *cartes de risque environnemental et humain* actualisées
- Intégrer ces outils dans les *politiques publiques de prévention climatique et d’aménagement*

---

## Liens utiles

- 📄 [Voir la présentation complète (PDF)](./Sahel_Migration_SatelliteAnalysis.pdf)
- [Sources de données](./sources.md)
- [Site du hackathon](https://www.spacehack4sustainability.com/migration-sahelian-africa)
