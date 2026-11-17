# Vérification 3e S09 — v1

- **Version :** v1 (relecture complète)
- **Date :** 2026-11-17
- **Séance :** 3e S09 « Les liens de parenté entre espèces »
- **Commit vérifié :** edf45a9 (dossier de séance dernièrement modifié au commit 50ce4b4)
- **Rapport précédent :** aucun
- **Limite de cette relecture :** les hôtes `www.genome.gov` et `evolution.berkeley.edu` sont hors du réseau autorisé de la session ; les liens de la section « Sources vérifiées » n'ont donc pas pu être rouverts. Les points ci-dessous sur ces sources reposent sur la lecture des citations de la fiche prof et sur mes connaissances : ils sont signalés « à recontrôler ».

**Verdict : corrections mineures** (aucune erreur scientifique bloquante ; sourçage incomplet et partie A du cours trop courte).

## Métriques de longueur (fiches de cours .docx ; mots)

| Séance | A | B | C | D | E (retour) | Cours total | Fiche de cours total | Pages PDF | Fiche prof (mots) | Diapos |
|---|---|---|---|---|---|---|---|---|---|---|
| 3e S06 (pilote) | 168 | 107 | 111 | 157 | 129 | 674 | 937 | 4 | 4401 | 12 |
| 3e S07 | 114 | 160 | 146 | 152 | 157 | 731 | 1028 | 3 | 4215 | 12 |
| 3e S08 | 131 | 176 | 114 | 156 | 147 | 726 | 1049 | 4 | 4324 | 12 |
| **3e S09** | **60** | 144 | 170 | 128 | 112 | 616 | 886 | 4 | 3663 | 12 |

