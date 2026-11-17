# Vérification 3e S18 — v4 (relecture de contrôle)

- **Date :** 2026-11-17
- **Séance :** 3e S18 — L'eau et les sols, des ressources à préserver
- **Commit vérifié :** 5827a64 (HEAD de main ; seul commit touchant S18 après 4005564)
- **Rapports précédents comparés :** v1, v2 (et v3 déposé en parallèle, non relu point par point) (tous deux sur 4005564, rédigés en parallèle) ; textes extraits de 4005564 et de HEAD puis comparés par diff (fiche de cours, fiche prof, fiche de révision, diaporama et notes).
- **Limite :** les hôtes SDES et USGS sont injoignables depuis cette session (réseau). Les chiffres SDES (28,9 Md m³, 45,2 %…) n'ont pas été rouverts ; ils restent « page lue par l'auteur » selon la fiche prof. Une recherche web confirme les ordres de grandeur USGS (2,5 %, ≈ 68-69 % de glaces, ≈ 30 % de nappes), pas les décimales. Seuls les textes des diapositives ont changé : les schémas n'ont pas été rendus en images (modifications limitées aux étiquettes).

**Verdict : corrections mineures** (aucune erreur bloquante ; la plupart des points de v1/v2 sont corrigés ; restent des sources « à recontrôler » et quelques nuances).

## Suivi des rapports précédents (v1 + v2 fusionnés)

