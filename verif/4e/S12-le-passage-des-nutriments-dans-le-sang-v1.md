# Vérification 4e S12 — v1 (relecture complète)

- **Date :** 2026-11-17
- **Séance :** 4e S12, « Le passage des nutriments dans le sang »
- **Commit vérifié :** 2c33b92 (HEAD de main : 4005564)
- **Rapport précédent :** aucun
- **Verdict : corrections mineures** (une simplification fausse à corriger, une partie de cours trop courte, une formulation de source à nuancer)

Limites : pubmed.ncbi.nlm.nih.gov n'est pas accessible depuis la session de relecture (domaine non autorisé) ; l'étude de Helander et Fändriks a été contrôlée par recherche web (résumé et BioNumbers). Les diapositives n'ont pas été converties en images : le contrôle porte sur le texte et les notes.

## Métriques de longueur (fiche de cours, mots)

| Séance | Part. A | B | C | D | E (retour) | Total fiche cours | Pages PDF | Mots fiche prof | Diapos |
|---|---|---|---|---|---|---|---|---|---|
| 4e S01 (pilote) | 135 | 88 | 142 | 90 | — (D = retour) | 647 | 3 | 3687 | 11 |
| 4e S10 | 105 | 101 | 140 | 102 | 143 | 900 | 3 | 3414 | 12 |
| 4e S11 | 86 | 121 | 96 | 100 | 157 | 850 | 3 | 3463 | 12 |
| **4e S12** | 83 | 86 | 93 | **36** | 128 | 725 | 3 | 3164 | 12 |

(Les totaux incluent cas d'usage, problématique et bilan. Les mots par partie excluent le titre de la partie.) Le total de la fiche de cours n'a pas baissé de façon nette par rapport à la pilote (+12 %), mais il baisse de 19 % par rapport à S10 et la fiche prof est la plus courte des quatre séances (−14 % par rapport à la pilote).

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **Acides gras « dans le sang » (simplification fausse)** — fiche de cours, partie C : « Les nutriments (glucose, acides aminés, acides gras) traversent la paroi de l'intestin, puis la paroi du capillaire, et entrent dans le sang » ; diapo 7 (notes et schéma : un seul capillaire sanguin) ; bilan. Les produits de la digestion des lipides sont reconstitués dans les cellules de la paroi en chylomicrons, trop gros pour entrer dans les capillaires sanguins : ils passent dans un vaisseau lymphatique de la villosité (chylifère) et rejoignent le sang plus loin. La fiche prof (précision 2) le sait, mais le texte élève l'affirme sans nuance, ce qui contredit la règle « simplifier oui, dire faux non ». Correction proposée : en C, nommer le glucose et les acides aminés seulement comme passant dans les capillaires sanguins, et ajouter une phrase du type « Une grande partie des lipides passe par un petit vaisseau lymphatique de la villosité avant de rejoindre le sang » (sans développer), ou, a minima, écrire « la plupart des nutriments » ; ajuster diapo 7, bilan et fiche de révision (points essentiels 5). Sources : Futura-Sciences, « Villosité » (capillaires sanguins et lymphatiques) ; Larousse, « Absorption intestinale » (chylomicrons) https://www.larousse.fr/encyclopedie/medical/absorption_intestinale/10867 ; Futura, « Chyle » https://www.futura-sciences.com/sante/definitions/medecine-chyle-7992/.
- [ ] **« Mesures de 2014 sur des prélèvements de volontaires »** — fiche de cours, cas 1 ; notes diapo 2 (« mesures de 2014 »). Le résumé de Helander et Fändriks (2014) donne 32 m² pour la muqueuse du tube digestif (≈ 2 m² pour le gros intestin) et un facteur 60-120 dû aux villosités et microvillosités. D'après BioNumbers (qui cite la page 685 de l'article), les ≈ 30 m² de l'intestin grêle sont **calculés** à partir d'un diamètre moyen de 2,5 cm et de facteurs d'amplification (villosités × 6,5, microvillosités × 13) : ce n'est pas une mesure directe sur des volontaires. La mention « volontaires » n'est pas étayée par ce que j'ai pu consulter. Correction proposée : « estimation de 2014 à partir de mesures de l'intestin » ou simplement « estimation récente (2014) ». Source : https://bionumbers.hms.harvard.edu/bionumber.aspx?id=111126 ; résumé https://pubmed.ncbi.nlm.nih.gov/24694282/ (non ouvert ici). Nouveau.
- [ ] **« Plus la surface est grande, plus les nutriments passent facilement »** — fiche de cours B. Formulation acceptable ; la fiche prof signale elle-même que la source de l'explication (« grosses molécules ne traversent pas la paroi ») n'est pas institutionnelle. Le tableau de sources cite des fiches de cours en ligne (SchoolMouv, etc.) : source faible pour un fait que l'enseignant non spécialiste devra défendre. Proposition : rattacher à un manuel de cycle 4 ou à Futura/Larousse, sinon reformuler : « les nutriments, petites substances, peuvent traverser la paroi » (la taille des molécules est bien la raison de la fragmentation par la digestion).
- [ ] **Question d'élève « Pourquoi manger du sucre fait monter la glycémie ? »** — fiche prof, §10 : « Le glucose, issu de la digestion, passe dans le sang ». Le sucre de table (saccharose) donne du glucose et du fructose ; la réponse est donc incomplète pour le « sucre » (vrai pour l'amidon). Correction proposée : « les glucides (amidon, sucre) sont digérés en glucose (et autres sucres simples) qui passent dans le sang ». Source : Larousse, absorption intestinale (lien ci-dessus) ; à vérifier dans un manuel. Nouveau.
- [ ] **Glycémie « 1 h 30 après un repas : moins de 1,40 g/L »** — cas d'usage 2. La source (e-sante.fr) est un site grand public ; le seuil est cohérent avec les usages cliniques mais mérite une source médicale (HAS, Assurance maladie, ameli.fr) dans le tableau de la fiche prof. Les deux valeurs du cas 2 ne montrent d'ailleurs « l'élévation » qu'indirectement (on ne donne pas la valeur maximale) : le raisonnement du cas 2 repose sur le texte « elle s'élève », pas sur un chiffre. Peu grave.
- [ ] **Source Helander non ouverte** — la fiche prof l'indique elle-même (« à recontrôler »). Le contrôle indépendant confirme 32 m² pour le tube digestif et 60-120 ; le chiffre « 30 m² » pour l'intestin grêle provient du corps de l'article (calcul), pas du résumé. Et Vidal est cité avec une « phrase tronquée » : la valeur 30 m² reste donc portée par une seule source indirecte. Acceptable, à garder signalé.

