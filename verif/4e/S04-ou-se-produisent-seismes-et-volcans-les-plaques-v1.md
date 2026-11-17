# Vérification scientifique : 4e S04, Où se produisent séismes et volcans ? Les plaques (v1)

- **Version :** v1 (relecture complète)
- **Date :** 17/11/2026
- **Séance :** `cours/4e/S04-ou-se-produisent-seismes-et-volcans-les-plaques/` (textes des 4 .docx et du .pptx, notes comprises)
- **Commit vérifié :** `edf45a9`
- **Rapport précédent comparé :** aucun
- **Limites :** plusieurs sites (nationalgeographic.org, usgs.gov, larousse.fr…) sont bloqués par le proxy : je n'ai pas pu rouvrir ces liens. Seule vérification indépendante faite : recalcul des distances à la limite de plaques la plus proche avec le fichier PB2002 (GitHub fraxen/tectonicplates). Les pourcentages 94 / 88 / 24 % n'ont pas été recalculés (scripts et données `analyse/`, `donnees/` non publiés dans ce dépôt). Les diapositives n'ont pas été converties en images : je n'évalue pas les schémas.

**Verdict : corrections nécessaires (légères).** Aucune erreur de fait sur les chiffres contrôlés ; un point d'exactitude (ceinture de feu = limites de la plaque Pacifique) est répété dans les quatre documents et contredit l'exercice de la fiche de révision.

## Métriques de longueur (cohérence transverse)

| Mesure | S01 (pilote) | S02 | S03 | S04 |
| --- | --- | --- | --- | --- |
| Partie A (mots) | 140 | 299 | 95 | 122 |
| Partie B | 90 | 135 | 101 | 197 |
| Partie C | 145 | 107 | 101 | 196 |
| Partie D / E (« Retour… » incluse) | 90 | 131 | 197 (D) + 98 (retour) | 136 (retour) |
| Cas d'usage (mots) | 124 | 187 | 208 | 182 |
| Total fiche de cours | 673 | 922 | 888 | 950 |
| Pages du PDF de la fiche de cours | 3 | 3 | 4 | 3 |
| Mots de la fiche prof | 3 822 | 3 871 | 4 563 | 4 235 |
| Diapositives | 11 | 12 | 12 | 12 |

