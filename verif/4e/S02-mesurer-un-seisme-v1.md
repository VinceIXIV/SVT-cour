# Vérification scientifique : 4e S02, Mesurer un séisme (v1)

- **Version :** v1 (relecture complète)
- **Date :** 16/11/2026
- **Séance :** `cours/4e/S02-mesurer-un-seisme/` (fiche de cours, fiche prof, fiche de révision, diaporama et notes ; les 12 diapositives ont été regardées)
- **Commit vérifié :** `c31b138` (HEAD de `main`)
- **Rapport précédent comparé :** aucun
- **Limite de la relecture :** les sites cités dans le tableau des sources (ISTerre, Comptes Rendus Géoscience, USGS…) n'étaient pas accessibles depuis l'environnement de relecture (hôtes bloqués). Les chiffres du Teil (tableau 3 de Beck et Schaming) et le délai de 770 s n'ont donc **pas pu être confrontés au texte de la source**. Le 770 s est cohérent avec un calcul de vraisemblance (distance Japon-Alpes-Maritimes d'environ 9 600 km, soit environ 85° ; temps de trajet de l'onde P d'environ 12 min 50 s). Les points ci-dessous reposent sur recherches web et recoupements.

**Verdict : corrections mineures.** Aucune erreur bloquante. Les définitions, l'échelle de magnitude (×10 en amplitude, ×32 en énergie) et les notions sont exactes. Restent une valeur du séisme du Japon à actualiser (USGS : 9,1) et quelques nuances d'énoncé.

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **Magnitude du Japon : « l'USGS a d'abord annoncé des valeurs plus faibles avant de la réviser à 9,0 » (fiche prof, partie 1, cas 2).**
  - **Constat :** la page officielle de l'USGS donne aujourd'hui **M 9,1 (Mww)** pour ce séisme (révision de 2016). La phrase de la fiche prof est donc périmée, et un élève qui cherche en ligne trouvera 9,1 (l'agence météorologique japonaise et l'EMSC retiennent 9,0).
  - **Correction proposée :** « 9,0 selon l'agence japonaise et l'EMSC ; l'USGS indique 9,1 depuis sa révision de 2016 : c'est la même grandeur, calculée avec des méthodes et des données différentes ». Garder 9,0 dans les documents élèves.
  - **Source :** [USGS, M 9.1 - 2011 Great Tohoku Earthquake](https://earthquake.usgs.gov/earthquakes/eventpage/official20110311054624120_30).

- [ ] **« C'est la même grandeur » à propos des magnitudes différentes du Teil (4,9 à 5,4) (fiche prof, partie B ; notes de la diapo 7 ; erreurs fréquentes ; questions d'élèves).**
  - **Constat :** les valeurs de 5,1 à 5,4 sont des magnitudes **locales** (ML), la valeur 4,9 est une magnitude de **moment** (Mw) : ce sont deux échelles différentes, calibrées pour concorder en moyenne, pas la même grandeur calculée autrement. Dire « même grandeur » est trop fort.
  - **Correction proposée :** « des échelles de magnitude différentes (locale, de moment) donnent des valeurs voisines mais pas identiques ; l'échelle de moment est la référence aujourd'hui ». Le rapport v1 de 4e S01 donne déjà ML 5,1 à 5,4 et Mw 4,9.