| # | Point | Statut |
|---|---|---|
| 1 | Durée de formation du sol (100 à 10 000 ans) vs FAO ; attribution | Partiellement corrigé / contesté (voir P1) |
| 2 | Sources « à recontrôler » dans la fiche prof | Partiellement corrigé (P2) |
| 3 | Total 29,4 / 28,9 Md m³ | Corrigé (cours, diapo 2, notes, prof : « France métropolitaine, hors hydroélectricité », 100,1 % expliqué) |
| 4 | « Canaux » ambigu | Corrigé (« alimentation des canaux de navigation », restitution expliquée) |
| 5 | « A fait disparaître 19 263 ha » | Corrigé (corrigé de l'exercice : « transformés en espaces urbanisés ») ; résidu mineur P3 |
| 6 | Période du 64 % (depuis 2011) | Partiellement corrigé (P3) |
| 7 | Étiquette « autres (lacs, rivières, sols…) 1,2 % » | Corrigé (« dont lacs et rivières ») |
| 8 | Objectif prof « eau douce utilisable » | Corrigé |
| 9 | ZAN 2050 / −50 % en 2031 | Corrigé (mention « font l'objet de discussions ») |
| 10 | Mécanisme de l'érosion non expliqué (Q2) | Corrigé (pluie, vent, pente, sol nu, pratiques agricoles) |
| 11 | Partie C : échelle du monde, traitement des eaux, limiter l'érosion | Partiellement corrigé (P2 : FAO) |
| 12 | Lien avec S17 (renouvelable / non renouvelable ; mot « prélèvement ») | Partiellement corrigé (I1) |
| 13 | Cas 2 : que devient un sol perdu (imperméabilisation, lien avec l'eau) | Non corrigé (mineur, I2) |
| 14 | « Consommer » non défini | Corrigé |
| 15 | Fiche de révision pt 3 : trois usages sur cinq seulement | Non corrigé (mineur, hors périmètre scientifique) |
| 16 | « On dessale l'eau de mer » sans source | Non corrigé (réponse reformulée, toujours « à recontrôler ») |

Décompte : 9 Corrigés, 4 Partiellement corrigés, 3 Non corrigés (mineurs), 0 Contesté retenu.

## Métriques de longueur (mots de la fiche de cours .docx ; cours = parties A… + retour)

| Séance | A | B | C | D | E | Total cours | Total fiche | Pages PDF | Mots fiche prof | Diapos |
|---|---|---|---|---|---|---|---|---|---|---|
| 3e S06 (pilote) | 168 | 107 | 111 | 157 | 129 (retour) | 672 | 937 | 4 | 4689 | 12 |
| 3e S16 | 122 | 150 | 151 | 118 (retour) | – | 541 | 855 | 3 | 3334 | 11 |
| 3e S17 | 92 | 175 | 139 | 119 (retour) | – | 525 | 800 | 3 | 3425 | 11 |
| **3e S18 (HEAD)** | 255 | 228 | 166 | 138 (retour) | – | **787** | 1146 | 3 | 3991 | 11 |

Mesure faite par un même script sur les cinq documents (valeurs différentes de v1/v2 : ces rapports comptaient autrement ; seule la comparaison entre lignes compte). S18 a augmenté de ~50 % depuis 4005564 (parties A et B surtout) : aucune baisse par rapport à la pilote ; au contraire, la fiche dépasse la pilote. Aucune partie réduite à une ou deux phrases. Aucun renvoi aux séances suivantes (grep « séance, prochain, suivant, plus tard » : seulement l'en-tête « Séance 2 » et la mention « séance autonome »).

## Erreurs (bloquantes)

Aucune.

## Points douteux

- [ ] **P1 — Durée de formation du sol : borne basse « cent ans » et cohérence interne** — fiche de cours cas 2 et partie B ; fiche prof §12 ; diapo 6. Citation : « entre cent ans en région tropicale et dix mille ans dans les zones froides » puis « quelques centimètres… des centaines d'années » et, partie B, « à l'échelle d'une vie humaine, c'est très lent ». Le texte dit maintenant « d'après le programme » et « ordres de grandeur », ce qui est honnête, et la fiche prof cite une phrase du programme entre guillemets (non vérifiable ici : Eduscol injoignable ; la recherche web n'a pas retrouvé cette phrase). D'autres sources donnent des durées très supérieures : Académie des sciences (L. Lavelle) 1 000 à 100 000 ans pour 1 m de sol ; document ADEME/CITEO « plusieurs milliers d'années pour 1 cm ». Le « cent ans » reste voisin d'une vie humaine, d'où une tension avec « un sol perdu ne se reforme pas à l'échelle humaine ». Correction proposée : garder l'attribution au programme, ajouter dans la fiche prof une phrase honnête (« durées très variables selon les sources ; retenir : plusieurs siècles au minimum, souvent des milliers d'années ») et vérifier la citation du programme (BOEN spécial n° 31 du 30/07/2020). Sources : https://www.academie-sciences.fr/pdf/rapport/livret_9.pdf ; https://eduscol.education.fr/document/23335/download (non rouvert). Statut : repris de v1/v2.
- [ ] **P2 — Sources encore « à recontrôler » dans la fiche prof §12** : FAO (« appellent à inverser la dégradation des sols », extrait Terre-net), érosion/haies/labour (fiches ontariennes, wallonnes, neuchâteloises, aucune page française officielle), station d'épuration (extrait de recherche), définition du sol, dessalement. Les affirmations sont physiquement justes et courantes (érosion hydrique/éolienne, rôle du couvert végétal et des haies), mais la règle du dépôt demande une source ouverte. Correction : citer un lien lu (AFES, INRAE, Ministère de l'Agriculture, FAO « Journée mondiale des sols ») ou retirer la mention de la FAO en C (« des organisations internationales alertent… » sans nommer). Source indicative : https://www.fao.org/soils-portal/fr/. Statut : repris, partiel.
- [ ] **P3 — Périmètre du 64 % et de « urbanisés »** — cas 2 et partie B : « 19 263 hectares… urbanisés en 2023… Depuis 2011, 64 % de ces surfaces ont servi à l'habitat ». « Ces surfaces » renvoie à 2023 alors que le 64 % porte sur 2011-2023 (cf. v1) ; et le Cerema mesure la « consommation d'espaces NAF », pas toute transformation en espace urbanisé (la fiche prof le précise ; la fiche élève définit « urbanisation » par une transformation, ce qui est cohérent mais plus restrictif que la mesure). Correction : « Entre 2011 et 2023, 64 % des surfaces consommées l'ont été pour l'habitat » et « consommés (transformés en surfaces bâties ou aménagées) ». Source : Cerema/Portail de l'artificialisation (non rouvert). Statut : repris, résidu.
- [ ] **P4 — ZAN : statut juridique en 2026** — partie C. La loi n° 2021-1104 fixe bien −50 % de consommation d'ENAF 2021-2031 par rapport à 2011-2021 et ZAN 2050 ; la mention « font l'objet de discussions » est appropriée : une proposition de loi sénatoriale (mars 2025) et d'autres textes en 2026 visent à assouplir l'objectif 2031 ; je n'ai pas trouvé de confirmation d'adoption définitive. À faire : relire Légifrance avant la rentrée ; en C, « rythme de l'urbanisation » est une paraphrase de « consommation d'espaces NAF » (distincte de l'« artificialisation » du ZAN, notion nette) : acceptable si la fiche prof garde sa précision. Sources : https://www.senat.fr/leg/ppl24-124.pdf ; https://www.banquedesterritoires.fr/bilan-de-la-loi-climat-et-resilience-une-mise-en-oeuvre-incomplete-et-amoindrie. Nouveau (état 2026).

## Incohérences

- [ ] **I1 — Classement avec S17** : S17 définit la ressource renouvelable par un renouvellement « à l'échelle d'une vie humaine » et l'eau y est citée ; S18 classe l'eau douce « renouvelable » (cohérent) mais ne qualifie pas explicitement le sol de « non renouvelable à l'échelle humaine » (formule absente du cours B ; la conclusion en D est implicite). Par ailleurs « prélèvement » est défini comme « prélèvement et utilisation » en S17 et comme « action de prendre de l'eau… on mesure le volume » en S18 : les deux sont compatibles (S18 est un cas particulier) mais un élève peut hésiter ; harmoniser par une demi-phrase. Statut : repris, partiel.
- [ ] **I2 — Cas 2 : « Que devient un sol perdu ? »** Réponse limitée à « ne peut plus porter de cultures » : l'imperméabilisation n'est pas définie ni reliée à l'eau (ruissellement, infiltration), pourtant lien naturel avec la partie A. Une phrase suffirait. Mineur. Statut : repris.
- [ ] **I3 — Partie C, « échelle du monde »** : l'exemple se limite à la FAO ; aucun moyen concret. Acceptable pour le niveau, à rattacher à P2.
- Vocabulaire : « urbanisation », « érosion », « eau douce » cohérents entre cours, révision, prof et diaporama ; la fiche de révision (vocabulaire « prélèvement ») est alignée sur la fiche de cours.

## Ce qui est solide

Les corrections de v1/v2 ont été appliquées de façon cohérente dans les quatre documents (périmètre 28,9 Md m³, canaux, « consommer », mécanisme de l'érosion, étiquette « autres » du schéma, objectif de la fiche prof). Les ordres de grandeur d'eau sont cohérents (2,5 % = 1,74 + 0,76) et honnêtement présentés comme estimation de 1993. Les corrections ont allongé la fiche de cours sans créer d'erreur nouvelle détectée ; elle est désormais plus étoffée que la pilote.