Aucune baisse : S04 est la fiche de cours la plus longue de la série (950 mots) et chaque partie dépasse ou égale la pilote (sauf A, 122 contre 140, soit -13 %). Pas d'Incohérence de longueur. Aucune partie réduite à une ou deux phrases ; la problématique est entièrement traitée (les trois questions ont leur partie). Aucun renvoi aux séances suivantes (recherche de « séance suivante », « on verra », « plus tard », « prochaine » : 0 occurrence).

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **La ceinture de feu = « limites de la plaque Pacifique avec les plaques voisines » : inexact et en contradiction avec l'exercice.**
  - **Où :** fiche de cours C et D (« La ceinture de feu du Pacifique correspond aux limites de la plaque Pacifique avec les plaques voisines »), fiche prof (partie D, EN BREF ; bilan), diapo 8 et 10 (notes), fiche de révision (vocabulaire).
  - **Problème :** une grande partie de la ceinture n'est pas une limite de la plaque Pacifique : la côte ouest de l'Amérique du Sud est la limite Nazca / Amérique du Sud, l'Amérique centrale la limite Cocos / Caraïbe, etc. L'exercice de la fiche de révision (Q2) fait justement trouver « Nazca / Amérique du Sud » : un élève attentif y verra une contradiction. La fiche prof (ligne « Ceinture de feu » du tableau de sources) cite elle-même plusieurs plaques (Nazca, Cocos, Amérique du Sud…).
  - **Correction proposée :** « La ceinture de feu du Pacifique suit les limites de plusieurs plaques autour de l'océan Pacifique (Pacifique, Nazca, Cocos, Amérique du Nord, Amérique du Sud, Eurasie, Philippines…) ».
  - **Source :** National Geographic Education, Plate Tectonics and the Ring of Fire (https://education.nationalgeographic.org/resource/plate-tectonics-ring-fire/) (non rouvert, accès bloqué).

- [ ] **Explication « les bords frottent et s'accrochent » appliquée à toutes les limites, alors que la partie A cite le milieu de l'Atlantique.**
  - **Où :** fiche de cours C (« leurs bords frottent et s'accrochent »), fiche prof partie C, diapo 8.
  - **Problème :** le mécanisme (frottement / accrochage) vaut surtout pour les limites où les plaques coulissent ou se rapprochent ; au milieu de l'Atlantique (cité en A comme bande de séismes et de volcans), les plaques s'écartent. L'élève n'a donc pas d'explication pour une des bandes citées. La fiche prof dit que les types de limites ne sont pas abordés, mais la formulation générale est trop restrictive.
  - **Correction proposée :** « Les plaques se déplacent sans cesse, l'une par rapport à l'autre : leurs bords frottent, se rapprochent ou s'écartent, et les roches y sont fortement déformées… ». Cela reste exact sans détailler les types de limites.
  - **Source :** USGS, What is an earthquake and what causes them to happen? (https://www.usgs.gov/faqs/what-earthquake-and-what-causes-them-happen) (non rouvert).

- [ ] **« Environ 90 % des séismes et environ 75 % des volcans actifs » : chiffres à nuancer, populations non comparables.**
  - **Où :** fiche de cours cas 2 et partie A, fiche de révision, diapo 3 (notes), fiche prof.
  - **Problème :** ces chiffres viennent de National Geographic. À ma connaissance l'USGS donne plutôt environ 90 % des séismes et 81 % des plus grands (non revérifié, accès bloqué). Surtout, « volcans actifs » (75 %) n'est pas la population de 447 volcans en éruption depuis 1900 utilisée à côté dans le cas 2 : l'élève peut les mélanger (88 % des 447 à moins de 300 km des limites, 75 % des « actifs » dans la ceinture, deux mesures différentes).
  - **Correction proposée :** écrire « d'après National Geographic » dans la fiche de cours, ou préciser « environ 75 % des volcans actifs » comme une donnée à part, distincte du décompte des 447 volcans ; vérifier la formulation USGS.
  - **Source :** https://education.nationalgeographic.org/resource/plate-tectonics-ring-fire/ ; USGS (https://www.usgs.gov/programs/earthquake-hazards) (à recontrôler).

- [ ] **Épaisseur de la lithosphère « plus de 200 km sous les continents ».**
  - **Où :** fiche de cours B, fiche prof (section 1, erreurs fréquentes), diapo 6.
  - **Problème :** présenté comme valeur générale ; sous les continents l'épaisseur est très variable (de l'ordre de 100 à 200 km selon les régions, davantage sous les très vieux continents). Source Larousse non rouverte. Formulation un peu trop catégorique pour un élève.
  - **Correction proposée :** « de moins de 100 km sous les océans à 150 km ou plus sous les continents (plus de 200 km par endroits) », ou « de l'ordre de 100 à 200 km » ; à confirmer à une source (Larousse, Eduscol).
  - **Source :** https://www.larousse.fr/encyclopedie/divers/lithosph%C3%A8re/186060 (non rouvert).

- [ ] **Chiffres 94 % / 88 % / 24 % non vérifiables par un tiers à partir du dépôt public.**
  - **Où :** fiche prof, section 12 (« le validateur peut relancer le script »).
  - **Problème :** `analyse/statistiques.py`, `donnees/seismes-usgs.csv` et `donnees/volcans-noaa.json` ne sont pas dans le dépôt public. J'ai pu recalculer seulement les distances avec PB2002 : **Le Teil ≈ 789 km, La Réunion ≈ 1 022 km, Hawaï ≈ 3 528 km** (fiche prof : 780, 1 000, 3 500 : confirmés). Les pourcentages ne sont pas contrôlés. Le fait que la méthode soit expliquée honnêtement dans la fiche prof est un bon point.
  - **Correction proposée :** publier le script et les données (ou un résumé des paramètres : tirage de points, nombre de points, seuil), ou indiquer dans la fiche prof une source externe. Aucune erreur constatée.

## Incohérences

Aucune incohérence de longueur ni de définition entre séances : « séisme = rupture de roches qui fait vibrer le sol » et « magma = roche fondue » sont cohérents avec S01 et S03 ; le terme « lithosphère » est défini pour la première fois en S04. Barème (/2, /3, /4, /1 = /10) et corrigé de l'exercice cohérents entre fiche prof et fiche de révision ; plan et numéros de diapositives cohérents entre fiche prof et diaporama (hors schémas non regardés).

## Ce qui est solide

Définitions de lithosphère, plaque et limite de plaques exactes ; vitesse des plaques (« quelques cm/an, comme les ongles ») sourcée USGS ; modèle du puzzle présenté avec sa limite ; exceptions (Le Teil, Hawaï, La Réunion) signalées honnêtement avec distances recalculées ; erreurs fréquentes bien choisies (plaque ≠ continent, pas d'« océan de magma »). Séance plus développée que la pilote.