- [ ] **Chaque unité de magnitude = amplitude × 10 (fiche de cours B, diapo 7, fiche prof).**
  - **Constat :** exact pour les échelles de type Richter (ML, Ms), et c'est la formulation de l'USGS. La magnitude de moment, utilisée pour les quatre séismes de la diapo 7, est définie à partir du moment sismique (surface de rupture × déplacement × rigidité), et l'énergie ×32 (10^1,5) découle de cette définition. La fiche de cours dit pourtant que la magnitude « se calcule à partir de l'amplitude des ondes » et, au même endroit, que la faille et son déplacement comptent : les deux sont vrais, mais la phrase peut faire croire que Mw = amplitude.
  - **Correction proposée :** garder tel quel pour les élèves, mais ajouter à la fiche prof : « le facteur 10 en amplitude vaut pour les échelles de type Richter ; pour la magnitude de moment, c'est le facteur 32 en énergie qui est à retenir ». Facteur 32 : l'USGS arrondit à 32 (valeur exacte 31,6).
  - **Source :** [USGS, magnitude, énergie et intensité](https://www.usgs.gov/programs/earthquake-hazards/earthquake-magnitude-energy-release-and-shaking-intensity).

- [ ] **Corrigé de la question 10 de la fiche prof (partie 6) : « Pourquoi le séisme du Teil, de magnitude modérée, a-t-il une forte intensité près de l'épicentre ? »**
  - **Constat :** la réponse attendue (« parce que l'intensité décrit les effets en un lieu : forte près de l'épicentre, même si la magnitude est modérée ») est une tautologie ; elle n'explique pas. La vraie raison, vue en S01, est un foyer très superficiel (environ 1 km) ; la fiche de cours cite la profondeur, le sol et les constructions parmi les facteurs mais ne l'applique jamais au Teil. La diapo 10 et la fiche de cours D disent seulement « peut donc s'accompagner ».
  - **Correction proposée :** compléter : « parce que le foyer est très proche de la surface (environ 1 km) et que le séisme est superficiel ; l'intensité dépend aussi du sol et des constructions ». La réponse de la partie « Questions d'élèves » (« s'il est proche de la surface ») est déjà juste.

- [ ] **Amplitude des ondes (fiche de cours A, fiche de révision, diapo 6).**
  - **Constat :** « les ondes P ont une faible amplitude, les ondes S une amplitude plus grande » est vrai en général, mais ce sont les ondes de surface qui ont l'amplitude maximale, notamment pour un séisme lointain comme celui du Japon. La source citée est faible (corrigé d'activité de lycée, L'Étudiant).
  - **Correction proposée :** écrire « en général » et indiquer en fiche prof que les plus grandes amplitudes appartiennent aux ondes de surface, arrivées après les ondes S. Une source plus solide : Universalis ou le dossier ISTerre déjà cité.

- [ ] **Lecture du schéma d'intensité (fiche de cours, cas 1, partie D ; diapo 2).**
  - **Constat :** « elle est de IV à 63 km, de II à 313 km » se lit comme « l'intensité vaut IV à 63 km ». Selon la fiche prof, les valeurs sont des **distances maximales** auxquelles chaque degré a été relevé (IV signifie IV ou IV-V relevé jusqu'à 63 km). C'est cohérent à peu près, mais l'intensité à une distance donnée varie localement (la fiche prof le dit).
  - **Correction proposée :** reformuler en « l'intensité IV a été relevée jusqu'à 63 km ». Non vérifiable ici à la source (tableau 3 de Beck et Schaming inaccessible).

## Incohérences

- [ ] **Diapo 10 : « Japon : enregistré en France : magnitude 9,0 ».** La magnitude n'est pas déterminée par la seule station française ; la diapo, lue seule, le laisse croire. Les notes sont correctes. Proposition : « Japon : magnitude 9,0 ; premières ondes en France après environ 13 min ».
- [ ] **Diapo 5 (notes) : « ressort »** est cité parmi les éléments, alors que la fiche de cours dit une masse « suspendue à un bâti ». Aucune erreur, mais ajouter « ressort » au texte de la fiche de cours (partie A), car l'élève voit un ressort sur le schéma.

## Ce qui est solide

- Définitions : sismographe, sismogramme, amplitude, magnitude (valeur unique, indépendante du lieu), intensité (une valeur par lieu) ; distinction claire, et analogie de l'ampoule avec ses limites énoncées.
- Facteurs de l'échelle (×10, ×32), Chili 1960 (9,5), Kaikōura (7,8), Richter 1935, limites du modèle du sismographe (vertical seulement, numérique aujourd'hui) : conformes.
- Le Teil (Mw 4,9, ressenti à environ 300 km, intensité d'au moins V jusqu'à environ 50 km) et le délai de 770 s : cohérents entre les quatre documents et plausibles (voir limite). Barème de l'exercice : 2 + 3 + 4 + 1 = 10, structure type brevet respectée.