## Incohérences

- [ ] **Partie D réduite** — fiche de cours, partie D « Ce qui n'est pas absorbé » : 36 mots (3 phrases), contre 86-143 mots pour les parties des séances S01, S10 et S11 (−60 % ou plus). La question 4 de la problématique y reçoit une réponse sans explication : manque (a) ce que sont les résidus (ce que les enzymes n'ont pas digéré ou ce que la paroi n'a pas absorbé, par exemple les fibres) ; (b) le rôle du gros intestin (absorption d'une partie de l'eau, longueur 1,5 à 1,8 m déjà donnée en S11) ; (c) le sens « évacué » (anus, fèces) sans détail excessif. À étoffer à 80-100 mots. La diapo 8 est également la plus pauvre de la séance (deux étiquettes).
- [ ] **Longueur de l'intestin grêle** — S11 : « 6 à 7 mètres » (fiche de cours et notes) ; S12 : « 6,5 à 7 mètres » (d'après Vidal). Deux fourchettes pour la même grandeur dans le même chapitre. Harmoniser (au choix, avec source), par exemple « environ 6 à 7 m » partout, ou citer les deux fourchettes dans la fiche prof.
- [ ] **Dénomination des nutriments lipidiques** — S11 définit la digestion des lipides en « acides gras » (sans glycérol) ; S12 reprend « acides gras » comme passant dans le sang : cohérent entre les séances, mais la fiche S12 hérite de la simplification signalée plus haut.
- [ ] **Diapo 5, schéma « Nutriments / grosses molécules »** — la diapo 5 oppose « Aliments : grosses molécules » à « Nutriments » ; cohérent avec S11. Rien à corriger ; noté pour mémoire.
- Pas de renvoi aux séances suivantes : vérifié (« séance suivante », « plus tard », « prochaine », « on verra » absents). Les renvois aux séances **précédentes** (« voir la séance précédente », « voir S10 » dans la fiche prof et la diapo 3) sont corrects. La note de la diapo 1 « on ne détaille pas ici la circulation du sang dans tout le corps » est une mention de non-traitement, tolérable ; elle ne renvoie pas explicitement à une séance.
- Toutes les notions annoncées par la problématique sont expliquées (questions 1 à 4), la partie D étant trop brève (voir ci-dessus). Les microvillosités sont mentionnées dans les parties B et C du cours mais ne sont pas définies (le terme « microvillosités » apparaît dans le cas 1) : ajouter une définition courte (« replis encore plus petits de la surface des cellules de la paroi ») ou employer « replis plus petits », comme dans la partie B.

## Ce qui est solide

Chaîne centrale exacte : absorption surtout dans l'intestin grêle, villosités avec capillaires sanguins, gros intestin et absorption d'une partie de l'eau, glycémie à jeun 0,70-1,10 g/L. La fiche prof traite honnêtement l'écart 200 m² / 30 m², évite la régulation de la glycémie et signale la voie lymphatique ; l'analogie de la passoire est assortie de sa limite. Les quatre documents (cours, prof, diaporama, révision) sont cohérents entre eux, y compris le corrigé de l'exercice et le barème sur 10.
