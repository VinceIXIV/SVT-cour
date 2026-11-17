# Vérification 3e S08 — v1

- **Version :** v1 (relecture complète)
- **Date :** 2026-11-17
- **Séance :** 3e S08 — Les mutations, source de nouveauté
- **Commit des documents vérifié :** 65b640b (HEAD au moment de la relecture : edf45a9)
- **Rapport précédent comparé :** aucun pour S08 (rapport S07 v1 consulté pour le contexte)
- **Documents lus :** fiche de cours, fiche prof, fiche de révision (.docx), diaporama (.pptx, notes comprises). Diapositives non converties en images (schémas non contrôlés visuellement : seuls leurs textes et légendes ont été relus).

**Verdict : corrections mineures.** Aucune erreur scientifique bloquante ; chiffres cohérents et calculs exacts. Une incohérence de vocabulaire avec S06/S07 (« cellule reproductrice ») à corriger. Limite : le réseau de la session refusait genome.gov, sante.fr, planet-vie.ens.fr et academie-medecine.fr ; **aucun lien du tableau « Sources vérifiées » n'a pu être rouvert**. Les chiffres ont été contrôlés par recoupement interne et calcul (voir ci-dessous), pas par lecture des sources.

## Métriques de longueur (fiche de cours, mots)

| Séance | A | B | C | D | E (retour) | Total fiche | Cas d'usage | Pages PDF cours | Mots fiche prof | Diapos |
|---|---|---|---|---|---|---|---|---|---|---|
| 4e S01 (pilote 4e, pour mémoire) | 143 | 96 | 149 | 97 | – | 709 | 147 | 3 | 3 809 | 11 |
| 3e S06 (pilote 3e) | 168 | 107 | 111 | 157 | 130 | 937 | 181 | 4 | 4 401 | 12 |
| 3e S07 | 114 | 160 | 146 | 152 | 158 | 1 028 | 217 | 3 | 4 215 | 12 |
| **3e S08** | 131 | 176 | 114 | 156 | 148 | 1 049 | 256 | 4 | 4 324 | 12 |

