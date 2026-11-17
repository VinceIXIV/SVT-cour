# Vérification 4e S15 — v1 (relecture complète)

- **Date :** 2026-11-17
- **Séance :** 4e S15 — L'utilisation des nutriments et du dioxygène par les cellules
- **Commit vérifié :** `2d03507` (dernier commit touchant `cours/4e/S15-…`)
- **Rapport précédent :** aucun
- **Périmètre :** fiche de cours, fiche prof, fiche de révision, diaporama (12 diapositives, notes comprises, diapos 2, 5 et 8 regardées en image).

## Verdict : corrections mineures

Aucune erreur scientifique bloquante : la respiration cellulaire (réactifs, produits, chaleur) est correcte pour le cycle 4, les valeurs de VO2 max sont confirmées, les calculs sont justes (35 × 70 = 2 450 ; 85 × 70 = 5 950). Restent des sources non ouvertes (Anses surtout), deux formulations trop absolues et un « pourquoi » annoncé mais pas expliqué (entraînement / VO2 max).

## Métriques de longueur

| Séance | A | B | C | D | E (retour) | Total cours | Total fiche de cours | Pages PDF cours | Mots fiche prof | Diapos |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4e S01 (pilote) | 135 | 88 | 142 | 90 | — | 455 | 647 | 3 | 3 687 | non mesuré |
| 4e S13 | 86 | 107 | 106 | 100 | 118 | 517 | 766 | 3 | 3 130 | non mesuré |
| 4e S14 | 110 | 105 | 98 | 106 | 133 | 552 | 797 | 3 | 3 339 | non mesuré |
| **4e S15** | **81** | **93** | **107** | **109** | **140** | **530** | **822** | **3** | **3 123** | **12** |

(Mots comptés sur le .docx, parties de « 3 Cours » seulement ; pour S01 la partie « Retour sur les cas d'usage » n'a pas été isolée par le comptage, total pilote sans elle.) Aucune baisse de longueur : les parties de S15 sont du même ordre que S13-S14 et que la pilote ; la plus courte est A (81 mots, −40 % par rapport à la pilote, mais elle contient définition, réactifs, produits et rôle du sang). Voir toutefois l'incohérence n° 1 (contenu, pas longueur).

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **1. Source Anses non ouverte et valeurs peu vérifiées** — fiche prof, §1 (cas 2) et §12 : « 2 600 kcal/j (18 à 69 ans) … 2 100 kcal/j (18 à 59 ans) … niveau d'activité 1,63, IMC 22 ». Le tableau lui-même indique « PDF non ouvert, à recontrôler ». Ma recherche confirme les valeurs 2 600 / 2 100 kcal/j, mais seulement par des sources secondaires (lanutrition.fr, support universitaire citant l'Anses) ; je n'ai trouvé aucune confirmation des tranches d'âge 18-69 / 18-59 ni du coefficient 1,63. De plus, la fiche prof signale elle-même que d'autres documents Anses donnent 2 200 et 1 800 kcal pour la même population : deux jeux de valeurs contradictoires pour le cas d'usage. *Correction :* ouvrir le rapport (NUT2012SA0103Ra-1.pdf) et noter la page ; sinon retirer les tranches d'âge précises et écrire « environ 2 600 kcal pour un homme et 2 100 kcal pour une femme, valeurs moyennes de référence ». Source : https://www.anses.fr/fr/system/files/NUT2012SA0103Ra-1.pdf
- [ ] **2. « Sans nutriments ni dioxygène, la cellule ne produit plus d'énergie » (trop absolu)** — fiche de cours B (« Un organisme qui ne reçoit plus de nutriments ou de dioxygène ne produit plus d'énergie ») ; diapo 6 notes ; fiche prof B (« sans nutriments ni dioxygène, la cellule ne fonctionne plus »). Sans dioxygène, certaines cellules produisent encore un peu d'énergie par fermentation (la fiche prof note elle-même que les fermentations ne sont pas au programme, §1 point 5). *Correction :* « ne produit plus (ou presque plus) d'énergie par la respiration cellulaire : ses cellules ne peuvent plus fonctionner normalement ». Source : Eduscol cycle 4 / manuels (respiration cellulaire).
- [ ] **3. Sources « à recontrôler » pour la chaleur, les mitochondries et les plantes** — fiche prof §1 et §10-12 : « la respiration cellulaire est la principale source de chaleur du corps » (Bordas et Digischool, « pages non ouvertes ») ; « les mitochondries sont le lieu de la respiration cellulaire » et « les plantes respirent aussi » (« source non consultée »). Les faits sont exacts, mais la règle du projet exige une source vérifiée. *Correction :* ouvrir une source (manuel, Eduscol) ou retirer l'adjectif « principale » (la fiche de cours dit seulement « une partie », ce qui est sûr). Fiche de cours : pas de problème.
- [ ] **4. Ambiguïté « consommation » / « mise à la disposition »** — fiche de cours cas 1, fiche de révision (doc. 1 « Consommation maximale de dioxygène »), diapo 2 : le VO2 max est défini (citation Vidal) comme dioxygène « mis à la disposition des cellules des muscles », puis nommé « consommation maximale ». Le sens usuel est bien la consommation maximale d'O2 par l'organisme, mais un élève lira deux grandeurs différentes. *Correction :* une phrase d'équivalence (« c'est la quantité maximale de dioxygène que les muscles peuvent utiliser par minute »). Source : Vidal, https://www.vidal.fr/sante/sport/corps-sport/poumons-pendant-sport.html (valeurs 35, 85 et 30-70 confirmées par recherche, page non ouvrable depuis la session).
- [ ] **5. « Pourquoi respire-t-on plus vite à l'effort ? » sans réponse prévue** — diapo 7 notes, question à poser. La ventilation n'est pas expliquée dans la fiche de cours de S15 et la fiche prof ne donne pas de réponse. *Correction :* ajouter la réponse attendue dans la note (les muscles consomment plus de dioxygène et rejettent plus de dioxyde de carbone, la ventilation augmente) ou changer la question. Source : séance 4e S13.
- [ ] **6. Définition de « énergie » vague** — fiche de révision et fiche prof (mots clés) : « Ce qui permet à une cellule de fonctionner ». Acceptable à ce niveau mais circulaire. *Correction suggérée :* ajouter « elle est libérée à partir des nutriments par la respiration cellulaire ». À la discrétion de l'auteur.

