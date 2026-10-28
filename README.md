Incendies-bejaia-jijel-2026
Analyse satellitaire des incendies d'août 2026 à Béjaïa et Jijel : zones brûlées, sévérité et exposition du bâti.

Analyse spatiale des surfaces brûlées, de la sévérité des incendies et de l'exposition du bâti à partir de données satellitaires ouvertes.**

Présentation du projet

Ce projet porte sur l'observation des incendies de forêt survenus en août 2026 dans les wilayas de Béjaïa et de Jijel, dans le nord-est de l'Algérie.

L'objectif est de caractériser spatialement cet épisode à partir de données satellitaires et de données géographiques ouvertes, afin de délimiter les surfaces brûlées, d'estimer la sévérité des brûlures et d'identifier les bâtiments situés dans le périmètre affecté.

L'étude mobilise des méthodes de télédétection et d'analyse spatiale pour mieux comprendre la répartition des incendies et l'exposition des espaces habités.

Objectifs

- Observer la chronologie et la répartition spatiale des foyers actifs.
- Délimiter les surfaces brûlées à partir d'images Sentinel-2.
- Estimer la sévérité des brûlures à l'aide de l'indice dNBR.
- Identifier les bâtiments situés à l'intérieur du périmètre brûlé.

Données mobilisées

| Données                         | Source               | Utilisation                                                    |
| ------------------------------- | -------------------- | -------------------------------------------------------------- |
| Sentinel-2 L2A                  | Programme Copernicus | Délimitation des surfaces brûlées et estimation de la sévérité |
| Détections de feux actifs VIIRS | NASA FIRMS           | Analyse de la chronologie et de la distribution des foyers     |
| Bâtiments et occupation du sol  | OpenStreetMap        | Identification des bâtiments exposés dans le périmètre brûlé   |

Les images Sentinel-2 utilisées correspondent aux dates du **9 juillet et du 7 septembre 2026**, permettant de comparer l'état de la végétation avant et après l'épisode étudié.

Méthodologie

1. Analyse temporelle des incendies

Les détections de feux actifs VIIRS sont utilisées pour observer l'évolution quotidienne de l'activité entre le 26 et le 29 août 2026, ainsi que le contexte précédant cet épisode.

Cette analyse permet de suivre la concentration et le regroupement spatial des foyers détectés.

2. Délimitation des surfaces brûlées

L'indice de végétation par différence normalisée (NDVI) est calculé à partir des bandes du proche infrarouge et du rouge de Sentinel-2.

La différence entre les deux dates est ensuite utilisée pour repérer les zones présentant une baisse importante de l'activité végétale :

`ΔNDVI = NDVI avant incendie − NDVI après incendie`

Les zones identifiées sont ensuite filtrées et nettoyées afin de limiter les artefacts de détection.

3. Estimation de la sévérité des brûlures

L'indice NBR est calculé à partir du proche infrarouge et de l'infrarouge à ondes courtes. Sa différence entre les dates avant et après incendie permet d'obtenir le dNBR.

Les valeurs sont classées selon les seuils de référence retenus dans l'étude, issus de la convention USGS, afin de distinguer plusieurs niveaux de sévérité.

4. Analyse de l'exposition du bâti

Les bâtiments OpenStreetMap sont superposés au périmètre brûlé afin d'identifier ceux qui se trouvent dans les zones affectées.

Leur typologie est complétée, lorsque cela est possible, à partir des données d'occupation du sol.

Important :** la présence d'un bâtiment dans le périmètre brûlé indique une exposition potentielle. Elle ne prouve pas que le bâtiment a effectivement été endommagé ou détruit.

Principaux résultats

L'analyse met en évidence plusieurs éléments :

- Les détections VIIRS montrent le regroupement de plusieurs foyers distincts le 26 août en un ensemble presque continu le 27 août, principalement à l'est de la wilaya de Jijel.
- Les surfaces brûlées sont concentrées dans les premiers reliefs situés en arrière de la plaine littorale.
- Les centres urbains de Béjaïa et de Jijel restent en dehors des principales surfaces brûlées identifiées.
- Les surfaces brûlées à l'est de Jijel présentent majoritairement une sévérité élevée, tandis que le littoral de Béjaïa montre une distribution plus hétérogène.
- Plus de 5 000 bâtiments OpenStreetMap sont recensés à l'intérieur du périmètre brûlé estimé.

Limites de l'étude

Les résultats dépendent de la disponibilité et de la qualité des données utilisées.

Les images satellitaires permettent d'estimer les surfaces brûlées, mais la classification obtenue reste sensible aux conditions d'observation et aux choix méthodologiques.

Les données OpenStreetMap peuvent être incomplètes, notamment concernant la présence des bâtiments et leur typologie. Enfin, une évaluation fiable des dommages au bâti nécessiterait des données complémentaires, par exemple des images à très haute résolution ou des observations de terrain.

Les surfaces brûlées par wilaya, commune et classe de sévérité nécessitent également des croisements spatiaux complémentaires pour être quantifiées précisément.


Auteur :** Mohamed Soidridine
Formation :** Master 2 Géographie, Aménagement, Environnement et Développement (GAED), parcours Géomatique et Modélisation Spatiale (GMS)
Établissement :** Aix-Marseille Université
Date :** Octobre 2026

Le rapport détaillé de l'étude sera disponible au format PDF dans ce dépôt.