(Comptage approximatif, titres de parties inclus.) Les parties de S08 sont à −22 % à +65 % de S06 : **aucune baisse nette (≥ 30 %)** ; la partie C (114 mots) est comparable à celle de S06 (111). Aucune partie réduite à une ou deux phrases. Les trois questions de la problématique sont réellement traitées (B, C, D). L'impression de raccourcissement ne se confirme pas pour cette séance.

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **« Cellule reproductrice » : définition différente de S06/S07 (nouveau).** Fiche de cours, partie C ; fiche prof, mots clés « mutation héréditaire » ; diapos 7 et 11. S06 et S07 définissent « gamètes, cellules reproductrices » (le gamète *est* la cellule reproductrice). S08 écrit « Les cellules reproductrices, elles, produisent les gamètes » et « une mutation dans une cellule reproductrice peut se retrouver dans un gamète » : ici la cellule reproductrice est une cellule qui *donne* des gamètes (lignée germinale). Un élève qui a lu S06/S07 est contredit. Correction proposée : dire « cellule de la lignée germinale (cellule qui produit les gamètes) » ou « cellule productrice de gamètes », et le définir ; ou garder « cellule reproductrice = gamète » et écrire « mutation présente dans un gamète » (valable aussi pour une mutation survenue dans le gamète lui-même). Source : NHGRI, « Germ cell / Mutation » (https://www.genome.gov/genetics-glossary/Mutation) (non rouvert).
- [ ] **« À n'importe quel endroit de l'ADN » (nouveau).** Fiche de cours, partie B : « Elle se produit au hasard, à n'importe quel endroit de l'ADN ». Le taux de mutation n'est pas uniforme (certaines positions mutent bien plus que d'autres). « Au hasard » est une simplification acceptable ; « à n'importe quel endroit » est trop fort. Correction proposée : « Elle se produit au hasard : on ne peut pas prévoir où ni quand » (retire l'affirmation d'uniformité). Source : Planet-Vie, taux de mutation par site (moyenne) (non rouvert).
- [ ] **Origine unique de l'allèle S (nouveau).** Cas 2 et partie E : « L'allèle S est apparu à la suite d'une mutation… Cette mutation a touché une cellule reproductrice : elle a été transmise de génération en génération ». La même mutation de la bêta-globine est apparue plusieurs fois indépendamment (haplotypes africains et indo-arabe, cités dans la littérature sur la drépanocytose). Le texte n'est pas faux mais suggère un événement unique ; en outre « a touché une cellule reproductrice » est une déduction, non une donnée de source. Correction proposée : en fiche prof, une ligne « l'allèle S est apparu plusieurs fois indépendamment ; on simplifie » ; en cours, « la mutation, survenue dans une cellule reproductrice, a pu être transmise ». Source à citer : Académie de médecine / Inserm (non rouverts) ou Orphanet, « Drépanocytose ».
- [ ] **« Les cellules du corps ne transmettent pas leur ADN aux enfants » (nouveau).** Partie C, 1re phrase. Formulation maladroite (les cellules du corps ont le même ADN que les autres) : l'idée est que leurs mutations n'arrivent pas dans les gamètes. Correction proposée : « Les cellules du corps ne donnent pas de gamètes : leur ADN n'est pas transmis aux enfants. »
- [ ] **Trois lignes du tableau de sources marquées « à recontrôler » (nouveau).** Fiche prof, section 12 : SchoolMouv (source secondaire, substitution/insertion/délétion), Drouin 2010 (UV, benzopyrène/p53), formulation « aléatoire ». Le contenu est exact au niveau collège (j'y souscris) mais le tableau demande une validation que cette relecture n'a pas pu faire. Correction proposée : remplacer SchoolMouv par une source institutionnelle (NHGRI, glossaire « Mutation » ou programme Eduscol) ; vérifier la citation Drouin.
- [ ] **« Presque toutes les mutations n'ont pas d'effet » (nouveau, mineur).** Fidèle à NHGRI (« presque aucune n'affecte notre santé ») et signalé dans la fiche prof comme simplification : à conserver, mais la fiche élève dit « presque aucune n'a d'effet sur la santé » alors que la partie D dit ensuite qu'elles « modifient un caractère » : bien distinguer « effet sur la santé » et « effet visible » (la fiche prof utilise tour à tour les deux).
- [ ] **Cas 1, « environ 70 lettres » (nouveau, mineur).** Calcul exact (6×10^9 × 1,2×10^-8 = 72) et fourchette 60–75 signalée en fiche prof : OK. Précision utile : ce sont des mutations *de novo* (apparues dans la lignée germinale d'un parent), pas « le génome d'un enfant diffère de celui de ses parents » au sens large (les deux génomes parentaux étant mélangés par le brassage). Formulation à préciser en fiche prof.
- [ ] **Brassage « ne modifie pas la séquence d'un gène » (nouveau, mineur).** Partie A. Valable au niveau collège (cohérent avec S07 : « ne crée pas de nouveaux allèles ») ; les échanges entre chromosomes sont hors programme. Aucune action requise sinon garder la cohérence de S07.

## Incohérences

- [ ] **Vocabulaire « cellule reproductrice »** : voir Points douteux (S06/S07 vs S08).
- Autres contrôles : définitions de gène et d'allèle identiques à S06 ; S07 dit que le brassage « ne crée pas de nouveaux allèles », S08 complète par la mutation : cohérent. Aucun renvoi à une séance suivante trouvé. Concordances : 70 / 6 milliards, 466 et 1 sur 1 736 (466/1 736 ⇒ environ 809 000 naissances, ordre de grandeur correct pour la France 2015), 40 %, chromosome 11, barème 2 + 3 + 4 + 1 = 10, légende du bilan (1 à 5) identique entre fiche prof, diapo 11 et fiche de cours. Fiche de révision : exercice conforme à la structure brevet (définir / relever / expliquer), documents cohérents avec le corrigé.

## Ce qui est solide

Définition de la mutation, origines (copie, agent mutagène), distinction mutation somatique / héréditaire, dépendance de l'effet à l'allèle, au nombre d'exemplaires et à l'environnement (cas du paludisme), formulation prudente « ni bonne ni mauvaise dans l'absolu », mise en garde contre la mutation « dirigée » par le besoin. Chiffres cohérents entre les quatre documents, aucun contenu hors programme (le code génétique est explicitement exclu), aucun contenu sensible.