## Incohérences

- [ ] **1. Notion annoncée, non expliquée : pourquoi la consommation varie avec l'entraînement** — problématique, question 3 (« Pourquoi la consommation de dioxygène varie-t-elle ? ») ; fiche de cours C. Le cours explique la variation selon l'activité (repos / effort), mais pour le VO2 max il constate seulement « varie d'une personne à l'autre : 35 à 85 » sans dire pourquoi (entraînement, hérédité). La fiche prof demande « Pourquoi un sportif entraîné consomme-t-il plus de dioxygène à l'effort ? » (§ E) sans réponse dans le tableau du §6, et la question 3 du brevet repose sur ce raisonnement. *Explication manquante :* une ou deux phrases : le VO2 max est une valeur maximale, atteinte à l'effort maximal ; l'entraînement en endurance l'augmente (Vidal : +10 à 50 %, avec l'hérédité) ; un sportif ne consomme pas plus au repos. Source : Vidal (même page).
- [ ] **2. Écart entre la fiche de cours et la fiche prof sur l'activité** — cours C : « besoin quotidien d'environ 2 100 à 2 600 kcal, selon le sexe et l'activité » ; la source (point 1) donne ces chiffres pour un niveau d'activité médian et un sexe donné, les variations d'activité donnant d'autres valeurs. *Correction :* « selon le sexe ; ils varient aussi avec l'activité ».
- [ ] **3. Vocabulaire : « déchet cellulaire » = dioxyde de carbone et eau** — fiche prof et révision. Le dioxyde de carbone est un déchet ; l'eau produite est un produit de la réaction, pas à proprement parler un « déchet » (elle rejoint l'eau du corps, comme la fiche prof le dit au §10). Les définitions de S10 (non relues en détail) parlent de « produits ». *Correction :* harmoniser (« déchets et produits rejetés »). Cohérence avec S10 vérifiée uniquement sur la respiration cellulaire (même contenu : réactifs, produits, ventilation ≠ respiration cellulaire).
- Longueur : pas de baisse nette ni de partie réduite à une ou deux phrases ; les cinq parties font 81 à 140 mots avec définitions. Aucun renvoi aux séances suivantes (diapo 1 « Cette séance termine le chapitre » : simple mention du bilan, acceptable).

## Ce qui est solide

Définition et bilan de la respiration cellulaire conformes au programme de cycle 4 et distincts de la ventilation (point souvent confondu, bien traité en erreurs fréquentes), valeurs VO2 max et calculs en L/min corrects, schémas des diapos 2, 5 et 8 lisibles et cohérents avec les légendes du bilan, barème de l'exercice (2 + 3 + 5 = 10) cohérent avec le barème du brevet.