(Les comptes par partie incluent la ligne de titre.) Le total du cours de S09 est à -9 % de la pilote : pas de baisse globale nette. Mais la partie A est à -64 % et la fiche prof à -17 % de la pilote (-15 % de S08).

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **Chiffre « 30 millions de lettres »** — fiche de cours, partie D ; fiche prof, parties D, 9, 10 ; diapo 8 (notes) : « 1,23 % … environ 30 millions de lettres sur 2,4 milliards ». Le calcul 0,0123 × 2,4 × 10⁹ ≈ 29,5 M est juste, mais, de mémoire, l'article de 2005 annonce environ 35 millions de substitutions pour ce génome : l'écart (1,23 % porte sur des substitutions mesurées sur les régions alignées, avec filtrage) n'est pas expliqué. À recontrôler dans le texte de l'article (https://www.genome.gov/Pages/Research/DIR/Chimp_Analysis.pdf) ; sinon retirer « 30 millions » et écrire « plusieurs dizaines de millions de lettres ». Je n'ai pas pu l'ouvrir. *nouveau*
- [ ] **« Les mêmes os se retrouvent dans des fossiles d'Eusthenopteron »** — fiche de cours, cas 1. La phrase suit l'énumération « humérus, radius, cubitus, puis les os de la main » : elle laisse croire que les os de la main existent aussi chez Eusthenopteron. La fiche prof elle-même rapporte la source (Berkeley) qui ne cite que humérus, radius, cubitus. Correction : « les mêmes os du bras et de l'avant-bras (humérus, radius, cubitus) » ; reprendre dans la diapo 2 et la partie B (« On la retrouve chez un poisson fossile »). Source : https://evolution.berkeley.edu/examples-of-homology/legs-and-limbs (non rouverte).
- [ ] **« Un caractère partagé par plusieurs espèces est apparu chez leur ancêtre commun »** — fiche de cours, partie C. Formulation trop affirmative : un caractère partagé peut aussi résulter d'une évolution indépendante (convergence). La fiche prof traite bien la distinction homologie / ressemblance due au mode de vie, mais la phrase de l'élève dit « est apparu » sans réserve. Correction : « s'explique le plus simplement par son apparition chez leur ancêtre commun » (formulation déjà utilisée dans la fiche prof, questions d'élèves).
- [ ] **« Pas de queue » comme caractère discriminant** — partie C et tableau du doc. 1. Exact pour le tableau (truite, lézard, chat, chimpanzé, humain), mais certains singes non apparentés de près aux hominoïdes n'ont pas de queue visible (ex. macaque de Barbarie) : l'élève qui en connaît un peut objecter. Le prof est prévenu pour le coccyx, pas pour cela ; ajouter une ligne dans les erreurs fréquentes (« le caractère n'est pertinent que dans le tableau étudié ; un seul caractère ne suffit pas, c'est le nombre de caractères partagés qui compte »).
- [ ] **« Pourquoi dit-on que l'humain est un singe ? … groupe des hominoïdes »** — fiche prof, §10. Réponse floue : « hominoïdes » désigne les grands singes et l'humain, mais la question porte sur « singe » (la classification en simiiformes / primates n'est pas donnée) et la réponse n'est sourcée que par Vidal / Futura-Sciences « connus par extraits de recherche : à recontrôler ». Reformuler : « En classification, l'humain fait partie des primates et du groupe des grands singes (hominoïdes) ; dans le langage courant, « singe » ne désigne pas toujours la même chose », et sourcer par une page de référence (ex. Larousse, Muséum national d'histoire naturelle). *nouveau*
- [ ] **Sources non vérifiées dans la fiche prof, §12** — plusieurs lignes se terminent par « non vérifiée », « à recontrôler », « page non ouverte », « à sourcer par le validateur » : mammifères (poils, mamelles), truite sans membres à doigts, ancêtre commun hypothétique (Schoolmouv/Kartable, ce qui n'est pas une source primaire), « pas d'échelle », section « parenté » du programme. Le CLAUDE.md exige que ce qui ne peut pas être vérifié soit retiré ou reformulé. Les affirmations sont par ailleurs exactes (connaissances de base), mais il faut citer une source fiable (Eduscol, Larousse, Muséum) pour chacune.
- [ ] **Définition d'« espèce »** — fiche de cours, partie A ; fiche prof §4 A : « individus semblables qui peuvent se reproduire entre eux et avoir des descendants » ; diapo 5 : « individus interféconds ». Il manque « fertiles » (un âne et une jument ont un descendant, le mulet, mais stérile). Proposition : « …avoir des descendants eux-mêmes fertiles ». Source : programme de cycle 3/4 ou manuel. *nouveau*
- [ ] **Barème de l'exercice** — fiche prof §8 : le tableau donne 2 + 3 + 5 points tandis que le barème écrit donne « raisonnement /4 ; langue /1 » ; cohérent (5 = 4 + 1), mais la question 2 demande « les caractères » (pluriel) pour une réponse attendue unique (« absence de queue »). Reformuler la question au singulier ou « le ou les caractères ». 

## Incohérences

- [ ] **Partie A de la fiche de cours trop courte** — 60 mots (pilote S06 : 168, S07 : 114, S08 : 131), soit environ -64 % par rapport à la pilote. Elle annonce un « rappel » de trois notions (caractères héréditaires, ADN, mutations) mais en une phrase chacune : la mutation n'est définie ni comme changement de la séquence d'ADN (définition donnée en S08), ni comme rare, aléatoire et transmise seulement si elle touche un gamète ; l'ADN n'est pas décrit comme une séquence de « lettres », alors que la partie D et le cas 2 parlent de « lettres » ; le lien « différences qui s'accumulent » est posé sans explication. Manque à rédiger : (1) ADN = longue séquence de lettres portée par les chromosomes, identique d'une cellule à l'autre, copiée à chaque génération ; (2) mutation = modification d'une ou plusieurs lettres, rare, aléatoire, transmise si elle touche un gamète (même définition qu'en 3e S08) ; (3) pourquoi une mutation s'accumule au fil des générations.
- [ ] **Notion annoncée mais peu expliquée : l'ancêtre commun « déduit »** — la partie C affirme qu'il est « une déduction » sans montrer comment on le déduit. Correction : une phrase, ou un petit exemple (« les poils et les mamelles se retrouvent chez le chat, le chimpanzé et l'humain : il est plus simple d'admettre qu'ils les ont hérités d'un même ancêtre que de supposer trois apparitions séparées »).
- [ ] **Vocabulaire vs séances précédentes** — le terme « lettres » (ADN) et le mot « allèle » sont utilisés en S06-S08 ; S09 définit « mutation » plus brièvement que S08 (« une modification de l'ADN, rare et aléatoire », fiche prof §6) ; harmoniser avec la définition de S08. Aucun renvoi aux séances suivantes repéré (grep des fiches, diapo et notes : « séance suivante », « plus tard » : aucune occurrence).
- [ ] **Fiche prof moins étoffée** — 3663 mots contre 4401 (S06) : la partie A de la fiche prof est un simple rappel sans réponses détaillées (« Qu'est-ce qu'une mutation ? » ne figure que dans le tableau de §6). À compléter en même temps que la partie A de la fiche de cours.

## Ce qui est solide

Les deux cas d'usage sont fidèles aux sources citées (1,23 % de substitutions, ~2,4 Gb alignées, os du membre), avec la mise en garde correcte contre « 98,77 % identique » et contre « l'humain descend du chimpanzé ». Le raisonnement caractères partagés → arbre → confirmation par l'ADN est correct pour le niveau collège, et les cinq documents (cours, prof, notes, diaporama, révision) sont cohérents entre eux (même tableau de caractères, même schéma, mêmes réponses). Le bilan et l'exercice type brevet suivent la structure attendue (définition, relevé, explication).
