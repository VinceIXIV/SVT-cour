# Vérification scientifique : 4e S01, L'origine des séismes (v1)

- **Version :** v1
- **Date :** 16/11/2026
- **Séance :** `cours/4e/S01-origine-des-seismes/` (fiche de cours, fiche prof, fiche de révision, diaporama et notes)
- **Commit vérifié :** `27883c7`, dernier commit de `main` qui touche `cours/` (HEAD `4cb045e` ne modifie que `CLAUDE.md`)
- **Rapport précédent comparé :** aucun (première relecture)

**Verdict : corrections mineures.** Aucune erreur bloquante. Les chiffres des deux cas d'usage et les définitions sont exacts. Il reste une incohérence de schéma (le jeu de faille dessiné est l'inverse de celui du Teil et du modèle en compression) et quelques affirmations à nuancer.

---

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **Schémas des parties B et C et schéma bilan (fiche de cours p. 2-3, diapos 6, 7 et 10) : le jeu de faille dessiné ne correspond ni au modèle ni au cas du Teil.**
  - **Constat :** la faille plonge vers la droite. Le bloc de droite, situé au-dessus du plan de faille, descend (flèche vers le bas) et le bloc de gauche monte. C'est le jeu d'une **faille normale**, produite par un étirement (extension). Or le modèle de la partie A montre une **compression** (deux forces opposées qui poussent vers le centre de la règle). Et la faille de la Rouvière a joué en **faille inverse**, c'est-à-dire en compression. Juste à côté du schéma, le texte de la partie B dit pourtant : « rejouer lors d'un nouveau séisme, comme au Teil ».
  - **Pourquoi c'est un problème :** le schéma n'est pas faux en soi, mais l'enseignant non spécialiste ne pourra pas répondre si un élève relie les flèches du modèle aux flèches du bloc-diagramme.
  - **Correction proposée :** inverser le sens des flèches et de l'escarpement pour dessiner une faille inverse (le bloc au-dessus du plan de faille monte). Le schéma devient alors cohérent avec la règle comprimée et avec le Teil. À défaut, ajouter une phrase dans la fiche prof : « le schéma montre un exemple de jeu de faille ; au Teil, la faille a joué en compression (faille inverse) ».
  - **Sources :** [Ritz et al. 2020, HAL](https://hal.umontpellier.fr/hal-02924549) ; [Universalis, Séisme du Teil](https://www.universalis.fr/encyclopedie/seisme-du-teil-2019/2-une-rupture-sismique-bien-visible/) ; [Comptes Rendus Géoscience](https://comptes-rendus.academie-sciences.fr/geoscience/articles/10.5802/crgeos.280/). Ces trois sources décrivent une faille normale ancienne réactivée en faille inverse.

- [ ] **Dégâts du Teil attribués à une seule cause (fiche de cours, partie D : « c'est ce qui explique les dégâts importants » ; diapo 9 ; fiche prof, parties 4D et 8, corrigé de la question 3).**
  - **Constat :** les retours d'expérience attribuent aussi l'ampleur des dégâts à la **forte vulnérabilité du bâti ancien** (maçonnerie traditionnelle construite sans norme parasismique).
  - **Correction proposée :** écrire « c'est la principale explication des dégâts », et ajouter dans la fiche prof : « les bâtiments anciens, en pierre, étaient aussi très fragiles ». Le corrigé de la question 3 reste valable, car il s'appuie sur les documents.
  - **Sources :** [IRMa, Risques Infos n° 42](https://www.irma-grenoble.com/PDF/risques_infos/N42/risques_infos42.pdf) ; [IRMa, article sur le Teil](https://irma-grenoble.com/PDF/risques_infos/N42/42article04.pdf).

- [ ] **Seuil du séisme superficiel (fiche prof, partie 1 : « on parle de séisme superficiel quand le foyer est à moins de 60 km »).**
  - **Constat :** l'USGS fixe la limite des séismes superficiels à 70 km (superficiels de 0 à 70 km, intermédiaires de 70 à 300 km, profonds de 300 à 700 km). La source citée, SchoolMouv, est faible.
  - **Correction proposée :** écrire « à moins de 60 à 70 km selon les auteurs », ou retenir 70 km avec la source USGS.
  - **Source :** [USGS, Determining the depth of an earthquake](https://www.usgs.gov/programs/earthquake-hazards/determining-depth-earthquake).

- [ ] **Longueur de la rupture en surface au Teil (« ≈ 4,5 km » : cas 1, diapo 2, document 2 et corrigé de l'exercice).**
  - **Constat :** Ritz et al. (2020), la source citée dans le tableau des sources, donnent environ **5 km** ; d'autres textes donnent 4,5 km. L'écart est sans gravité.
  - **Correction proposée :** écrire « environ 5 km », ou citer précisément la source qui donne 4,5 km.
  - **Sources :** [Ritz et al. 2020](https://hal.umontpellier.fr/hal-02924549) ; [Techno-Science](https://www.techno-science.net/actualite/seisme-teil-vers-reevaluation-risque-sismique-france-europe-ouest-N19927.html).

## Incohérences

- [ ] **Tableau récapitulatif des questions (fiche prof, partie 6) et notes de la diapo 5.**
  - **Constat :** la question « Que se passe-t-il si les forces continuent de s'exercer ? » figure dans le tableau de la fiche prof, mais pas dans les notes de la diapo 5. L'enseignant qui suit seulement le diaporama ne la posera pas.
  - **Correction proposée :** l'ajouter aux notes de la diapo 5, ou la retirer du tableau.

- [ ] **Schéma bilan et exercice de la fiche de révision.**
  - **Constat :** il s'agit du même point que le premier point douteux. Le document 1 de l'exercice (coupe du Teil) ne montre aucun sens de déplacement, ce qui est correct. Le schéma bilan, lui, montre un jeu normal. Un élève qui compare les deux pourrait croire que la faille du Teil a joué en faille normale.
  - **Correction proposée :** elle découle de la correction du premier point douteux.

## Ce qui est solide

- **Le Teil :** date, heure, Mw 4,9 et magnitudes locales de 5,1 à 5,4, foyer à environ 1 km, faille de la Rouvière, déplacement d'environ 10 cm, 4 blessés. Tout est conforme aux sources.
- **Kaikōura :** Mw 7,8, au moins 21 failles, zone d'environ 180 km, décalage de 10 à 12 m sur la faille de Kekerengu, 2 morts. Tout est conforme aux sources, et le sens de décalage dessiné en vue du dessus est correct (décrochement dextre).
- **Notions :** les définitions (foyer, épicentre, faille, ondes sismiques), la vitesse d'environ 6 km/s et la profondeur maximale d'environ 700 km sont justes. Les limites du modèle de la règle sont bien expliquées. Les réponses aux questions d'élèves sont prudentes et exactes (prévision, zonage sismique, consignes de sécurité).
